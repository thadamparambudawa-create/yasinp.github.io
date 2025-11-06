<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <title>Muhammed Yasin P — Creative & Digital Solutions</title>
  <meta name="description" content="Creative professional skilled in Adobe Premiere Pro, After Effects, Photoshop, Illustrator, and front-end web development. Delivering impactful visual and digital experiences." />
  <meta name="author" content="Muhammed Yasin P" />

  <!-- ✅ Favicon -->
  <link rel="icon" type="image/png" href="favicon.png" />

  <!-- ✅ SEO & OG Meta -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://yasinp.in/" />
  <meta property="og:title" content="Muhammed Yasin P — Creative & Digital Solutions" />
  <meta property="og:description" content="Video Editor • Graphic Designer • Front-End Developer — crafting impactful digital content with clarity and creativity." />
  <meta property="og:image" content="https://yourwebsite.com/preview.jpg" />

  <!-- ✅ Twitter Card -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Muhammed Yasin P — Creative & Digital Solutions" />
  <meta name="twitter:description" content="Creative designer & developer specializing in modern digital content." />
  <meta name="twitter:image" content="https://yourwebsite.com/preview.jpg" />

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --muted:#9aa4b2;
      --accent:#06b6d4;
      --glass:rgba(255,255,255,0.04);
      --radius:14px;
      --max:1100px;
      color-scheme:dark;
    }
    *{box-sizing:border-box;}
    html,body{
      height:100%;margin:0;
      font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;
      color:#e6eef6;
      background:linear-gradient(180deg,var(--bg),#071024 120%);
    }
    a{transition:all .2s ease;}
    .container{max-width:var(--max);margin:36px auto;padding:28px;}
    header{display:flex;align-items:center;justify-content:space-between;gap:18px;}
    .brand{display:flex;align-items:center;gap:12px;text-decoration:none;color:inherit;}
    .logo{
      width:44px;height:44px;border-radius:10px;
      background:linear-gradient(135deg,var(--accent),#7c3aed);
      display:flex;align-items:center;justify-content:center;
      font-weight:800;color:#061019;
    }
    nav{display:flex;gap:14px;align-items:center;}
    nav a{color:var(--muted);text-decoration:none;padding:8px 12px;border-radius:10px;}
    nav a:hover{color:var(--accent);}
    nav a.primary{background:linear-gradient(90deg,rgba(6,182,212,0.12),rgba(124,58,237,0.08));color:var(--accent);font-weight:600;}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:32px;align-items:center;margin-top:28px;}
    .card{
      background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);
      padding:28px;border-radius:var(--radius);
      box-shadow:0 6px 30px rgba(2,6,23,0.6);
      border:1px solid rgba(255,255,255,0.03);
    }
    h1{font-size:34px;margin:0 0 10px;line-height:1.05;}
    p.lead{color:var(--muted);margin:0 0 18px;}
    .cta{display:flex;gap:12px;margin-top:12px;}
    .btn{
      padding:12px 16px;border-radius:12px;text-decoration:none;font-weight:600;
      display:inline-flex;align-items:center;gap:10px;transition:all .2s ease;
    }
    .btn.primary{background:linear-gradient(90deg,var(--accent),#7c3aed);color:#041018;}
    .btn.primary:hover{opacity:.9;}
    .btn.ghost{border:1px solid rgba(255,255,255,0.06);color:var(--muted);background:transparent;}
    .btn.ghost:hover{border-color:var(--accent);color:var(--accent);}
    .stats{display:flex;gap:12px;margin-top:20px;}
    .stat{background:var(--glass);padding:12px;border-radius:10px;text-align:center;min-width:92px;}
    .stat strong{display:block;font-size:18px;}
    .stat small{color:var(--muted);}
    .panel{padding:18px;border-radius:12px;background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);}
    .features{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;}
    .feature{padding:12px;border-radius:10px;background:rgba(255,255,255,0.012);}
    .feature:hover{background:rgba(255,255,255,0.05);}
    form input,form textarea{
      width:100%;padding:10px;border-radius:10px;
      background:transparent;border:1px solid rgba(255,255,255,0.04);color:inherit;
    }
    form label{font-size:13px;color:var(--muted);display:block;margin-bottom:6px;}
    footer{margin-top:38px;color:var(--muted);display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:8px;}
    @media(max-width:900px){.hero{grid-template-columns:1fr;}nav{display:none;}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <a class="brand" href="#">
        <div class="logo">YN</div>
        <div>
          <div style="font-weight:700">yacn.___</div>
          <div style="font-size:12px;color:var(--muted)">Video Editor • Graphic Designer • Front-End Developer</div>
        </div>
      </a>
      <nav>
        <a href="#services">Services</a>
        <a href="#work">Work</a>
        <a href="#contact" class="primary">Contact</a>
      </nav>
    </header>

    <main class="hero">
      <section class="card">
        <h1>Crafting modern visuals & digital experiences that inspire</h1>
        <p class="lead">From video editing and motion graphics to full-stack web development — I bring ideas to life through design, code, and creativity.</p>

        <div class="cta">
          <a class="btn primary" href="#contact">Get in touch</a>
          <a class="btn ghost" href="#work">View portfolio</a>
        </div>

        <div class="stats" aria-hidden>
          <div class="stat"><strong>8+</strong><small>Years Experience</small></div>
          <div class="stat"><strong>60+</strong><small>Projects</small></div>
          <div class="stat"><strong>20%</strong><small>Avg Growth</small></div>
        </div>

        <section style="margin-top:18px">
          <h3 style="margin:0 0 10px 0">Core Expertise</h3>
          <div class="features">
            <div class="feature">
              <strong>Adobe Premiere Pro</strong>
              <div style="font-size:13px;color:var(--muted)">Professional video editing, color grading & cinematic storytelling.</div>
            </div>
            <div class="feature">
              <strong>After Effects</strong>
              <div style="font-size:13px;color:var(--muted)">Motion graphics, VFX, and high-end animation for digital content.</div>
            </div>
            <div class="feature">
              <strong>Photoshop & Illustrator</strong>
              <div style="font-size:13px;color:var(--muted)">Creative visuals, posters, and branding assets for businesses.</div>
            </div>
            <div class="feature">
              <strong>CapCut & Social Media Editing</strong>
              <div style="font-size:13px;color:var(--muted)">Trend-based short-form content with transitions & effects.</div>
            </div>
            <div class="feature">
              <strong>Visual Studio Code</strong>
              <div style="font-size:13px;color:var(--muted)">Front-end web development & modern UI/UX scripting.</div>
            </div>
          </div>
        </section>
      </section>

      <aside>
        <div class="panel card">
          <h3 style="margin-top:0">Quick Contact</h3>
          <p style="color:var(--muted);font-size:14px;margin-bottom:12px">Tell me about your project — I typically reply within 24–48 hours.</p>

          <form id="contact" action="mailto:yaxn.mohz@gmail.com?subject=New%20Project%20Inquiry" method="GET" enctype="text/plain">
            <label for="name">Name</label>
            <input id="name" name="name" type="text" placeholder="Your name" required>

            <label for="email" style="margin-top:10px">Email</label>
            <input id="email" name="email" type="email" placeholder="you@example.com" required>

            <label for="message" style="margin-top:10px">Message</label>
            <textarea id="message" name="message" rows="5" placeholder="Tell me about the project..." required></textarea>

            <div style="display:flex;gap:8px;margin-top:12px">
              <button class="btn primary" type="submit">Send</button>
              <button class="btn ghost" type="reset">Reset</button>
            </div>
          </form>

          <hr style="border:none;border-top:1px solid rgba(255,255,255,0.03);margin:16px 0">
          <div style="font-size:13px;color:var(--muted)">
            <div><strong>👤 Name:</strong> Muhammed Yasin P</div>
            <div style="margin-top:6px"><strong>📧 Email:</strong> <a href="mailto:yaxn.mohz@gmail.com" style="color:var(--accent);text-decoration:none;">yaxn.mohz@gmail.com</a></div>
            <div style="margin-top:6px"><strong>📞 Phone:</strong> <a href="tel:+918086723763" style="color:var(--accent);text-decoration:none;">+91 8086 7237 63</a></div>
            <div style="margin-top:6px"><strong>📍 Location:</strong> <a href="https://www.google.com/maps/place/Kerala,+India/" target="_blank" style="color:var(--accent);text-decoration:none;">Kerala, India</a></div>
            <div style="margin-top:6px"><strong>📸 Instagram:</strong> <a href="https://www.instagram.com/sidheeqiyyacampus?utm_source=qr" target="_blank" style="color:var(--accent);text-decoration:none;">@sidheeqiyyacampus</a></div>
          </div>
        </div>
      </aside>
    </main>

    <footer>
      <div>&copy; <span id="year"></span> Muhammed Yasin P — Crafted with care.</div>
      <div style="font-size:13px;color:var(--muted)">Built with HTML & CSS • Fully Responsive</div>
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
    document.getElementById('contact').addEventListener('submit',function(){
      alert("✅ Message ready to send! Your email app will open now.");
    });
  </script>
</body>
</html>
