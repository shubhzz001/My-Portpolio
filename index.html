<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shubham Somase — Electrical Engineer</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<style>
  :root {
    --purple: #7c3aed;
    --purple-light: #a78bfa;
    --purple-dark: #4c1d95;
    --red: #dc2626;
    --red-light: #f87171;
    --bg: #080810;
    --bg2: #0d0d18;
    --bg3: #111120;
    --text: #e2e8f0;
    --muted: #94a3b8;
    --border: rgba(124,58,237,0.2);
    --card-bg: rgba(13,13,24,0.9);
    --gold: #f59e0b;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{font-family:'Segoe UI',system-ui,sans-serif;background:var(--bg);color:var(--text);overflow-x:hidden;}

  /* NAV */
  nav{position:fixed;top:0;left:0;right:0;z-index:200;display:flex;align-items:center;justify-content:space-between;padding:1rem 3rem;background:rgba(8,8,16,0.85);backdrop-filter:blur(16px);border-bottom:1px solid var(--border);}
  .nav-logo{font-size:1rem;font-weight:800;color:var(--purple-light);letter-spacing:0.05em;}
  .nav-links{display:flex;gap:1.75rem;list-style:none;}
  .nav-links a{text-decoration:none;color:var(--muted);font-size:0.8rem;letter-spacing:0.05em;text-transform:uppercase;transition:color 0.2s;}
  .nav-links a:hover{color:var(--purple-light);}

  /* HERO */
  #hero{position:relative;height:100vh;display:flex;align-items:center;justify-content:center;overflow:hidden;}
  #canvas3d{position:absolute;inset:0;z-index:0;}
  .hero-left{position:relative;z-index:1;padding:2rem 3rem;max-width:680px;}
  .hero-eyebrow{font-size:0.8rem;letter-spacing:0.18em;text-transform:uppercase;color:var(--red-light);margin-bottom:1.25rem;display:flex;align-items:center;gap:0.6rem;}
  .hero-eyebrow::before{content:'';display:inline-block;width:28px;height:2px;background:var(--red);}
  .hero-greeting{font-size:clamp(1rem,2vw,1.2rem);color:var(--muted);margin-bottom:0.5rem;font-weight:400;}
  .hero-name{font-size:clamp(3rem,7vw,5.5rem);font-weight:900;line-height:1;letter-spacing:-0.03em;color:#fff;margin-bottom:0.2rem;}
  .hero-name .accent{color:var(--purple-light);}
  .hero-roles{font-size:clamp(1rem,2vw,1.25rem);color:var(--muted);margin:1rem 0 0.5rem;font-weight:400;}
  .hero-roles span{color:#fff;font-weight:600;}
  .hero-pipe{color:var(--purple);margin:0 0.5rem;}
  .hero-sub{font-size:0.95rem;color:var(--muted);line-height:1.8;max-width:480px;margin:1rem 0 2rem;}
  .hero-cta{display:flex;gap:1rem;flex-wrap:wrap;}
  .btn-primary{padding:0.8rem 2.2rem;border-radius:6px;background:var(--purple);color:#fff;border:none;cursor:pointer;font-size:0.9rem;font-weight:700;text-decoration:none;display:inline-block;transition:all 0.2s;letter-spacing:0.03em;}
  .btn-primary:hover{background:#6d28d9;transform:translateY(-2px);box-shadow:0 8px 24px rgba(124,58,237,0.4);}
  .btn-outline{padding:0.8rem 2.2rem;border-radius:6px;background:transparent;color:var(--muted);border:1px solid rgba(148,163,184,0.3);cursor:pointer;font-size:0.9rem;font-weight:600;text-decoration:none;display:inline-block;transition:all 0.2s;}
  .btn-outline:hover{border-color:var(--purple-light);color:var(--purple-light);transform:translateY(-2px);}
  .scroll-hint{position:absolute;bottom:2.5rem;left:3rem;z-index:1;display:flex;align-items:center;gap:0.75rem;color:var(--muted);font-size:0.75rem;letter-spacing:0.1em;text-transform:uppercase;}
  .scroll-line{width:40px;height:1px;background:var(--muted);animation:scroll-grow 2s ease-in-out infinite;}
  @keyframes scroll-grow{0%,100%{width:20px;opacity:0.4}50%{width:50px;opacity:1}}

  /* SECTIONS */
  .section-wrap{padding:7rem 3rem;max-width:1200px;margin:0 auto;}
  .section-label{font-size:0.72rem;letter-spacing:0.18em;text-transform:uppercase;color:var(--purple-light);margin-bottom:0.6rem;display:flex;align-items:center;gap:0.6rem;}
  .section-label::before{content:'';display:inline-block;width:20px;height:1px;background:var(--purple-light);}
  .section-title{font-size:clamp(2rem,3.5vw,3rem);font-weight:800;color:#fff;line-height:1.1;margin-bottom:1rem;letter-spacing:-0.02em;}
  .section-sub{color:var(--muted);max-width:560px;line-height:1.8;font-size:0.95rem;margin-bottom:3rem;}

  /* ABOUT */
  .about-grid{display:grid;grid-template-columns:1fr 1.6fr;gap:5rem;align-items:center;}
  .avatar-wrap{position:relative;}
  .avatar-box{aspect-ratio:1;border-radius:16px;background:linear-gradient(135deg,#1a0a3d,#0d0d18);border:1px solid var(--border);display:flex;align-items:center;justify-content:center;font-size:5rem;font-weight:900;color:var(--purple-light);overflow:hidden;position:relative;}
  .avatar-box::after{content:'';position:absolute;bottom:0;left:0;right:0;height:3px;background:linear-gradient(90deg,var(--purple),var(--purple-light));}
  .avatar-glow{position:absolute;width:200px;height:200px;border-radius:50%;background:radial-gradient(circle,rgba(124,58,237,0.25),transparent 70%);top:50%;left:50%;transform:translate(-50%,-50%);pointer-events:none;}
  .avatar-initials{position:relative;z-index:1;}
  .about-text p{color:var(--muted);line-height:1.9;margin-bottom:1rem;font-size:0.95rem;}
  .stat-row{display:flex;gap:2.5rem;margin-top:2rem;flex-wrap:wrap;padding-top:2rem;border-top:1px solid var(--border);}
  .stat{text-align:left;}
  .stat-num{font-size:1.8rem;font-weight:900;color:#fff;line-height:1;}
  .stat-num span{color:var(--purple-light);}
  .stat-label{font-size:0.7rem;color:var(--muted);text-transform:uppercase;letter-spacing:0.1em;margin-top:0.3rem;}
  .edu-list{margin-top:2rem;display:flex;flex-direction:column;gap:0.75rem;}
  .edu-item{padding:0.9rem 1.25rem;border-radius:8px;border:1px solid var(--border);background:var(--card-bg);}
  .edu-deg{font-size:0.9rem;font-weight:700;color:#fff;}
  .edu-info{display:flex;justify-content:space-between;margin-top:0.2rem;}
  .edu-school{font-size:0.78rem;color:var(--purple-light);}
  .edu-year{font-size:0.78rem;color:var(--muted);}
  .edu-grade{font-size:0.78rem;color:var(--gold);}

  /* SKILLS */
  .skills-cats{display:grid;grid-template-columns:1fr 1fr;gap:2rem;}
  .skill-cat-title{font-size:0.78rem;text-transform:uppercase;letter-spacing:0.12em;color:var(--purple-light);margin-bottom:1rem;font-weight:700;}
  .skill-chips{display:flex;flex-wrap:wrap;gap:0.6rem;}
  .chip{padding:0.45rem 1rem;border-radius:6px;border:1px solid var(--border);background:var(--card-bg);font-size:0.8rem;color:var(--text);transition:all 0.2s;cursor:default;}
  .chip:hover{border-color:var(--purple);color:var(--purple-light);background:rgba(124,58,237,0.08);transform:translateY(-1px);}

  /* PROJECTS */
  .projects-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(340px,1fr));gap:1.5rem;}
  .project-card{border-radius:12px;border:1px solid var(--border);background:var(--card-bg);padding:2rem;transition:all 0.3s;position:relative;overflow:hidden;display:flex;flex-direction:column;}
  .project-card:hover{border-color:var(--purple);transform:translateY(-4px);box-shadow:0 20px 50px rgba(0,0,0,0.5);}
  .project-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,var(--purple),var(--purple-light));opacity:0;transition:opacity 0.3s;}
  .project-card:hover::before{opacity:1;}
  .project-num{font-size:0.7rem;color:var(--purple);font-weight:700;letter-spacing:0.15em;margin-bottom:0.75rem;}
  .project-title{font-size:1.05rem;font-weight:800;color:#fff;margin-bottom:0.35rem;line-height:1.3;}
  .project-period{font-size:0.75rem;color:var(--muted);margin-bottom:1rem;}
  .project-desc{font-size:0.85rem;color:var(--muted);line-height:1.8;flex:1;}
  .project-tags{display:flex;gap:0.5rem;flex-wrap:wrap;margin-top:1.25rem;}
  .ptag{font-size:0.7rem;padding:0.25rem 0.6rem;border-radius:4px;background:rgba(124,58,237,0.12);color:var(--purple-light);border:1px solid rgba(124,58,237,0.25);}
  .project-link{margin-top:1.25rem;display:inline-flex;align-items:center;gap:0.4rem;font-size:0.78rem;color:var(--purple-light);text-decoration:none;border-top:1px solid var(--border);padding-top:1rem;}
  .project-link:hover{color:#fff;}
  .award-badge{display:inline-flex;align-items:center;gap:0.4rem;margin-top:0.75rem;padding:0.3rem 0.75rem;border-radius:6px;background:rgba(245,158,11,0.1);border:1px solid rgba(245,158,11,0.3);font-size:0.75rem;color:var(--gold);width:fit-content;}

  /* PUBLICATIONS */
  .pub-list{display:flex;flex-direction:column;gap:1.25rem;}
  .pub-card{border-radius:10px;border:1px solid var(--border);background:var(--card-bg);padding:1.5rem;display:flex;gap:1.25rem;transition:border-color 0.2s;}
  .pub-card:hover{border-color:var(--purple);}
  .pub-num{width:36px;height:36px;border-radius:8px;background:rgba(124,58,237,0.15);border:1px solid var(--border);display:flex;align-items:center;justify-content:center;font-size:0.8rem;font-weight:800;color:var(--purple-light);flex-shrink:0;}
  .pub-type{font-size:0.68rem;text-transform:uppercase;letter-spacing:0.12em;color:var(--purple-light);margin-bottom:0.3rem;}
  .pub-title{font-size:0.95rem;font-weight:700;color:#fff;line-height:1.5;}
  .pub-venue{font-size:0.78rem;color:var(--muted);margin-top:0.3rem;}

  /* PATENTS */
  .patents-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:1.25rem;}
  .patent-card{border-radius:10px;border:1px solid var(--border);background:var(--card-bg);padding:1.5rem;transition:all 0.2s;position:relative;}
  .patent-card:hover{border-color:var(--purple);transform:translateY(-2px);}
  .patent-icon{font-size:1.5rem;margin-bottom:0.75rem;}
  .patent-title{font-size:1rem;font-weight:800;color:#fff;margin-bottom:0.4rem;line-height:1.3;}
  .patent-appno{font-size:0.78rem;color:var(--purple-light);margin-bottom:0.3rem;font-family:monospace;}
  .patent-date{font-size:0.75rem;color:var(--muted);margin-bottom:0.75rem;}
  .patent-link{display:inline-flex;align-items:center;gap:0.35rem;font-size:0.75rem;color:var(--purple-light);text-decoration:none;padding:0.3rem 0.75rem;border-radius:5px;border:1px solid var(--border);transition:all 0.2s;}
  .patent-link:hover{border-color:var(--purple);color:#fff;background:rgba(124,58,237,0.1);}

  /* CERTIFICATIONS */
  .certs-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:1rem;}
  .cert-card{border-radius:10px;border:1px solid var(--border);background:var(--card-bg);padding:1.25rem 1.5rem;display:flex;flex-direction:column;gap:0.5rem;transition:all 0.2s;}
  .cert-card:hover{border-color:var(--purple);transform:translateY(-2px);}
  .cert-issuer-row{display:flex;align-items:center;gap:0.5rem;margin-bottom:0.25rem;}
  .cert-badge{width:28px;height:28px;border-radius:6px;display:flex;align-items:center;justify-content:center;font-size:0.9rem;flex-shrink:0;}
  .cert-issuer-name{font-size:0.72rem;text-transform:uppercase;letter-spacing:0.1em;color:var(--muted);}
  .cert-name{font-size:0.92rem;font-weight:700;color:#fff;line-height:1.4;}
  .cert-bottom{display:flex;align-items:center;justify-content:space-between;margin-top:0.25rem;}
  .cert-date{font-size:0.72rem;color:var(--muted);}
  .cert-link{font-size:0.72rem;color:var(--purple-light);text-decoration:none;padding:0.2rem 0.6rem;border:1px solid var(--border);border-radius:4px;transition:all 0.2s;}
  .cert-link:hover{border-color:var(--purple);color:#fff;}
  .cert-check{color:#22c55e;font-size:1rem;}

  /* EXTRACURRICULARS */
  .extra-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(340px,1fr));gap:1.5rem;}
  .extra-card{border-radius:12px;border:1px solid var(--border);background:var(--card-bg);padding:1.75rem;transition:all 0.3s;position:relative;overflow:hidden;}
  .extra-card:hover{border-color:var(--purple);transform:translateY(-3px);}
  .extra-card::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px;background:var(--purple);opacity:0;transition:opacity 0.3s;}
  .extra-card:hover::before{opacity:1;}
  .extra-role{font-size:1rem;font-weight:800;color:#fff;margin-bottom:0.2rem;}
  .extra-org{font-size:0.85rem;color:var(--purple-light);margin-bottom:0.2rem;}
  .extra-period{font-size:0.75rem;color:var(--muted);margin-bottom:1rem;}
  .extra-desc{font-size:0.82rem;color:var(--muted);line-height:1.8;margin-bottom:1.25rem;}
  .extra-skills{display:flex;flex-wrap:wrap;gap:0.4rem;margin-bottom:1rem;}
  .extra-skill{font-size:0.68rem;padding:0.2rem 0.55rem;border-radius:4px;background:rgba(124,58,237,0.1);color:var(--purple-light);border:1px solid rgba(124,58,237,0.2);}
  .extra-links{display:flex;gap:0.5rem;flex-wrap:wrap;}
  .extra-link{font-size:0.72rem;color:var(--muted);text-decoration:none;padding:0.25rem 0.65rem;border:1px solid var(--border);border-radius:4px;transition:all 0.2s;}
  .extra-link:hover{border-color:var(--purple-light);color:var(--purple-light);}

  /* SOFT SKILLS */
  .soft-skills-wrap{display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;}
  .soft-skill-item{display:flex;gap:1rem;align-items:flex-start;padding:1.25rem;border-radius:10px;border:1px solid var(--border);background:var(--card-bg);transition:border-color 0.2s;}
  .soft-skill-item:hover{border-color:var(--purple);}
  .soft-icon{width:38px;height:38px;border-radius:8px;background:rgba(124,58,237,0.15);display:flex;align-items:center;justify-content:center;font-size:1.1rem;flex-shrink:0;}
  .soft-skill-name{font-size:0.9rem;font-weight:700;color:#fff;margin-bottom:0.2rem;}
  .soft-skill-desc{font-size:0.78rem;color:var(--muted);line-height:1.6;}

  /* CONTACT */
  #contact{text-align:center;}
  .contact-card{max-width:620px;margin:0 auto;border-radius:16px;border:1px solid var(--border);background:var(--card-bg);padding:3.5rem 2.5rem;}
  .contact-email{font-size:1.3rem;font-weight:800;color:#fff;margin:1rem 0 0.3rem;}
  .contact-phone{font-size:0.9rem;color:var(--muted);}
  .contact-links{display:flex;gap:0.75rem;justify-content:center;flex-wrap:wrap;margin-top:2rem;}
  .contact-btn{padding:0.7rem 1.5rem;border-radius:8px;border:1px solid var(--border);background:transparent;color:var(--muted);text-decoration:none;font-size:0.85rem;display:flex;align-items:center;gap:0.5rem;transition:all 0.2s;}
  .contact-btn:hover{border-color:var(--purple);color:var(--purple-light);background:rgba(124,58,237,0.08);}

  footer{text-align:center;padding:2.5rem;color:var(--muted);font-size:0.78rem;border-top:1px solid var(--border);}

  /* REVEAL */
  .reveal{opacity:0;transform:translateY(28px);transition:opacity 0.7s ease,transform 0.7s ease;}
  .reveal.visible{opacity:1;transform:translateY(0);}

  /* DIVIDER LINE */
  .h-line{width:100%;height:1px;background:var(--border);margin:0;}

  @media(max-width:768px){
    nav{padding:1rem 1.5rem;}
    .nav-links{display:none;}
    .section-wrap{padding:5rem 1.5rem;}
    .hero-left{padding:1.5rem;}
    .about-grid,.skills-cats,.soft-skills-wrap{grid-template-columns:1fr;}
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-logo">Shubham Somase</div>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#patents">Patents</a></li>
    <li><a href="#research">Research</a></li>
    <li><a href="#certifications">Certs</a></li>
    <li><a href="#activities">Activities</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<section id="hero">
  <canvas id="canvas3d"></canvas>
  <div class="hero-left">
    <div class="hero-eyebrow">Electrical Engineering · Automation · Robotics</div>
    <p class="hero-greeting">Hey, I'm</p>
    <h1 class="hero-name">Shubham<br><span class="accent">Somase</span></h1>
    <p class="hero-roles">
      <span>Automation Engineer</span><span class="hero-pipe">|</span>
      <span>Robotics Builder</span><span class="hero-pipe">|</span>
      <span>Inventor</span>
    </p>
    <p class="hero-sub">Final-year B.Tech student at Sanjivani College of Engineering, turning ideas into intelligent systems — 3 design patents, 2 publications, AIR 17 at DD-Robocon 2025.</p>
    <div class="hero-cta">
      <a href="#projects" class="btn-primary">View My Work</a>
      <a href="#contact" class="btn-outline">Contact Me</a>
    </div>
  </div>
  <div class="scroll-hint">
    <div class="scroll-line"></div>
    <span>scroll</span>
  </div>
</section>

<div class="h-line"></div>

<!-- ABOUT -->
<section id="about">
  <div class="section-wrap">
    <div class="reveal">
      <p class="section-label">Get to know me</p>
      <h2 class="section-title">About Me</h2>
    </div>
    <div class="about-grid">
      <div class="reveal">
        <div class="avatar-wrap">
          <div class="avatar-box">
            <div class="avatar-glow"></div>
            <div class="avatar-initials">SS</div>
          </div>
        </div>
        <div class="edu-list" style="margin-top:1.5rem;">
          <div class="edu-item">
            <div class="edu-deg">B.Tech — Electrical Engineering</div>
            <div class="edu-info">
              <span class="edu-school">Sanjivani College of Engineering</span>
              <span class="edu-grade">7.2 CGPA</span>
            </div>
            <div class="edu-year">Aug 2023 – Jul 2027 (Final Year)</div>
          </div>
          <div class="edu-item">
            <div class="edu-deg">HSC (12th)</div>
            <div class="edu-info">
              <span class="edu-school">K.B Rohamare College</span>
              <span class="edu-grade">61.17%</span>
            </div>
            <div class="edu-year">Jun 2022 – May 2023</div>
          </div>
          <div class="edu-item">
            <div class="edu-deg">SSC (10th)</div>
            <div class="edu-info">
              <span class="edu-school">Sanjivani English Medium School</span>
              <span class="edu-grade">81.20%</span>
            </div>
            <div class="edu-year">Jun 2020 – May 2021</div>
          </div>
        </div>
      </div>
      <div class="reveal">
        <p style="color:var(--muted);line-height:1.9;font-size:0.95rem;margin-bottom:1rem;">I'm a final-year Electrical Engineering student passionate about automation, embedded systems, and intelligent control. My work spans biometric-secured vending machines, nationally-ranked competition robotics, and IoT assistive technology.</p>
        <p style="color:var(--muted);line-height:1.9;font-size:0.95rem;margin-bottom:1rem;">I've filed 3 design patents, published in peer-reviewed journals, and secured AIR 17 at DD-Robocon 2025 — all while leading the Tesla R&D Club and serving as President.</p>
        <p style="color:var(--muted);line-height:1.9;font-size:0.95rem;">Fluent in English, Hindi, Marathi — and learning Japanese, because great engineering is as much about communication as it is about circuits.</p>
        <div class="stat-row">
          <div class="stat"><div class="stat-num">3<span>+</span></div><div class="stat-label">Patents</div></div>
          <div class="stat"><div class="stat-num">2</div><div class="stat-label">Publications</div></div>
          <div class="stat"><div class="stat-num" style="font-size:1.2rem;">AIR <span>17</span></div><div class="stat-label">Robocon</div></div>
          <div class="stat"><div class="stat-num">4</div><div class="stat-label">Languages</div></div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="h-line"></div>

<!-- SKILLS -->
<section id="skills">
  <div class="section-wrap">
    <div class="reveal">
      <p class="section-label">Technical Stack</p>
      <h2 class="section-title">Skills & Tools</h2>
      <p class="section-sub">Built through competitions, research, and hands-on engineering projects.</p>
    </div>
    <div class="skills-cats reveal">
      <div>
        <div class="skill-cat-title">⚡ Engineering Tools</div>
        <div class="skill-chips">
          <div class="chip">PLC Programming</div>
          <div class="chip">SCADA</div>
          <div class="chip">AutoCAD</div>
          <div class="chip">MATLAB</div>
          <div class="chip">Simulink</div>
          <div class="chip">ANSYS</div>
          <div class="chip">Circuit Design</div>
          <div class="chip">Solar Energy Systems</div>
          <div class="chip">Embedded Systems</div>
          <div class="chip">IoT</div>
        </div>
      </div>
      <div>
        <div class="skill-cat-title">🧠 Professional Skills</div>
        <div class="skill-chips">
          <div class="chip">Project Management</div>
          <div class="chip">Team Leadership</div>
          <div class="chip">Strategic Planning</div>
          <div class="chip">Critical Thinking</div>
          <div class="chip">Problem Solving</div>
          <div class="chip">Creative Design</div>
          <div class="chip">Innovation</div>
          <div class="chip">Time Management</div>
          <div class="chip">Communication</div>
          <div class="chip">Adaptability</div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="h-line"></div>

<!-- PROJECTS -->
<section id="projects">
  <div class="section-wrap">
    <div class="reveal">
      <p class="section-label">What I've Built</p>
      <h2 class="section-title">Featured Projects</h2>
      <p class="section-sub">Real engineering — from IIT Delhi competition floors to IoT-powered assistive technology.</p>
    </div>
    <div class="projects-grid">
      <div class="project-card reveal">
        <div class="project-num">01 — Automation</div>
        <div class="project-title">Smart Ration Vending Machine (SRVM)</div>
        <div class="project-period">Jan 2026 – May 2026</div>
        <p class="project-desc">Designed a biometric-based automated ration distribution system with embedded control logic for secure and efficient access. Programmed end-to-end dispensing sequences and formulated optimizations to improve accuracy and fault tolerance.</p>
        <div class="project-tags">
          <span class="ptag">PLC</span><span class="ptag">Embedded</span><span class="ptag">Biometrics</span><span class="ptag">Automation</span>
        </div>
      </div>
      <div class="project-card reveal">
        <div class="project-num">02 — Robotics</div>
        <div class="project-title">DD-Robocon 2025 — Competition Robot</div>
        <div class="project-period">Aug 2024 – Jul 2025</div>
        <p class="project-desc">Designed and prototyped robotic pick-and-place mechanisms for automated operations. Debugged control logic, optimized robot response time, and resolved critical mechanical-electrical integration issues for competition-ready performance.</p>
        <div class="award-badge">🏆 All India Rank 17 · IIT Delhi</div>
        <div class="project-tags">
          <span class="ptag">Robotics</span><span class="ptag">Control Systems</span><span class="ptag">Mechatronics</span>
        </div>
        <a href="https://www.linkedin.com/posts/shubhamsomase_robocon2025-robotics-engineering-ugcPost-7360897758364397568-b4H4/" target="_blank" class="project-link">↗ View on LinkedIn</a>
      </div>
      <div class="project-card reveal">
        <div class="project-num">03 — IoT · Assistive Tech</div>
        <div class="project-title">Smart Stick for the Visually Impaired</div>
        <div class="project-period">Conference Publication · ICRTC-2026</div>
        <p class="project-desc">IoT-based smart navigation aid with real-time obstacle detection and auditory feedback enabling independent mobility for visually impaired users.</p>
        <div class="project-tags">
          <span class="ptag">IoT</span><span class="ptag">Sensors</span><span class="ptag">Assistive Tech</span>
        </div>
      </div>
      <div class="project-card reveal">
        <div class="project-num">04 — EV · Decision Systems</div>
        <div class="project-title">EV Charging Station Decision Support</div>
        <div class="project-period">Journal Publication</div>
        <p class="project-desc">Real-time decision support application for optimal EV charging station selection, addressing range anxiety and infrastructure planning for electric mobility.</p>
        <div class="project-tags">
          <span class="ptag">EV</span><span class="ptag">Decision Systems</span><span class="ptag">Real-time</span>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="h-line"></div>

<!-- PATENTS -->
<section id="patents">
  <div class="section-wrap">
    <div class="reveal">
      <p class="section-label">Intellectual Property</p>
      <h2 class="section-title">Design Patents</h2>
      <p class="section-sub">Three registered design patents in engineering and product innovation.</p>
    </div>
    <div class="patents-grid">
      <div class="patent-card reveal">
        <div class="patent-icon">⚙️</div>
        <div class="patent-title">Emergency Hydraulic Wheel for Tractor Trolley</div>
        <div class="patent-appno">Application No. — see LinkedIn post</div>
        <div class="patent-date">April 2025 · Design Registration</div>
        <a href="https://www.linkedin.com/posts/shubhamsomase_innovation-designregistration-intellectualproperty-share-7431949384935739394-ZsWM/" target="_blank" class="patent-link">↗ View Patent Post</a>
      </div>
      <div class="patent-card reveal">
        <div class="patent-icon">🪑</div>
        <div class="patent-title">Smart Adjustable Seating Stool</div>
        <div class="patent-appno">Application No. — see LinkedIn post</div>
        <div class="patent-date">January 2025 · Design Registration</div>
        <a href="https://www.linkedin.com/posts/shubhamsomase_innovation-designpatent-proudmoment-share-7362684206415593473-X_52/" target="_blank" class="patent-link">↗ View Patent Post</a>
      </div>
      <div class="patent-card reveal">
        <div class="patent-icon">🪴</div>
        <div class="patent-title">Smart Bench</div>
        <div class="patent-appno">Application No. — see LinkedIn post</div>
        <div class="patent-date">Design Registration</div>
        <a href="https://www.linkedin.com/posts/shubhamsomase_innovation-engineering-designregistration-share-7455826650291855360-9WV-/" target="_blank" class="patent-link">↗ View Patent Post</a>
      </div>
    </div>
    <p style="color:var(--muted);font-size:0.78rem;margin-top:1.5rem;font-style:italic;">💡 Open each LinkedIn post to find the official application number and update accordingly.</p>
  </div>
</section>

<div class="h-line"></div>

<!-- PUBLICATIONS -->
<section id="research">
  <div class="section-wrap">
    <div class="reveal">
      <p class="section-label">Research</p>
      <h2 class="section-title">Publications</h2>
    </div>
    <div class="pub-list">
      <div class="pub-card reveal">
        <div class="pub-num">01</div>
        <div>
          <div class="pub-type">Journal Article · UGC Compliant International Research Journal</div>
          <div class="pub-title">Design and Implementation of a Real-time Decision Support Application for Optimal EV Charging Station Selection</div>
          <div class="pub-venue">UGC Compliant International Research Journal</div>
        </div>
      </div>
      <div class="pub-card reveal">
        <div class="pub-num">02</div>
        <div>
          <div class="pub-type">Conference Paper · ICRTC-2026</div>
          <div class="pub-title">IoT-Based Smart Stick for the Visually Impaired: Real-Time Obstacle Detection and Auditory Feedback System</div>
          <div class="pub-venue">International Conference on Recent Trends in Computing 2026</div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="h-line"></div>

<!-- CERTIFICATIONS -->
<section id="certifications">
  <div class="section-wrap">
    <div class="reveal">
      <p class="section-label">Credentials</p>
      <h2 class="section-title">Certifications</h2>
      <p class="section-sub">Verified credentials from IITs, MathWorks, and national competitions.</p>
    </div>
    <div class="certs-grid">
      <div class="cert-card reveal">
        <div class="cert-issuer-row">
          <div class="cert-badge" style="background:rgba(245,158,11,0.15);">🏆</div>
          <span class="cert-issuer-name">IIT Delhi · DD-Robocon</span>
        </div>
        <div class="cert-name">DD-Robocon 2025 — All India Rank 17</div>
        <div class="cert-bottom">
          <span class="cert-date">July 2025</span>
          <a href="https://www.linkedin.com/posts/shubhamsomase_robocon2025-robotics-engineering-ugcPost-7360897758364397568-b4H4/" target="_blank" class="cert-link">View ↗</a>
        </div>
      </div>
      <div class="cert-card reveal">
        <div class="cert-issuer-row">
          <div class="cert-badge" style="background:rgba(59,130,246,0.15);">📘</div>
          <span class="cert-issuer-name">NPTEL · IIT Kharagpur</span>
        </div>
        <div class="cert-name">Ethics in Engineering Practices</div>
        <div class="cert-bottom">
          <span class="cert-date">May 2025</span>
          <span class="cert-check">✓</span>
        </div>
      </div>
      <div class="cert-card reveal">
        <div class="cert-issuer-row">
          <div class="cert-badge" style="background:rgba(59,130,246,0.15);">📘</div>
          <span class="cert-issuer-name">NPTEL · IIT Roorkee</span>
        </div>
        <div class="cert-name">Soft Skills</div>
        <div class="cert-bottom">
          <span class="cert-date">October 2025</span>
          <span class="cert-check">✓</span>
        </div>
      </div>
      <div class="cert-card reveal">
        <div class="cert-issuer-row">
          <div class="cert-badge" style="background:rgba(220,38,38,0.15);">🔴</div>
          <span class="cert-issuer-name">MathWorks</span>
        </div>
        <div class="cert-name">MATLAB Onramp — 100% Complete</div>
        <div class="cert-bottom">
          <span class="cert-date">12 March 2025</span>
          <a href="https://matlabacademy.mathworks.com/progress/share/certificate.html?id=9d2dbb8e-ce61-42f5-9b98-fe5481d8b07e&" target="_blank" class="cert-link">View ↗</a>
        </div>
      </div>
      <div class="cert-card reveal">
        <div class="cert-issuer-row">
          <div class="cert-badge" style="background:rgba(220,38,38,0.15);">🔴</div>
          <span class="cert-issuer-name">MathWorks</span>
        </div>
        <div class="cert-name">MATLAB Onramp — 100% Complete</div>
        <div class="cert-bottom">
          <span class="cert-date">12 March 2025</span>
          <a href="https://matlabacademy.mathworks.com/progress/share/certificate.html?id=0ad84f1d-6ee8-4289-bad4-8616efe23108&" target="_blank" class="cert-link">View ↗</a>
        </div>
      </div>
      <div class="cert-card reveal">
        <div class="cert-issuer-row">
          <div class="cert-badge" style="background:rgba(220,38,38,0.15);">🔴</div>
          <span class="cert-issuer-name">MathWorks</span>
        </div>
        <div class="cert-name">Simulink Onramp — 13% (In Progress)</div>
        <div class="cert-bottom">
          <span class="cert-date">10 January 2025</span>
          <a href="https://matlabacademy.mathworks.com/progress/share/certificate.html?id=49241880-c39e-4bca-b2db-79f4b16def1d&" target="_blank" class="cert-link">View ↗</a>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="h-line"></div>

<!-- EXTRACURRICULARS -->
<section id="activities">
  <div class="section-wrap">
    <div class="reveal">
      <p class="section-label">Leadership & Involvement</p>
      <h2 class="section-title">Extracurricular Activities</h2>
      <p class="section-sub">Leading teams, building communities, and developing real-world skills beyond the classroom.</p>
    </div>

    <!-- Soft Skills Banner -->
    <div class="reveal" style="margin-bottom:3rem;">
      <div style="padding:1.5rem;border-radius:12px;border:1px solid var(--border);background:var(--card-bg);margin-bottom:1.5rem;">
        <div style="font-size:0.78rem;text-transform:uppercase;letter-spacing:0.12em;color:var(--purple-light);margin-bottom:1rem;">Management & Soft Skills Developed</div>
        <div class="soft-skills-wrap">
          <div class="soft-skill-item">
            <div class="soft-icon">📋</div>
            <div>
              <div class="soft-skill-name">Event & Project Management</div>
              <div class="soft-skill-desc">Planned and executed departmental events, technical competitions, and placement programs across multiple roles simultaneously.</div>
            </div>
          </div>
          <div class="soft-skill-item">
            <div class="soft-icon">👥</div>
            <div>
              <div class="soft-skill-name">Team Leadership</div>
              <div class="soft-skill-desc">Led the Tesla R&D Club as President and guided cross-functional student teams in robotics and research initiatives.</div>
            </div>
          </div>
          <div class="soft-skill-item">
            <div class="soft-icon">🎨</div>
            <div>
              <div class="soft-skill-name">Creative Communication & Design</div>
              <div class="soft-skill-desc">Designed promotional materials and managed alumni communication as part of SARC's creative team.</div>
            </div>
          </div>
          <div class="soft-skill-item">
            <div class="soft-icon">🤝</div>
            <div>
              <div class="soft-skill-name">Stakeholder Coordination</div>
              <div class="soft-skill-desc">Coordinated between students, faculty, and industry partners as a T&P Coordinator to facilitate placements and training programs.</div>
            </div>
          </div>
          <div class="soft-skill-item">
            <div class="soft-icon">🗣️</div>
            <div>
              <div class="soft-skill-name">Public Speaking & Representation</div>
              <div class="soft-skill-desc">Represented the department and college in national-level robotics competitions and institutional events.</div>
            </div>
          </div>
          <div class="soft-skill-item">
            <div class="soft-icon">⏱️</div>
            <div>
              <div class="soft-skill-name">Time Management & Multitasking</div>
              <div class="soft-skill-desc">Balanced four concurrent extracurricular roles alongside research, patents, and academic coursework.</div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="extra-grid">
      <div class="extra-card reveal">
        <div class="extra-role">President</div>
        <div class="extra-org">Tesla R&D Club</div>
        <div class="extra-period">Oct 2025 – Present</div>
        <div class="extra-desc">Leading the college's R&D club — driving innovation initiatives, mentoring members, and overseeing technical and creative projects. Responsible for club strategy, event planning, and team management.</div>
        <div class="extra-skills">
          <span class="extra-skill">Leadership</span>
          <span class="extra-skill">Strategic Planning</span>
          <span class="extra-skill">Club Management</span>
          <span class="extra-skill">Mentorship</span>
        </div>
      </div>

      <div class="extra-card reveal">
        <div class="extra-role">R&D Member</div>
        <div class="extra-org">Team Sphinx</div>
        <div class="extra-period">Aug 2024 – Present</div>
        <div class="extra-desc">Contributing to research and development activities — collaborating on technical projects, prototyping solutions, and applying engineering skills in a team-oriented environment.</div>
        <div class="extra-skills">
          <span class="extra-skill">R&D</span>
          <span class="extra-skill">Prototyping</span>
          <span class="extra-skill">Collaboration</span>
        </div>
      </div>

      <div class="extra-card reveal">
        <div class="extra-role">Executive Member</div>
        <div class="extra-org">
          <a href="https://www.linkedin.com/in/eesa-scoe-830775291/" target="_blank" style="color:var(--purple-light);text-decoration:none;">Electrical Engineering Students Association (EESA)</a>
        </div>
        <div class="extra-period">2025–26</div>
        <div class="extra-desc">Contributed to organizing departmental events, technical activities, and student engagement programs — developing leadership and teamwork skills as an executive team member.</div>
        <div class="extra-skills">
          <span class="extra-skill">Event Management</span>
          <span class="extra-skill">Student Engagement</span>
          <span class="extra-skill">Teamwork</span>
        </div>
        <div class="extra-links">
          <a href="https://www.linkedin.com/posts/shubhamsomase_codechefscoe-scoe-gratitude-activity-7332414204957691904-ULMg" target="_blank" class="extra-link">📄 Appreciation Letter ↗</a>
        </div>
      </div>

      <div class="extra-card reveal">
        <div class="extra-role">Creative & Design Team Member</div>
        <div class="extra-org">
          <a href="https://www.linkedin.com/company/sarc-sanjivani/" target="_blank" style="color:var(--purple-light);text-decoration:none;">Student Alumni Relations Cell (SARC)</a>
        </div>
        <div class="extra-period">2024 – Present</div>
        <div class="extra-desc">Designed promotional materials, supported alumni engagement initiatives, and assisted in organizing institutional events and communication activities. Strengthened creative design and marketing skills.</div>
        <div class="extra-skills">
          <span class="extra-skill">Graphic Design</span>
          <span class="extra-skill">Alumni Relations</span>
          <span class="extra-skill">Communication</span>
          <span class="extra-skill">Event Planning</span>
        </div>
        <div class="extra-links">
          <a href="https://www.linkedin.com/posts/shubhamsomase_sarc-letterofappreciation-sanjivanicollegeofengineering-activity-7423740611801018369-9ncW" target="_blank" class="extra-link">📄 Appreciation Letter ↗</a>
        </div>
      </div>

      <div class="extra-card reveal">
        <div class="extra-role">Student Training & Placement Coordinator</div>
        <div class="extra-org">T&P Cell, Sanjivani College of Engineering</div>
        <div class="extra-period">Aug 2024 – 2025</div>
        <div class="extra-desc">Coordinated training and placement activities, maintained student communication, and ensured smooth execution of placement-related programs. Bridged the gap between students and industry opportunities.</div>
        <div class="extra-skills">
          <span class="extra-skill">Coordination</span>
          <span class="extra-skill">Industry Liaison</span>
          <span class="extra-skill">Communication</span>
          <span class="extra-skill">Program Execution</span>
        </div>
        <div class="extra-links">
          <a href="https://www.linkedin.com/posts/shubhamsomase_certificateofappreciation-engineeringlife-activity-7358763427869216768-7-sr" target="_blank" class="extra-link">📄 Appreciation Letter ↗</a>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="h-line"></div>

<!-- CONTACT -->
<section id="contact">
  <div class="section-wrap">
    <div class="reveal">
      <p class="section-label">Reach Out</p>
      <h2 class="section-title">Let's Connect</h2>
    </div>
    <div class="contact-card reveal">
      <p style="color:var(--muted);line-height:1.8;">Open to automation engineering roles, research collaborations, and project opportunities. Feel free to reach out!</p>
      <div class="contact-email">shubhamssomase001@gmail.com</div>
      <div class="contact-phone">+91 90210 85920</div>
      <div class="contact-links">
        <a href="mailto:shubhamssomase001@gmail.com" class="contact-btn">✉ Email Me</a>
        <a href="https://www.linkedin.com/in/shubhamsomase" target="_blank" class="contact-btn">💼 LinkedIn</a>
        <a href="tel:+919021085920" class="contact-btn">📞 +91 90210 85920</a>
      </div>
    </div>
  </div>
</section>

<footer>
  <p>Shubham Somase · B.Tech Electrical Engineering · Sanjivani College of Engineering · 2026</p>
</footer>

<script>
/* ── 3D HERO (Prathyaksh-inspired: dark bg, big spinning rings, floating nodes, mouse parallax) ── */
(function(){
  const canvas = document.getElementById('canvas3d');
  const renderer = new THREE.WebGLRenderer({canvas, antialias:true, alpha:true});
  renderer.setPixelRatio(Math.min(window.devicePixelRatio,2));
  const scene = new THREE.Scene();
  const camera = new THREE.PerspectiveCamera(55,1,0.1,100);
  camera.position.set(0,0,9);

  function resize(){
    const w=canvas.clientWidth,h=canvas.clientHeight;
    renderer.setSize(w,h,false);
    camera.aspect=w/h;
    camera.updateProjectionMatrix();
  }
  resize();
  window.addEventListener('resize',resize);

  /* Core icosahedron */
  const coreGeo = new THREE.IcosahedronGeometry(1.1,1);
  const coreMat = new THREE.MeshBasicMaterial({color:0x7c3aed,wireframe:true});
  const core = new THREE.Mesh(coreGeo,coreMat);
  scene.add(core);

  /* Inner ring */
  const r1 = new THREE.Mesh(
    new THREE.TorusGeometry(2.8,0.018,8,90),
    new THREE.MeshBasicMaterial({color:0x6d28d9})
  );
  r1.rotation.x = Math.PI/2.5;
  scene.add(r1);

  /* Outer ring */
  const r2 = new THREE.Mesh(
    new THREE.TorusGeometry(4.2,0.012,8,120),
    new THREE.MeshBasicMaterial({color:0xa78bfa})
  );
  r2.rotation.x = -Math.PI/4;
  r2.rotation.y = Math.PI/5;
  scene.add(r2);

  /* Third tilted ring */
  const r3 = new THREE.Mesh(
    new THREE.TorusGeometry(5.5,0.008,6,100),
    new THREE.MeshBasicMaterial({color:0x4c1d95})
  );
  r3.rotation.x = Math.PI/6;
  r3.rotation.z = Math.PI/7;
  scene.add(r3);

  /* Floating dots */
  const dots=[];
  const dGeo=new THREE.IcosahedronGeometry(0.1,0);
  for(let i=0;i<50;i++){
    const m=new THREE.Mesh(dGeo,new THREE.MeshBasicMaterial({color:i%3===0?0xa78bfa:0x7c3aed,wireframe:i%4===0}));
    const rad=3+Math.random()*5;
    const th=Math.random()*Math.PI*2;
    const ph=Math.random()*Math.PI;
    m.position.set(rad*Math.sin(ph)*Math.cos(th),rad*Math.sin(ph)*Math.sin(th),rad*Math.cos(ph)-1);
    m.userData={spd:0.15+Math.random()*0.4,ph:Math.random()*Math.PI*2,base:m.position.y};
    scene.add(m);
    dots.push(m);
  }

  /* Connection lines */
  const lMat=new THREE.LineBasicMaterial({color:0x4c1d95,opacity:0.35,transparent:true});
  for(let i=0;i<dots.length;i++){
    for(let j=i+1;j<dots.length;j++){
      if(dots[i].position.distanceTo(dots[j].position)<3){
        scene.add(new THREE.Line(new THREE.BufferGeometry().setFromPoints([dots[i].position,dots[j].position]),lMat));
      }
    }
  }

  /* Mouse */
  let mx=0,my=0;
  window.addEventListener('mousemove',e=>{
    mx=(e.clientX/window.innerWidth-0.5)*1.2;
    my=(e.clientY/window.innerHeight-0.5)*0.7;
  });

  const clock=new THREE.Clock();
  function animate(){
    requestAnimationFrame(animate);
    const t=clock.getElapsedTime();
    core.rotation.y=t*0.25;
    core.rotation.x=t*0.12;
    r1.rotation.z=t*0.12;
    r2.rotation.z=-t*0.08;
    r2.rotation.x=-Math.PI/4+Math.sin(t*0.05)*0.1;
    r3.rotation.y=t*0.06;
    dots.forEach(d=>{
      d.position.y=d.userData.base+Math.sin(t*d.userData.spd+d.userData.ph)*0.3;
      d.rotation.y=t*d.userData.spd;
    });
    camera.position.x+=(mx-camera.position.x)*0.04;
    camera.position.y+=(-my-camera.position.y)*0.04;
    camera.lookAt(0,0,0);
    renderer.render(scene,camera);
  }
  animate();
})();

/* ── SCROLL REVEAL ── */
const io=new IntersectionObserver(entries=>{
  entries.forEach(e=>{if(e.isIntersecting)e.target.classList.add('visible');});
},{threshold:0.08});
document.querySelectorAll('.reveal').forEach(el=>io.observe(el));
</script>
</body>
</html>
