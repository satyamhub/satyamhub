diff --git a/README.md b/README.md
index b3b1ead..d32789a 100644
--- a/README.md
+++ b/README.md
@@ -1,26 +1,31 @@
 # Satyam Mall
 
-B.Tech CSE student focused on DSA and full‑stack web development.
+B.Tech CSE student at G.L. Bajaj Institute of Technology and Management, focused on DSA and full‑stack web development.
 
 ---
 
 ## About
 - B.Tech in Computer Science and Engineering
-- Daily DSA practice with a focus on problem‑solving
-- Building full‑stack projects and backend fundamentals
+- Daily DSA practice in C++ with a focus on problem‑solving (130+ LeetCode solutions and a growing [DSA notes repo](https://github.com/satyamhub/DSA))
+- Building and shipping full‑stack projects, from a campus marketplace to an appointment system
+- Exploring AI agents and graph analytics through hackathon and side projects
 - Goal: product‑based engineering roles and impactful work
 
 ---
 
 ## Tech Stack
 <p align="center">
-  <img src="https://skillicons.dev/icons?i=cpp,js,html,css,react,nodejs,git,github,vscode" />
+  <img src="https://skillicons.dev/icons?i=cpp,js,ts,html,css,react,nextjs,nodejs,php,python,postgres,prisma,tailwind,git,github,vscode" />
 </p>
 
 ---
 
 ## Projects
-- Nestoida — Rental listing platform for PGs, flats, hostels, and co‑living spaces in Noida. `PHP · JavaScript · HTML · CSS` • [Repo](https://github.com/satyamhub/Nestoida)
+- **PeerKart × G.L. Bajaj** — Campus marketplace for students to buy, sell, and pass on books, gadgets, and essentials. Web app plus Android APK releases. [Live](https://glbpeerkart.netlify.app) • [Repo](https://github.com/satyamhub/PeerKart-x-GL-Bajaj)
+- **HealSync** — Hospital doctor–patient appointment management with role-based auth, doctor availability and slots, and double-booking prevention. `Next.js · TypeScript · Tailwind CSS · Prisma · PostgreSQL` • [Repo](https://github.com/satyamhub/HealSync)
+- **Cloudforce Fraud Ring** — TigerGraph-powered fraud detection demo that expands one suspicious account into a full mule ring (Devacation 2026). `TigerGraph · Flask · HTML` • [Live](https://cloudforce.vercel.app/) • [Repo](https://github.com/satyamhub/cloudforce-fraud-ring)
+- **DeskPilot** — AI autopilot that turns natural language into browser automation, running fully locally. `Python · Ollama · Playwright` • [Repo](https://github.com/satyamhub/deskpilot)
+- **Nestoida** — Rental listing platform for PGs, flats, hostels, and co‑living spaces in Noida. `PHP · JavaScript · HTML · CSS` • [Repo](https://github.com/satyamhub/Nestoida)
 
 ---
 
@@ -36,14 +41,15 @@ B.Tech CSE student focused on DSA and full‑stack web development.
 ---
 
 ## Current Focus
-- DSA and problem‑solving consistency
+- DSA and problem‑solving consistency in C++
+- Full‑stack development with Next.js, TypeScript, and Prisma
 - Backend development and system fundamentals
-- Real‑world full‑stack projects
+- Shipping real‑world projects with real users
 
 ---
 
 ## 2026 Goals
-- Solve 300+ DSA problems
+- Solve 300+ DSA problems (130+ done in my LeetCode repo so far)
 - Secure an internship in a product‑based company
 - Build 3 full‑stack projects end‑to‑end
 
diff --git a/index.html b/index.html
index 3ab2430..bcf54be 100644
--- a/index.html
+++ b/index.html
@@ -58,7 +58,7 @@
       <div class="hero-card">
         <div class="stat">
           <span class="stat-label">Primary Stack</span>
-          <span class="stat-value">PHP • JS • MySQL</span>
+          <span class="stat-value">JS • TS • PHP • Python</span>
         </div>
         <div class="stat">
           <span class="stat-label">Focus</span>
@@ -284,7 +284,7 @@
     <section id="projects" class="section">
       <div class="section-title">
         <h2>Projects</h2>
-        <p>Selected work showcasing full‑stack and backend fundamentals.</p>
+        <p>Selected work across full‑stack web, mobile releases, AI agents, and graph analytics.</p>
       </div>
       <div class="project-card">
         <img class="project-shot" src="nestoida_home.png" alt="Nestoida homepage screenshot" />
@@ -312,6 +312,38 @@
           </div>
         </div>
       </div>
+      <div class="project-card">
+        <div class="project-body">
+          <h3>PeerKart × G.L. Bajaj</h3>
+          <p>Campus marketplace where students buy, sell, and pass on books, gadgets, and essentials. Available on the web and as Android APK releases.</p>
+          <div class="chips"><span>Web</span><span>Android</span></div>
+          <div class="project-links"><a class="btn small" href="https://github.com/satyamhub/PeerKart-x-GL-Bajaj" target="_blank" rel="noopener">Repository</a><a class="btn small" href="https://glbpeerkart.netlify.app" target="_blank" rel="noopener">Live</a></div>
+        </div>
+      </div>
+      <div class="project-card">
+        <div class="project-body">
+          <h3>HealSync</h3>
+          <p>Hospital appointment management with patient, doctor, and admin roles, doctor availability and slot generation, and database-level double-booking prevention.</p>
+          <div class="chips"><span>Next.js</span><span>TypeScript</span><span>Tailwind CSS</span><span>Prisma</span><span>PostgreSQL</span></div>
+          <div class="project-links"><a class="btn small" href="https://github.com/satyamhub/HealSync" target="_blank" rel="noopener">Repository</a></div>
+        </div>
+      </div>
+      <div class="project-card">
+        <div class="project-body">
+          <h3>Cloudforce Fraud Ring</h3>
+          <p>TigerGraph-powered fraud detection demo that turns one suspicious account into a full mule ring with explainable graph queries. Built for Devacation 2026.</p>
+          <div class="chips"><span>TigerGraph</span><span>Flask</span><span>HTML</span></div>
+          <div class="project-links"><a class="btn small" href="https://github.com/satyamhub/cloudforce-fraud-ring" target="_blank" rel="noopener">Repository</a><a class="btn small" href="https://cloudforce.vercel.app/" target="_blank" rel="noopener">Live</a></div>
+        </div>
+      </div>
+      <div class="project-card">
+        <div class="project-body">
+          <h3>DeskPilot</h3>
+          <p>AI autopilot that converts natural language commands into browser automation, running entirely on a local LLM.</p>
+          <div class="chips"><span>Python</span><span>Ollama</span><span>Playwright</span></div>
+          <div class="project-links"><a class="btn small" href="https://github.com/satyamhub/deskpilot" target="_blank" rel="noopener">Repository</a></div>
+        </div>
+      </div>
     </section>
 
     <section id="resume" class="section alt">
