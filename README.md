# PORTFOLIO
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shubham Umraniya Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #1c1c1c, #0a0a0a);
      color: #ffffff;
      overflow-x: hidden;
      scroll-behavior: smooth;
    }

    section {
      padding: 90px 10%;
      position: relative;
    }

    .compartment {
      background: #ffffff;
      color: #000000;
      border-radius: 25px;
      padding: 60px;
      margin-top: 40px;
      box-shadow: 0 0 20px rgba(0,0,0,0.15);
      transition: transform 0.5s, box-shadow 0.5s;
    }

    .compartment:hover {
      transform: translateY(-10px);
      box-shadow: 0 15px 30px rgba(0,0,0,0.25);
    }

    header {
      padding: 20px 50px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      background: rgba(0,0,0,0.75);
      backdrop-filter: blur(12px);
      z-index: 1000;
    }

    .logo {
      font-size: 2rem;
      font-weight: 800;
      color: #4facfe;
    }

    nav a {
      margin-left: 25px;
      font-size: 1.2rem;
      color: #ffffff;
      text-decoration: none;
      transition: 0.3s;
    }

    nav a:hover {
      color: #4facfe;
    }

    .hero {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      text-align: center;
      background: linear-gradient(135deg, #4facfe, #235cff);
      animation: fadeIn 2s ease;
    }

    .hero h1 {
      font-size: 4rem;
      color: #ffffff;
      margin: 0;
      animation: slideIn 2s ease;
    }

    .hero p {
      font-size: 1.3rem;
      margin-top: 20px;
      color: #ffffff;
      animation: slideIn 2s ease 0.5s;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideIn {
      from { transform: translateY(20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    .skill-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 40px;
    }

    .skill-card {
      padding: 25px;
      font-size: 1.2rem;
      text-align: center;
      background: #ffffff;
      color: #000000;
      border-radius: 15px;
      box-shadow: 0 0 12px rgba(0,0,0,0.15);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .skill-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.2);
    }

    .contact-card {
      display: flex;
      flex-direction: column;
      gap: 20px;
      padding: 40px;
      border-radius: 30px;
      background: #f9f9f9;
      color: #000;
      box-shadow: 0 0 30px rgba(0,0,0,0.2);
      max-width: 500px;
      margin: 0 auto;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .contact-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 15px 30px rgba(0,0,0,0.25);
    }

    .contact-card div {
      display: flex;
      align-items: center;
      font-size: 1.2rem;
      gap: 15px;
    }

    .contact-card div i {
      font-size: 1.5rem;
      color: #4facfe;
    }

    .floating-icons {
      position: fixed;
      bottom: 25px;
      right: 25px;
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .floating-icons a {
      font-size: 30px;
      background: #1b1b1b;
      padding: 15px;
      border-radius: 50%;
      text-decoration: none;
      display: flex;
      justify-content: center;
      align-items: center;
      transition: 0.3s;
    }

    .floating-icons a:hover {
      background: #333;
      transform: scale(1.2);
    }

    .float-wa { color: #25d366; }
    .float-mail { color: #ff9800; }

    /* Typewriter effect */
    .typewriter {
      overflow: hidden;
      border-right: .15em solid #000;
      white-space: nowrap;
      animation: typing 4s steps(100, end), blink-caret .75s step-end infinite;
    }

    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }

    @keyframes blink-caret {
      from, to { border-color: transparent; }
      50% { border-color: black; }
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body>

<header>
  <div class="logo">SHUBHAM</div>
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#interests">Interests</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>HII I AM "SHUBHAM UMRANIYA"</h1>
  <p class="info">| ICT Engineer | Cybersecurity Analyst |</p>
</section>
<marquee behaviour="scroll" direction="right" scrollamount="15"> SHUBHAM UMRANIYA</marquee>

<section id="about">
  <div class="compartment">
    <h2>ABOUT ME</h2>
    <p class="compartment">
     Passionate ICT Engineer and Cybersecurity Enthusiast currently pursuing a Diploma in Information and Communication Technology at Marwadi University.
I am driven by a strong curiosity for technology and a commitment to learning, improving, and solving real-world problems. <br>

I enjoy working on network systems, secure communication technologies, and creative technical solutions. With a growing interest in cybersecurity, ethical hacking, and modern communication systems, I constantly explore new tools, concepts, and technologies to enhance my skill set.<br>
    </p>
  </div>
</section>

<section id="skills">
  <div class="compartment">
    <h2>SKILLS</h2>
    <div class="skill-grid">
      <div class="skill-card">HTML</div>
      <div class="skill-card">ENGLISH</div>
      <div class="skill-card">Java</div>
      <div class="skill-card">Cybersecurity</div>
      <div class="skill-card">Problem Solving</div>
      <div class="skill-card">Critical Thinking</div>
      <div class="skill-card">Communication</div>
      <div class="skill-card">Debugging</div>
    </div>
  </div>
</section>

<section id="interests">
  <div class="compartment">
    <h2>INTERESTS</h2>
    <p class="compartment">
    I am highly interested in Cybersecurity and ICT Engineering, with a strong passion for understanding how digital systems operate, communicate, and stay protected. I enjoy exploring network security, threat detection, ethical hacking concepts, and designing secure IT infrastructures.
Alongside this, I am fascinated by ICT engineering—especially how communication systems, networks, and modern technologies can be optimized to improve performance and reliability.
Together, these domains drive me to continuously learn, analyze complex problems, and work towards building secure, efficient, and future-ready technological solutions.
    </p>
  </div>
</section>

<section id="contact">
  <div class="compartment contact-card">
    <h2>Contact Me</h2>
    <div><i class="fas fa-phone"></i> <a href="tel:+919328529576">+91 9328529576</a></div>
    <div><i class="fas fa-envelope"></i> <a href="mailto:shubham.umraniya128127@marwadiuniversity.ac.in">shubham.umraniya128127@marwadiuniversity.ac.in</a></div>
    <div><i class="fas fa-stream"></i> ICT DIPLOMA</div>
    <div><i class="fas fa-graduation-cap"></i> Semester: 3rd</div>
    
  </div>
</section>

<script>
  function openWhatsApp() {
    const wa_me = "https://wa.me/919328529576?text=Hello%20Shubham%2C%20I%20visited%20your%20portfolio%20website!";
    window.open(wa_me, '_blank');
  }
</script>

</body>
</html>
