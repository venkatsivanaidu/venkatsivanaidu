  ## Hi there 👋

<!--
**venkatsivanaidu/venkatsivanaidu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Portfolio of Y. Venkatsiva Naidu, B.Sc. Computer Science student and aspiring developer.">
<title>Y. Venkatsiva Naidu | Portfolio</title>

<style>
:root {
  --bg: #080b14;
  --surface: #101625;
  --surface2: #151e30;
  --text: #f1f5ff;
  --muted: #a3aec3;
  --accent: #62a5ff;
  --purple: #a78bfa;
  --border: rgba(255,255,255,.09);
}

* { margin:0; padding:0; box-sizing:border-box; scroll-behavior:smooth; }

body {
  background:var(--bg);
  color:var(--text);
  font-family:Arial, sans-serif;
  line-height:1.7;
}

a { color:inherit; text-decoration:none; }

.container {
  width:min(1100px,90%);
  margin:auto;
}

header {
  position:fixed;
  top:0; left:0;
  width:100%;
  z-index:100;
  background:rgba(8,11,20,.88);
  backdrop-filter:blur(15px);
  border-bottom:1px solid var(--border);
}

nav {
  min-height:72px;
  display:flex;
  align-items:center;
  justify-content:space-between;
}

.logo {
  font-size:21px;
  font-weight:bold;
  color:var(--accent);
}

.nav-links {
  display:flex;
  gap:27px;
  list-style:none;
}

.nav-links a {
  color:var(--muted);
  font-size:14px;
  transition:.3s;
}

.nav-links a:hover,
.nav-links a.active { color:var(--accent); }

.menu-btn {
  display:none;
  background:none;
  color:white;
  border:0;
  font-size:27px;
  cursor:pointer;
}

section { padding:90px 0; scroll-margin-top:65px; }

.hero {
  min-height:100vh;
  display:flex;
  align-items:center;
  padding-top:100px;
  background:
  radial-gradient(ellipse at 80% 35%,rgba(76,100,220,.19),transparent 45%),
  radial-gradient(ellipse at 10% 80%,rgba(99,70,180,.12),transparent 40%);
}

.hero-content { max-width:760px; }

.tag {
  display:inline-block;
  padding:7px 15px;
  border:1px solid rgba(98,165,255,.3);
  border-radius:30px;
  color:var(--accent);
  background:rgba(98,165,255,.08);
  font-size:13px;
  margin-bottom:22px;
}

.hero h1 {
  font-size:clamp(38px,7vw,72px);
  line-height:1.15;
  margin-bottom:18px;
}

.gradient {
  background:linear-gradient(90deg,#62a5ff,#b69aff);
  -webkit-background-clip:text;
  color:transparent;
}

.hero p {
  max-width:650px;
  color:var(--muted);
  font-size:17px;
  margin-bottom:28px;
}

.buttons { display:flex; flex-wrap:wrap; gap:14px; }

.btn {
  display:inline-block;
  padding:12px 22px;
  border-radius:8px;
  font-weight:bold;
  font-size:14px;
  transition:.3s;
  border:1px solid var(--border);
}

.btn-primary {
  background:var(--accent);
  color:#07101e;
  border-color:var(--accent);
}

.btn:hover { transform:translateY(-3px); }

.btn-outline:hover {
  border-color:var(--accent);
  color:var(--accent);
}

.section-title {
  font-size:32px;
  margin-bottom:10px;
}

.section-subtitle {
  color:var(--muted);
  margin-bottom:35px;
}

.about-box, .card, .contact-box {
  background:var(--surface);
  border:1px solid var(--border);
  border-radius:14px;
  padding:25px;
}

.about-box p { color:var(--muted); }

.grid {
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:20px;
}

.card {
  transition:.3s;
}

.card:hover {
  transform:translateY(-5px);
  border-color:rgba(98,165,255,.5);
}

.card h3 {
  margin-bottom:12px;
  color:var(--accent);
}

.card p { color:var(--muted); font-size:14px; }

.skills-grid {
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:15px;
}

.skill {
  background:var(--surface2);
  border:1px solid var(--border);
  padding:16px;
  text-align:center;
  border-radius:9px;
  font-size:14px;
  transition:.3s;
}

.skill:hover {
  border-color:var(--accent);
  color:var(--accent);
}

.project-number {
  color:var(--purple);
  font-size:13px;
  margin-bottom:10px;
}

.project-links {
  display:inline-block;
  margin-top:14px;
  color:var(--accent);
  font-size:13px;
}

.education-table {
  width:100%;
  border-collapse:collapse;
  background:var(--surface);
  border-radius:12px;
  overflow:hidden;
}

.education-table th,
.education-table td {
  text-align:left;
  padding:17px;
  border:1px solid var(--border);
  font-size:14px;
}

.education-table th {
  background:var(--surface2);
  color:var(--accent);
}

.strengths {
  display:flex;
  flex-wrap:wrap;
  gap:12px;
}

.strengths span {
  background:var(--surface2);
  padding:10px 16px;
  border-radius:30px;
  border:1px solid var(--border);
  font-size:14px;
}

.contact-box { text-align:center; }

.contact-box p { color:var(--muted); margin:12px 0; }

.contact-links {
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:14px;
  margin-top:22px;
}

footer {
  text-align:center;
  padding:25px;
  color:var(--muted);
  border-top:1px solid var(--border);
  font-size:13px;
}

.reveal {
  opacity:0;
  transform:translateY(20px);
  transition:opacity .7s, transform .7s;
}

.reveal.show {
  opacity:1;
  transform:translateY(0);
}

@media(max-width:750px) {
  .menu-btn { display:block; }

  .nav-links {
    display:none;
    position:absolute;
    top:72px;
    left:0;
    width:100%;
    background:#101625;
    flex-direction:column;
    padding:22px 5%;
    gap:18px;
    border-bottom:1px solid var(--border);
  }

  .nav-links.open { display:flex; }

  .grid { grid-template-columns:1fr; }
  .skills-grid { grid-template-columns:repeat(2,1fr); }
  section { padding:70px 0; }

  .education-table th,
  .education-table td {
    padding:10px 7px;
    font-size:12px;
  }
}

@media(max-width:400px) {
  .skills-grid { grid-template-columns:1fr 1fr; }
}
</style>
</head>

<body>

<header>
  <nav class="container">
    <a href="#home" class="logo">YSN.</a>

    <button class="menu-btn" id="menuBtn" aria-label="Toggle navigation">☰</button>

    <ul class="nav-links" id="navLinks">
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<main>

<!-- HOME -->
<section class="hero" id="home">
  <div class="container hero-content reveal">
    <span class="tag">● Fresher | Open to Opportunities</span>

    <h1>Hello, I'm<br>
      <span class="gradient">Y. Venkatsiva Naidu</span>
    </h1>

    <h2>Frontend Developer & Technology Enthusiast</h2>

    <p>
      B.Sc. Computer Science student passionate about web development,
      programming, Artificial Intelligence, 3D experiences and IoT.
      I enjoy learning new technologies and creating practical projects.
    </p>

    <div class="buttons">
      <a href="#projects" class="btn btn-primary">Explore My Projects</a>
      <a href="#contact" class="btn btn-outline">Contact Me</a>
      <a href="mailto:venkatsivanaidu17@gmail.com"
         class="btn btn-outline">Email Me</a>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="container reveal">
    <h2 class="section-title">About Me</h2>
    <p class="section-subtitle">Get to know me</p>

    <div class="about-box">
      <p>
        I am Y. Venkatsiva Naidu, a B.Sc. Computer Science student
        at Shri Gnanambica Degree College (Autonomous).
        I am interested in developing responsive websites,
        learning programming languages and exploring modern technologies.
        <br><br>
        I have explored projects involving Java, Python, MySQL,
        Three.js, Arduino and local AI models.
        I believe in continuous learning, creative thinking
        and improving my technical knowledge through practical work.
        <br><br>
        I am a fresher and open to internships and entry-level opportunities.
      </p>
    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills">
  <div class="container reveal">
    <h2 class="section-title">Technical Skills</h2>
    <p class="section-subtitle">Technologies and tools I have explored</p>

    <div class="skills-grid">
      <div class="skill">HTML5</div>
      <div class="skill">CSS3</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Responsive Design</div>
      <div class="skill">Three.js</div>
      <div class="skill">Java</div>
      <div class="skill">Python</div>
      <div class="skill">MySQL</div>
      <div class="skill">SQL</div>
      <div class="skill">Git</div>
      <div class="skill">GitHub</div>
      <div class="skill">Visual Studio Code</div>
      <div class="skill">Eclipse IDE</div>
      <div class="skill">Selenium WebDriver</div>
      <div class="skill">Artificial Intelligence</div>
      <div class="skill">Prompt Engineering</div>
      <div class="skill">Ollama</div>
      <div class="skill">Arduino</div>
      <div class="skill">ESP8266</div>
      <div class="skill">ESP32</div>
      <div class="skill">IoT</div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <div class="container reveal">
    <h2 class="section-title">My Projects</h2>
    <p class="section-subtitle">Academic and personal projects</p>

    <div class="grid">

      <article class="card">
        <div class="project-number">PROJECT 01</div>
        <h3>Interactive 3D Website</h3>
        <p><b>Technologies:</b> HTML, CSS, JavaScript, Three.js</p>
        <p>
          Created interactive 3D web page experiments.
          Practised displaying 3D models, animations
          and interactive website layouts.
        </p>
      </article>

      <article class="card">
        <div class="project-number">PROJECT 02</div>
        <h3>Automated Examination System</h3>
        <p><b>Technologies:</b> Java, Swing, MySQL</p>
        <p>
          Developing a desktop application concept
          with Admin, Teacher and Student modules.
          Includes planned student records,
          examination management and results features.
        </p>
      </article>

      <article class="card">
        <div class="project-number">PROJECT 03</div>
        <h3>Smart Home Automation</h3>
        <p><b>Technologies:</b> ESP8266, ESP32, Arduino, Wi-Fi</p>
        <p>
          Experimented with microcontrollers,
          relay-based device control and web-based
          home automation concepts.
        </p>
      </article>

      <article class="card">
        <div class="project-number">PROJECT 04</div>
        <h3>Local AI Assistant</h3>
        <p><b>Technologies:</b> Python, Ollama, Local AI Models</p>
        <p>
          Experimented with running AI models locally
          and exploring API-based interaction and
          possible embedded-device integration.
        </p>
      </article>

    </div>
  </div>
</section>

<!-- EDUCATION -->
<section id="education">
  <div class="container reveal">
    <h2 class="section-title">Education</h2>
    <p class="section-subtitle">My academic background</p>

    <div style="overflow-x:auto">
      <table class="education-table">
        <thead>
          <tr>
            <th>Qualification</th>
            <th>Institution</th>
            <th>Specialization</th>
            <th>Status</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>B.Sc.</td>
            <td>Shri Gnanambica Degree College (Autonomous)</td>
            <td>Computer Science</td>
            <td>Current Student</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</section>

<!-- INTERESTS AND STRENGTHS -->
<section id="interests">
  <div class="container reveal">
    <h2 class="section-title">Interests & Strengths</h2>
    <p class="section-subtitle">What motivates me</p>

    <div class="grid">
      <div class="card">
        <h3>Areas of Interest</h3>
        <p>
          Frontend Development, UI Design, Full-Stack Development,
          Artificial Intelligence, 3D Web Development,
          Robotics and Internet of Things.
        </p>
      </div>

      <div class="card">
        <h3>Personal Strengths</h3>
        <div class="strengths">
          <span>Quick Learner</span>
          <span>Creative Thinking</span>
          <span>Problem-solving</span>
          <span>Self-learning</span>
          <span>Adaptability</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="container reveal">
    <h2 class="section-title">Get In Touch</h2>
    <p class="section-subtitle">Let's connect and work together</p>

    <div class="contact-box">
      <h2 class="gradient">Have an opportunity?</h2>
      <p>
        I am open to internships, entry-level positions,
        collaborations and learning opportunities.
      </p>

      <div class="contact-links">
        <a class="btn btn-primary"
           href="mailto:venkatsivanaidu17@gmail.com">
          Send Email
        </a>

        <a class="btn btn-outline"
           href="tel:+918328186436">
          Call Me
        </a>

        <a class="btn btn-outline"
           href="https://github.com/venkatsivanaidu"
           target="_blank" rel="noopener">
          GitHub
        </a>

        <a class="btn btn-outline"
           href="https://www.linkedin.com/in/venkata-siva-ba833537b/"
           target="_blank" rel="noopener">
          LinkedIn
        </a>
      </div>

      <p style="margin-top:25px">
        Andhra Pradesh, India<br>
        +91 8328186436<br>
        venkatsivanaidu17@gmail.com
      </p>
    </div>
  </div>
</section>

</main>

<footer>
  <p>© <span id="year"></span> Y. Venkatsiva Naidu. All Rights Reserved.</p>
  <p>Designed and developed with HTML, CSS and JavaScript.</p>
</footer>

<script>
// Mobile navigation
const menuBtn = document.getElementById("menuBtn");
const navLinks = document.getElementById("navLinks");

menuBtn.addEventListener("click", () => {
  navLinks.classList.toggle("open");
  menuBtn.textContent =
    navLinks.classList.contains("open") ? "×" : "☰";
});

// Close menu after selecting a section
document.querySelectorAll(".nav-links a").forEach(link => {
  link.addEventListener("click", () => {
    navLinks.classList.remove("open");
    menuBtn.textContent = "☰";
  });
});

// Reveal animations
const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add("show");
    }
  });
}, { threshold: 0.12 });

document.querySelectorAll(".reveal").forEach(element => {
  observer.observe(element);
});

// Footer year
document.getElementById("year").textContent =
  new Date().getFullYear();

// Active navigation link
const sections = document.querySelectorAll("main section");
const links = document.querySelectorAll(".nav-links a");

window.addEventListener("scroll", () => {
  let current = "home";

  sections.forEach(section => {
    if (window.scrollY >= section.offsetTop - 150) {
      current = section.id;
    }
  });

  links.forEach(link => {
    link.classList.toggle(
      "active",
      link.getAttribute("href") === "#" + current
    );
  });
});
</script>

</body>
</html>
