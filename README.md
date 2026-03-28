<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
  <title>Shoaib | Full Stack Architect – SERN Stack & Flutter Dev</title>
  <!-- Google Fonts & simple CSS reset -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700;14..32,800&family=Fira+Code:wght@400;500;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #000000;
      color: #eef2ff;
      font-family: 'Inter', sans-serif;
      scroll-behavior: smooth;
    }

    /* custom scroll */
    ::-webkit-scrollbar {
      width: 6px;
    }
    ::-webkit-scrollbar-track {
      background: #0a0a0a;
    }
    ::-webkit-scrollbar-thumb {
      background: #00D2FF;
      border-radius: 12px;
    }

    .container {
      max-width: 1280px;
      margin: 0 auto;
      padding: 1.5rem 2rem;
    }

    /* section styles */
    .section-card {
      background: #0a0a0a;
      border-radius: 2rem;
      padding: 2rem 2rem;
      margin-bottom: 2.5rem;
      border: 1px solid #1f1f2e;
      transition: all 0.2s ease;
    }

    .section-title {
      font-size: 1.8rem;
      font-weight: 700;
      background: linear-gradient(135deg, #FFFFFF 0%, #00D2FF 100%);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      margin-bottom: 1.25rem;
      letter-spacing: -0.3px;
      display: inline-block;
      border-left: 4px solid #00D2FF;
      padding-left: 1rem;
    }

    .badge-group {
      display: flex;
      flex-wrap: wrap;
      gap: 0.75rem;
      justify-content: center;
      margin: 1rem 0;
    }

    .glow-text {
      color: #00D2FF;
      font-weight: 600;
    }

    .tech-stack-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.5rem;
      margin: 1.5rem 0;
    }

    .tech-icon {
      background: #111111;
      padding: 0.5rem;
      border-radius: 20px;
      transition: transform 0.2s ease;
      display: inline-flex;
      align-items: center;
      justify-content: center;
    }
    .tech-icon:hover {
      transform: translateY(-5px);
    }

    /* project table responsive */
    .project-table {
      width: 100%;
      border-collapse: separate;
      border-spacing: 1rem;
    }
    .project-card {
      background: #0f0f17;
      border-radius: 1.5rem;
      padding: 1.25rem;
      height: 100%;
      border: 1px solid #202030;
      transition: all 0.2s;
    }
    .project-card:hover {
      border-color: #00D2FF66;
      background: #12121c;
    }

    @media (max-width: 780px) {
      .container {
        padding: 1rem;
      }
      .section-card {
        padding: 1.25rem;
      }
      .project-table, .project-table tbody, .project-table tr {
        display: flex;
        flex-direction: column;
      }
    }

    hr {
      border-color: #1e2a3a;
      margin: 1rem 0;
    }

    .contrib-image {
      max-width: 100%;
      border-radius: 20px;
      background: #0a0a0a;
      padding: 0.5rem;
      border: 1px solid #2a2a3a;
      margin-top: 0.5rem;
    }

    /* stats images */
    .stats-wrapper {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
      margin: 1rem 0;
    }
    .stats-wrapper img {
      max-width: 49%;
      border-radius: 20px;
      background: #050505;
    }
    @media (max-width: 700px) {
      .stats-wrapper img {
        max-width: 100%;
      }
    }
  </style>
</head>
<body>

<!-- header wave + profile intro exactly as original but kept dynamic -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:0a0a0a,100:00D2FF&height=300&section=header&text=Shoaib%20|%20Full%20Stack%20Dev&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=⚡%20Building%20Digital%20Excellence%20⚡&descAlignY=56&descAlign=50&descSize=18" width="100%" alt="header" style="max-width: 100%;">
</div>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00D2FF&center=true&vCenter=true&multiline=false&width=750&lines=Full+Stack+Architect+(SERN+Stack);Next.js+%2B+TypeScript+Expert;Flutter+%26+Dart+App+Developer;Clean+Code+%7C+Scalable+Systems;DSA+%7C+OOP+%7C+System+Design;Open+Source+Enthusiast+%F0%9F%9A%80" alt="typing svg">
</p>

<p align="center">
  <a href="https://wa.me/923053022216"><img src="https://img.shields.io/badge/WhatsApp-Contact-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=black"/></a>
  <a href="https://www.linkedin.com/in/shabyhere"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=black"/></a>
  <a href="https://github.com/muhammadshoaib549"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=black"/></a>
</p>

<div class="container">
  <!-- EXECUTIVE SUMMARY -->
  <div class="section-card">
    <div class="section-title">🚀 Executive Summary</div>
    <p style="font-size: 1.15rem; font-style: italic; margin-bottom: 1rem;">> "Turning complex logic into elegant, high-performance digital reality."</p>
    <p>I am a <strong class="glow-text">Software Engineering Student</strong> and <strong class="glow-text">Full-Stack Architect</strong> obsessed with the art of clean code. I don't just build apps — I engineer scalable ecosystems. By merging deep <strong>CS Fundamentals</strong> with modern <strong>Next.js & Supabase</strong> (SERN) stacks, I deliver products that are as robust on the backend as they are beautiful on the frontend.</p>
    <div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 1rem; margin-top: 1.8rem;">
      <div>🛠️ <strong>The Architect's Choice</strong><br>Specialized in the <span class="glow-text">SERN Stack</span> (Supabase, Express, React, Next.js)</div>
      <div>📱 <strong>Mobile Expert</strong><br>Building cross-platform apps with <span class="glow-text">Flutter & Dart</span></div>
      <div>🐧 <strong>Environment</strong><br>Living in the terminal on <span class="glow-text">Linux Mint Cinnamon</span></div>
      <div>⚡ <strong>Performance First</strong><br>Obsessed with sub-second load times and optimized DSA implementations</div>
      <div>🎯 <strong>Motto</strong><br><em>"Consistency beats motivation. Show up every single day."</em></div>
    </div>
  </div>

  <!-- CORE COMPUTER SCIENCE SKILLS -->
  <div class="section-card">
    <div class="section-title">🧠 Core Computer Science Skills</div>
    <div class="badge-group">
      <img src="https://img.shields.io/badge/Data_Structures-Advanced-00D2FF?style=for-the-badge&labelColor=black">
      <img src="https://img.shields.io/badge/Algorithms-Advanced-00D2FF?style=for-the-badge&labelColor=black">
      <img src="https://img.shields.io/badge/OOP-Expert-00D2FF?style=for-the-badge&labelColor=black">
      <img src="https://img.shields.io/badge/Problem_Solving-Strong-00D2FF?style=for-the-badge&labelColor=black">
    </div>
  </div>

  <!-- CURRENT FOCUS + MASTERING -->
  <div class="section-card">
    <div class="section-title">🔥 Current Focus</div>
    <div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 1rem; text-align: center;">
      <div><strong>💡 Learning</strong><br>Advanced System Design</div>
      <div><strong>🏗️ Building</strong><br>SaaS Boilerplate</div>
      <div><strong>📖 Reading</strong><br>Clean Architecture</div>
      <div><strong>🤝 Contributing</strong><br>Open Source</div>
    </div>
    <div class="badge-group" style="margin-top: 1.5rem;">
      <img src="https://img.shields.io/badge/🚀%20CURRENTLY%20MASTERING-Next.js%2014%20%7C%20Flutter%20%7C%20Supabase-00D2FF?style=for-the-badge&labelColor=black">
    </div>
  </div>

  <!-- TECHNICAL ARSENAL (icons & stacks) -->
  <div class="section-card">
    <div class="section-title">🛠️ Technical Arsenal</div>
    <div><strong>💻 Development Stack</strong></div>
    <div style="margin: 0.5rem 0 1rem 0; background: #0c0c10; padding: 0.8rem; border-radius: 1rem;">
      <p><strong>Frontend:</strong> React.js · Next.js · TypeScript · Tailwind CSS · Framer Motion · .NET · Java Swing · Flutter</p>
      <p><strong>Mobile:</strong> Flutter · Dart</p>
      <p><strong>Backend & DB:</strong> Node.js · Express · Supabase (PostgreSQL) · SQL · Prisma</p>
      <p><strong>Languages:</strong> HTML5, CSS3, JavaScript, TypeScript, Dart, Java, Python, C#, C++, Assembly (8086)</p>
      <p><strong>Simulation & IoT:</strong> Proteus Professional 8 · Cisco Packet Tracer</p>
      <p><strong>Data Science:</strong> Jupyter Notebook · Python · NumPy · Pandas</p>
    </div>

    <!-- Languages icons row -->
    <div><strong>🔧 Languages</strong></div>
    <div class="tech-stack-grid">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="45" title="HTML5">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="45" title="CSS3">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" height="45" title="Tailwind">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="45" title="JavaScript">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="45" title="TypeScript">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg" height="45" title="Dart">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="45" title="Java">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="45" title="Python">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="45" title="C++">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="45" title="C#">
    </div>

    <div><strong>🎨 Frontend & Mobile</strong></div>
    <div class="tech-stack-grid">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="45" style="background:#fff; border-radius:8px; padding:4px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="45">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" height="45">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-original.svg" height="45">
    </div>

    <div><strong>🗄️ Backend & Database</strong></div>
    <div class="tech-stack-grid">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="45">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="45" style="background:#fff; border-radius:8px;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/supabase/supabase-original.svg" height="45">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="45">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prisma/prisma-original.svg" height="45" style="background:#fff; border-radius:8px;">
    </div>

    <div><strong>⚙️ Tools & Platforms</strong></div>
    <div class="tech-stack-grid">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" style="background:#fff; border-radius:50%;">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="40">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40">
    </div>
  </div>

  <!-- FEATURED PROJECTS TABLE exactly as original style -->
  <div class="section-card">
    <div class="section-title">📂 Featured Projects</div>
    <table class="project-table" style="width:100%; border-collapse: collapse;">
      <tbody>
        <tr>
          <td style="width:50%; vertical-align:top; padding:0.5rem;">
            <div class="project-card">
              <h3>🚲 <b>Mian Autos</b></h3>
              <p><i>E-commerce & Management System for bike workshops</i></p>
              <div>
                <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
                <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white">
                <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white">
              </div>
              <details><summary>📋 Features</summary><ul><li>Inventory Management</li><li>Service Booking System</li><li>Customer Portal</li><li>Payment Integration</li></ul></details>
            </div>
          </td>
          <td style="width:50%; vertical-align:top; padding:0.5rem;">
            <div class="project-card">
              <h3>🛒 <b>OmniCart</b></h3>
              <p><i>High-performance, scalable e-commerce platform</i></p>
              <div>
                <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
                <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white">
                <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white">
              </div>
              <details><summary>📋 Features</summary><ul><li>Real-time Inventory</li><li>Cart Management</li><li>Order Tracking</li><li>Admin Dashboard</li></ul></details>
            </div>
          </td>
        </tr>
        <tr>
          <td style="vertical-align:top; padding:0.5rem;">
            <div class="project-card">
              <h3>📱 <b>Flutter App</b></h3>
              <p><i>Cross-platform mobile application</i></p>
              <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white">
              <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white">
            </div>
          </td>
          <td style="vertical-align:top; padding:0.5rem;">
            <div class="project-card">
              <h3>💬 <b>Real-time Chat</b></h3>
              <p><i>DSA optimized messaging application</i></p>
              <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
              <img src="https://img.shields.io/badge/DSA-Optimized-FF6B6B?style=flat-square">
            </div>
          </td>
        </tr>
        <tr>
          <td style="vertical-align:top; padding:0.5rem;">
            <div class="project-card">
              <h3>🏪 <b>Super Market System</b></h3>
              <p><i>Inventory and sales management</i></p>
              <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white">
              <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white">
            </div>
          </td>
          <td style="vertical-align:top; padding:0.5rem;">
            <div class="project-card">
              <h3>🚗 <b>RideEase App</b></h3>
              <p><i>UI/UX design for ride-sharing</i></p>
              <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white">
              <img src="https://img.shields.io/badge/UI%2FUX-Design-00D2FF?style=flat-square">
            </div>
          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <!-- GITHUB ANALYTICS + ACTIVITY GRID & IMAGE FROM THE USER'S CONTRIBUTION GRAPH (EXACT AS IN IMAGE) -->
  <div class="section-card">
    <div class="section-title">📊 GitHub Analytics</div>
    <div class="stats-wrapper">
      <img src="https://github-readme-stats.vercel.app/api?username=muhammadshoaib549&show_icons=true&theme=tokyonight&hide_border=true&bg_color=000000&title_color=00D2FF&icon_color=00D2FF&include_all_commits=true&count_private=true" alt="github stats">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=muhammadshoaib549&theme=tokyonight&hide_border=true&background=000000&sideLabels=00D2FF&stroke=00D2FF&currStreakLabel=00D2FF" alt="streak">
    </div>
    <div align="center" style="margin: 0.5rem 0;">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadshoaib549&layout=compact&theme=tokyonight&hide_border=true&bg_color=000000&title_color=00D2FF&langs_count=8" width="48%" alt="top langs">
    </div>

    <!-- ACTIVITY OVERVIEW & CONTRIBUTION GRID from image (exactly as described) -->
    <div style="margin-top: 2rem; background: #05070c; border-radius: 1.5rem; padding: 1.5rem;">
      <div style="display: flex; justify-content: space-between; flex-wrap: wrap; margin-bottom: 1rem;">
        <h3 style="color:#00D2FF;">📈 Activity overview</h3>
        <span style="background: #111; padding: 0.2rem 0.8rem; border-radius: 40px;">Contributed to torvalds/linux, torvalds/GuitarPedal, torvalds/1590A and 2 other repositories</span>
      </div>
      <!-- Contribution chart: 100% commits, etc exactly as the image's contribution activity -->
      <div style="background:#0f1117; border-radius: 1rem; padding: 1rem;">
        <div style="display: flex; gap: 2rem; flex-wrap: wrap; justify-content: space-between; align-items: center;">
          <div><strong>Contribution activity</strong><br>✅ <span class="glow-text">100% Commits</span> &nbsp;| Pull requests &nbsp;| Code review &nbsp;| Issues</div>
          <div><span>📅 X-axis: Mar Apr May Jun Jul Aug Sep Oct Nov Dec Jan Feb Mar</span></div>
          <div>Y-axis (left): Mon Wed Fri &nbsp;|&nbsp; Y-axis (right): Less ➔ More</div>
        </div>
        <!-- Visual representation: exactly the "3,090 contributions in the last year" and the grid-like image from user -->
        <div align="center" style="margin: 1.5rem 0 0.5rem">
          <p style="font-size: 1.8rem; font-weight: 800;">3,090 contributions in the last year</p>
          <!-- contribution heatmap style simulation (like github-like squares) but keep original image style? we embed provided GH chart but also add visual cue -->
          <div style="background: #0a0c12; border-radius: 1rem; padding: 0.5rem;">
            <!-- we use the actual contribution grid from ghchart.rshah.org that matches consistent style -->
            <img src="https://ghchart.rshah.org/39d353/muhammadshoaib549?bg=000000" alt="contribution grid" style="max-width:100%; border-radius: 12px;">
            <p style="font-size: 0.8rem; margin-top: 0.5rem;">📌 Contribution grid (last year) — each green square represents a commit day.</p>
          </div>
        </div>
      </div>
    </div>
    <div align="center" style="margin-top: 1.5rem;">
      <img src="https://github-readme-stats.vercel.app/api?username=muhammadshoaib549&show_icons=true&theme=tokyonight&hide_border=true&bg_color=000000&title_color=00D2FF&icon_color=39d353&include_all_commits=true&count_private=true&show=reviews,discussions,prsMerged,prsMergedPercentage" width="90%" alt="detailed activity">
    </div>
  </div>

  <!-- HIRING STATUS -->
  <div class="section-card" align="center">
    <div class="section-title">⚡ Hiring Status</div>
    <img src="https://img.shields.io/badge/Status-Available%20for%20Work-00D2FF?style=for-the-badge&labelColor=black">
    <div style="display: flex; justify-content: center; gap: 2rem; margin: 1.5rem 0;">
      <div><strong>🌍 Freelance</strong><br>Available for Web & Mobile builds</div>
      <div><strong>🏠 Remote</strong><br>Ready to join engineering teams worldwide</div>
      <div><strong>📨 Contact</strong><br>Best reached via WhatsApp / LinkedIn</div>
    </div>
  </div>

  <!-- CONNECT + RESUME + QUOTE -->
  <div class="section-card" align="center">
    <div class="section-title">🤝 Let's Connect</div>
    <div class="badge-group">
      <a href="https://github.com/muhammadshoaib549/Shoaib_CV/blob/main/Shoaib,s%20CV.pdf"><img src="https://img.shields.io/badge/Download%20Resume-FF0000?style=for-the-badge&logo=adobeacrobatreader&logoColor=white&labelColor=black"></a>
      <a href="https://wa.me/923053022216"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=black"></a>
      <a href="https://www.linkedin.com/in/shabyhere"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=black"></a>
      <a href="mailto:muhammadshoaibshahid4@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=black"></a>
    </div>
    <p style="margin: 1.5rem 0 1rem; font-size: 1.2rem;">💡 <em>"Consistency beats motivation. Show up every single day."</em></p>
    <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical&bg_color=000000" width="70%">
    <br><br>
    <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D2FF,50:0077aa,100:000000&height=180&section=footer&text=Let's%20Build%20Something%20Amazing%20🚀&fontSize=24&fontColor=ffffff&animation=twinkling&fontAlignY=65" width="100%" style="margin-top: 1rem;">
  </div>
</div>

</body>
</html>
