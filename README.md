<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aman Khan | Web Developer Portfolio</title>
  <style>
    body {
      font-family: "Segoe UI", Arial, sans-serif;
      margin: 0;
      background: #f9f9f9;
      color: #222;
      scroll-behavior: smooth;
    }

    /* ---------- Header ---------- */
    header {
      background: #0077b6;
      color: #fff;
      position: fixed;
      width: 100%;
      top: 0;
      left: 0;
      padding: 15px 0;
      box-shadow: 0 3px 10px rgba(0,0,0,0.2);
      z-index: 1000;
    }

    .nav-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1100px;
      margin: auto;
      padding: 0 20px;
    }

    .logo {
      font-size: 1.5em;
      font-weight: bold;
      letter-spacing: 1px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 25px;
      margin: 0;
      padding: 0;
    }

    nav a {
      text-decoration: none;
      color: #fff;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #00b4d8;
    }

    /* ---------- Hero Section ---------- */
    .hero {
      background: linear-gradient(135deg, #0077b6, #00b4d8);
      color: #fff;
      text-align: center;
      padding: 150px 20px 100px;
    }

    .hero img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid #fff;
      margin-bottom: 20px;
    }

    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.1em;
      max-width: 600px;
      margin: 0 auto 25px;
    }

    .hero a {
      background: #fff;
      color: #0077b6;
      text-decoration: none;
      padding: 10px 25px;
      border-radius: 8px;
      font-weight: bold;
      transition: background 0.3s, transform 0.2s;
    }

    .hero a:hover {
      background: #00b4d8;
      color: #fff;
      transform: scale(1.05);
    }

    /* ---------- About Section ---------- */
    section {
      padding: 80px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: #0077b6;
      font-size: 2em;
      text-align: center;
      margin-bottom: 40px;
    }

    .about {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }

    .about p {
      max-width: 700px;
      font-size: 1.05em;
      line-height: 1.6;
    }

    /* ---------- Skills Section ---------- */
    .skills-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      margin-top: 20px;
    }

    .skill {
      background: #0077b6;
      color: #fff;
      padding: 10px 20px;
      border-radius: 20px;
      font-weight: 600;
      transition: transform 0.2s;
    }

    .skill:hover {
      transform: scale(1.1);
      background: #00b4d8;
    }

    /* ---------- Projects Section ---------- */
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
      transition: transform 0.3s;
    }

    .project:hover {
      transform: translateY(-5px);
    }

    .project h3 {
      color: #0077b6;
    }

    /* ---------- Contact Section ---------- */
    .contact p {
      text-align: center;
      font-size: 1.1em;
    }

    .contact a {
      color: #0077b6;
      text-decoration: none;
      font-weight: bold;
    }

    /* ---------- Footer ---------- */
    footer {
      background: #0077b6;
      color: #fff;
      text-align: center;
      padding: 15px 0;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      nav ul { flex-direction: column; gap: 10px; }
    }
  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <div class="nav-container">
      <div class="logo">Aman Khan</div>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- HERO / HOME -->
  <section class="hero" id="home">
    <img src="https://via.placeholder.com/150" alt="Aman Khan Photo">
    <h1>Hi, I'm Aman Khan</h1>
    <p>Final-year B.Sc. Computer Science student and aspiring Web Developer passionate about creating interactive, responsive, and user-friendly web applications.</p>
    <a href="#projects">View My Work</a>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <h2>About Me</h2>
    <div class="about">
      <p>
        I’m a passionate web developer and a final-year B.Sc. Computer Science student with strong skills in HTML, CSS, JavaScript, and Java.
        I enjoy solving problems, learning new technologies, and turning creative ideas into real web solutions.
        My goal is to build clean, efficient, and visually appealing applications that provide a great user experience.
      </p>
      <p><strong>Education:</strong> B.Sc. Computer Science (2022 – 2025) <br>
         <strong>Experience:</strong> Web Developer Intern at Prodigy Infotech</p>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills-list">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Java</div>
      <div class="skill">Python</div>
      <div class="skill">MySQL</div>
      <div class="skill">MongoDB</div>
      <div class="skill">Responsive Design</div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="projects-grid">
      <div class="project">
        <h3>Dental Clinic Management System</h3>
        <p>A desktop application built using Java and MySQL to manage appointments, patient records, and billing efficiently.</p>
      </div>
      <div class="project">
        <h3>Stopwatch Web Application</h3>
        <p>A simple stopwatch using HTML, CSS, and JavaScript with start, stop, reset, and lap time functionalities.</p>
      </div>
      <div class="project">
        <h3>Tic-Tac-Toe Game</h3>
        <p>An interactive two-player web game built using JavaScript logic for real-time gameplay and win detection.</p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>📧 Email: <a href="mailto:amankhan.dev@example.com">amankhan.dev@example.com</a></p>
    <p>🔗 LinkedIn: <a href="#">linkedin.com/in/amankhan</a></p>
    <p>💻 GitHub: <a href="#">github.com/amankhan-dev</a></p>
  </section>

  <footer>
    <p>© 2025 Aman Khan | All Rights Reserved</p>
  </footer>

</body>
</html>
