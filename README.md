<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Paradigm Plumbing Partners LLC — Premium Plumbing Services (Austin, TX)</title>
<meta name="description" content="Paradigm Plumbing Partners LLC — Expert commercial & residential plumbing in Texas. Licensed (TSBPE RMP-44391). Fast service, financing, and preventative memberships." />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Poppins:wght@600;700&display=swap" rel="stylesheet">
<link rel="preload" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" as="style" onload="this.rel='stylesheet'">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/glightbox/dist/css/glightbox.min.css" />
<meta name="theme-color" content="#0b0b0b" />

<!-- Structured data (LocalBusiness) -->
<script type="application/ld+json">
{
  "@context":"https://schema.org",
  "@type":"Plumber",
  "name":"Paradigm Plumbing Partners LLC",
  "url":"https://your-domain.example",
  "logo":"https://your-domain.example/logo.png",
  "telephone":"(512) 538-7628",
  "description":"Commercial and residential plumbing services in Texas. Licensed RMP-44391.",
  "address":{
    "@type":"PostalAddress",
    "addressLocality":"Austin",
    "addressRegion":"TX",
    "addressCountry":"US"
  },
  "areaServed":"Greater Texas Region",
  "foundingDate":"2022"
}
</script>

<style>
  :root{
    --bg-grad-1: #071017;
    --bg-grad-2: #0e222a;
    --gold: #ffd24d;
    --muted: #cfd8dc;
    --glass: rgba(255,255,255,0.04);
    --glass-2: rgba(255,255,255,0.03);
    --accent: rgba(255,210,77,0.12);
    --card-radius: 14px;
    --transition: 280ms cubic-bezier(.2,.9,.2,1);
    --max-width: 1180px;
    --nav-height: 64px;
  }

  /* Page reset */
  *{box-sizing:border-box}
  html,body{height:100%}
  body{
    margin:0;
    font-family:Inter, Poppins, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    color:var(--muted);
    background: linear-gradient(180deg,var(--bg-grad-1) 0%, var(--bg-grad-2) 100%);
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:grayscale;
    line-height:1.5;
  }

  /* Container layout */
  .wrap{max-width:var(--max-width); margin:0 auto; padding:0 20px;}

  /* Top navigation (fixed) */
  header{
    position:fixed; inset:0 0 auto 0; z-index:1000; height:var(--nav-height);
    backdrop-filter: blur(6px); background: linear-gradient(90deg, rgba(0,0,0,0.45), rgba(0,0,0,0.35));
    border-bottom: 1px solid rgba(255,255,255,0.03);
  }
  .nav-inner{max-width:var(--max-width); margin:0 auto; height:100%; display:flex; align-items:center; justify-content:space-between; padding:0 20px;}
  .brand{display:flex; gap:12px; align-items:center; color:var(--gold); font-weight:700; letter-spacing:0.6px; font-size:1.05rem}
  .brand i{font-size:1.1rem}
  nav ul{list-style:none; display:flex; gap:18px; align-items:center; margin:0; padding:0}
  nav a{color:var(--muted); text-decoration:none; font-weight:600; font-size:0.95rem; padding:8px; border-radius:8px; transition:var(--transition)}
  nav a:hover, nav a.active{color:#081217; background:var(--gold); box-shadow:0 6px 18px rgba(255,210,77,0.12);}
  .hamburger{display:none; width:38px; height:38px; align-items:center; justify-content:center; border-radius:10px; background:transparent; border:1px solid rgba(255,255,255,0.04)}

  /* Hero */
  .hero{
    min-height:88vh;
    display:grid;
    grid-template-columns:1fr 420px;
    gap:28px;
    align-items:center;
    padding-top:calc(var(--nav-height) + 28px);
  }
  .hero-left{padding:40px 10px}
  .h-eyebrow{color:var(--gold); font-weight:700; margin-bottom:12px; letter-spacing:0.6px}
  h1{font-family:Poppins, Inter; font-size:2.6rem; margin:0 0 16px; color:var(--gold); line-height:1.03; text-shadow:0 6px 28px rgba(0,0,0,0.6)}
  .hero-sub{color:#cbd5db; font-size:1.05rem; max-width:720px}
  .cta-row{margin-top:22px; display:flex; gap:12px; align-items:center; flex-wrap:wrap}
  .btn{
    display:inline-flex; align-items:center; gap:10px; padding:12px 18px; border-radius:999px; border:2px solid rgba(255,210,77,0.18);
    background:transparent; color:var(--muted); font-weight:700; cursor:pointer; text-decoration:none; transition:var(--transition)
  }
  .btn.primary{background:linear-gradient(90deg,var(--gold), #ffd97f); color:#081217; box-shadow:0 10px 40px rgba(255,210,77,0.08)}
  .btn.ghost{background:transparent; border:1px solid rgba(255,255,255,0.06)}
  .small-meta{margin-top:10px; color:#9fb0b9; font-size:0.9rem}

  /* Right panel: quick card */
  .hero-card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:14px; padding:18px; border:1px solid rgba(255,210,77,0.06); box-shadow: 0 10px 40px rgba(0,0,0,0.6)}
  .hero-card h4{color:var(--gold); margin:0 0 6px; font-size:1.05rem}
  .hero-card p{margin:0 0 12px; color:#cbd5db; font-size:0.95rem}
  .hero-card .stat{display:flex; gap:12px; align-items:center; margin-top:10px}
  .stat .num{font-weight:800; color:#fff; font-size:1.25rem}
  .stat small{color:#9fb0b9}

  /* Sections */
  section{padding:64px 0}
  section h2{color:var(--gold); font-size:1.9rem; margin-bottom:18px}
  .card{background:var(--glass); padding:18px; border-radius:var(--card-radius); border:1px solid rgba(255,255,255,0.03); box-shadow: 0 8px 30px rgba(2,6,10,0.6)}

  /* Services grid */
  .services-grid{display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:16px}
  .service{padding:18px; display:flex; gap:12px; align-items:flex-start; transition:var(--transition)}
  .service:hover{transform:translateY(-8px); box-shadow:0 18px 60px rgba(255,210,77,0.06)}
  .service i{font-size:1.6rem; color:var(--gold); margin-top:6px}
  .service h3{margin:0; font-size:1.05rem; color:#fff}

  /* Quote tool */
  .quote-grid{display:grid; gap:12px; grid-template-columns:repeat(12,1fr)}
  .field{grid-column:span 6}
  .field.small{grid-column:span 4}
  .field.full{grid-column:span 12}
  label{display:block; font-weight:700; color:var(--gold); margin-bottom:6px; font-size:0.9rem}
  select,input,textarea{width:100%; padding:12px; border-radius:10px; border:1px solid rgba(255,255,255,0.04); background:transparent; color:var(--muted)}
  .estimate-box{margin-top:12px; background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); padding:14px; border-radius:10px; border:1px solid rgba(255,255,255,0.03)}
  .breakdown{display:flex; flex-direction:column; gap:8px; color:#dbe7ea}
  .breakdown .row{display:flex; justify-content:space-between; font-weight:600}
  .result-amount{font-size:1.6rem; color:var(--gold); font-weight:800; margin-top:6px}

  /* Projects gallery */
  .gallery{display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:12px}
  .gallery img{width:100%; height:150px; object-fit:cover; border-radius:10px; border:3px solid rgba(255,210,77,0.08)}

  /* Contact */
  .contact-grid{display:grid; gap:16px; grid-template-columns: 1fr 1fr}
  .contact-grid form{display:flex; flex-direction:column; gap:10px}
  .contact-grid input, .contact-grid textarea{padding:12px; background:transparent; border-radius:10px; border:1px solid rgba(255,255,255,0.04); color:var(--muted)}
  .contact-grid button{align-self:flex-start}

  /* Testimonials */
  .testimonials{display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:12px}
  .testimonial{padding:12px; border-radius:10px; background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.02));}

  /* Footer */
  footer{padding:28px 20px; text-align:center; border-top:1px solid rgba(255,255,255,0.03); color:#9fb0b9; margin-top:20px}

  /* Floating action buttons */
  .fab{position:fixed; right:18px; bottom:18px; display:flex; flex-direction:column; gap:10px; z-index:1400}
  .fab a{display:inline-flex; align-items:center; justify-content:center; width:52px; height:52px; border-radius:999px; background:linear-gradient(180deg,var(--gold), #ffd97f); color:#081217; box-shadow:0 12px 36px rgba(0,0,0,0.45); font-weight:700; text-decoration:none}
  .back-top{background:transparent; width:46px; height:46px; border-radius:10px; display:inline-grid; place-items:center; color:var(--muted); border:1px solid rgba(255,255,255,0.04)}

  /* Responsive */
  @media (max-width:1100px){
    .hero{grid-template-columns:1fr; padding-top:calc(var(--nav-height) + 22px)}
    .hero-card{order:2}
  }
  @media (max-width:720px){
    nav ul{display:none}
    .hamburger{display:flex}
    header .nav-open{position:fixed; inset:var(--nav-height) 0 auto 0; background:linear-gradient(180deg, rgba(2,6,10,0.9), rgba(2,6,10,0.98)); padding:12px; z-index:1500}
    .hero{padding:18px 0}
    .field{grid-column:span 12}
    .field.small{grid-column:span 12}
    .contact-grid{grid-template-columns:1fr}
  }

  /* Animated plumbing background (subtle) */
  /* we draw pipes as SVG positioned behind content */
  .bg-viz{position:fixed; inset:0; z-index:0; pointer-events:none; opacity:0.12; mix-blend-mode:screen}
  .content{position:relative; z-index:10}
  .sr-only{position:absolute!important; width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0,0,0,0);white-space:nowrap;border:0}
</style>
</head>
<body>
<!-- subtle decorative SVG pipes / animated shimmer -->
<div class="bg-viz" aria-hidden="true">
  <svg width="100%" height="100%" viewBox="0 0 1600 900" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="g1" x1="0" x2="1">
        <stop offset="0" stop-color="#ffd24d"/>
        <stop offset="1" stop-color="#fff1b3" stop-opacity="0.9"/>
      </linearGradient>
      <linearGradient id="water" x1="0" x2="1">
        <stop offset="0" stop-color="#66d0ff"/>
        <stop offset="1" stop-color="#2f9fff"/>
      </linearGradient>
      <filter id="blurMe"><feGaussianBlur stdDeviation="18" /></filter>
    </defs>

    <!-- Horizontal pipe band -->
    <g transform="translate(0,120)">
      <rect x="0" y="0" width="1600" height="22" rx="12" fill="url(#g1)" opacity="0.12"/>
      <rect x="0" y="0" width="1600" height="8" rx="4" fill="url(#water)" opacity="0.06">
        <animate attributeName="x" from="0" to="-1600" dur="10s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- Vertical pipe band -->
    <g transform="translate(1200,0) rotate(90 0 0)">
      <rect x="-900" y="-12" width="1600" height="22" rx="12" fill="url(#g1)" opacity="0.08"/>
      <rect x="-900" y="-12" width="1600" height="8" rx="4" fill="url(#water)" opacity="0.05">
        <animate attributeName="x" from="0" to="-1600" dur="14s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- Rounded elbow -->
    <g transform="translate(400,460)">
      <path d="M0 0 C120 0 120 160 240 160" stroke="url(#g1)" stroke-width="18" stroke-linecap="round" fill="none" opacity="0.14" />
      <path d="M6 0 C126 0 126 160 246 160" stroke="url(#water)" stroke-width="6" stroke-linecap="round" fill="none" opacity="0.07">
        <animate attributeName="stroke-dashoffset" from="0" to="200" dur="8s" repeatCount="indefinite" />
      </path>
    </g>
  </svg>
</div>

<div class="content">
<header>
  <div class="nav-inner wrap" role="navigation" aria-label="Main navigation">
    <div class="brand" aria-hidden="false">
      <i class="fas fa-tools"></i>
      <span>Paradigm Plumbing</span>
    </div>

    <nav>
      <ul id="main-nav">
        <li><a href="#home" data-link>Home</a></li>
        <li><a href="#services" data-link>Services</a></li>
        <li><a href="#about" data-link>About</a></li>
        
        <li><a href="#projects" data-link>Projects</a></li>
        <li><a href="#contact" data-link>Contact</a></li>
      </ul>
    </nav>

    <button class="hamburger" id="hamb-toggle" aria-label="Open menu" aria-expanded="false">
      <i class="fas fa-bars" style="color:var(--muted)"></i>
    </button>
  </div>
</header>

<main>
  <!-- HERO -->
  <section id="home" class="hero wrap" tabindex="-1" aria-labelledby="home-title">
    <div class="hero-left">
      <div class="h-eyebrow">Licensed • Insured • TSBPE RMP-44391</div>
      <h1 id="home-title">Commercial & Residential </h1>
      <p class="hero-sub">Paradigm Plumbing Partners LLC combines construction experience with elite plumbing craftsmanship to deliver secure, code-compliant systems across the Greater Texas Region. Fast response, financing options, and preventative maintenance memberships available.</p>

      <div class="cta-row" role="region" aria-label="Primary actions">
        <a class="btn primary" href="#contact"><i class="fas fa-phone"></i> Schedule Service</a>
        <button class="btn ghost" id="estimate-cta"><i class="fas fa-calculator"></i> Get Quick Estimate</button>
        <div class="small-meta">Project Manager: <strong>Jose Salazar</strong> · <a href="tel:+15125387628" style="color:var(--gold); text-decoration:none">512-538-7628</a></div>
      </div>
    </div>

    <aside class="hero-card" aria-label="Highlights & quick info">
      <h4>Why choose Paradigm?</h4>
      <p>20+ years construction experience · 10+ years plumbing expertise · Fast on-site diagnostics and premium workmanship.</p>
      <div class="stat"><div><span class="num">RMP-44391</span></div><div><small>TSBPE Registered Master Plumber</small></div></div>
      <div class="stat"><div><span class="num">Priority</span></div><div><small>Memberships & Preventative Maintenance</small></div></div>
      <div style="margin-top:12px">
        <a class="btn" href="#projects"><i class="fas fa-project-diagram"></i> View Projects</a>
      </div>
    </aside>
  </section>

  <!-- SERVICES -->
  <section id="services" class="wrap" aria-labelledby="services-title">
    <h2 id="services-title">Services We Offer</h2>
    <div class="services-grid" role="list">
      <div class="service card" role="listitem">
        <i class="fas fa-building"></i>
        <div>
          <h3>Commercial Construction & TI</h3>
          <p style="margin:6px 0 0; color:#cbd5db">Ground-up systems, tenant improvements, backflow prevention, and phased project coordination.</p>
        </div>
      </div>

      <div class="service card" role="listitem">
        <i class="fas fa-house-chimney"></i>
        <div>
          <h3>Residential New builds & Service </h3>
          <p style="margin:6px 0 0; color:#cbd5db">Custom fixtures, tankless & high-efficiency water heaters, repipes, and smart plumbing solutions.</p>
        </div>
      </div>

      <div class="service card" role="listitem">
        <i class="fas fa-shield-alt"></i>
        <div>
          <h3>Memberships & Preventative Care</h3>
          <p style="margin:6px 0 0; color:#cbd5db">Annual inspections, priority scheduling, discounts on repairs, and system checks.</p>
        </div>
      </div>

      <div class="service card" role="listitem">
        <i class="fas fa-dollar-sign"></i>
        <div>
          <h3>Financing & Flexible Payment</h3>
          <p style="margin:6px 0 0; color:#cbd5db">financing Available to handle larger system upgrades without delay.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="wrap" aria-labelledby="about-title">
    <h2 id="about-title">About Paradigm Plumbing</h2>
    <div class="card" style="display:flex; gap:18px; align-items:flex-start; flex-direction:column">
      <p><strong>Founded:</strong> 2022 · <strong>Licensed:</strong> TSBPE RMP-44391</p>
      <p>Paradigm Plumbing Partners LLC is built on 20+ years of construction experience and over a decade of dedicated plumbing expertise. We value communication, clean job sites, and transparent pricing backed by quality workmanship.</p>
      <p><strong>Leadership</strong><br>Jose Salazar — Project Manager / Estimator · Adriana Salazar — Project Manager / Coordinator</p>
    </div>
  </section>

 

  <!-- Projects -->
  <section id="projects" class="wrap" aria-labelledby="projects-title">
    <h2 id="projects-title">Our Finished Work</h2>
    <div class="gallery card">
      <a href="https://via.placeholder.com/1200x800?text=Repiping" class="images/" data-gallery="projects">
        <img loading="lazy" src="C:\Users\Jose\OneDrive\Desktop\PPP one drive\OneDrive\PPP website\11-08-2025\20220111_083623.jpg
        " alt="Commercial Buildout">
      </a>

      <a href="https://via.placeholder.com/1200x800?text=Water+Heater" class="glightbox" data-gallery="projects">
        <img loading="lazy" src="https://via.placeholder.com/600x400?text=Water+Heater" alt="Water Heater">
      </a>

      <a href="https://via.placeholder.com/1200x800?text=Repiping" class="glightbox" data-gallery="projects">
        <img loading="lazy" src="https://via.placeholder.com/600x400?text=Repiping" alt="Repiping">
      </a>

      <a href="https://via.placeholder.com/1200x800?text=Drain+Cleaning" class="glightbox" data-gallery="projects">
        <img loading="lazy" src="https://via.placeholder.com/600x400?text=Drain+Cleaning" alt="Drain Cleaning">
      </a>
    </div>
  </section>

  <!-- Testimonials & Certifications -->
  <section class="wrap" aria-labelledby="trust-title">
    <h2 id="trust-title">Trusted by Clients & Verified</h2>

    <div style="display:grid; grid-template-columns:1fr 360px; gap:16px">
      <div class="card testimonials" aria-label="Customer testimonials">
        <div class="testimonial">
          <strong>Stephanie R.</strong> <small style="color:#9fb0b9">— Austin, TX</small>
          <p style="margin-top:8px">"Fast, clean, and transparent — Jose identified the problem quickly and fixed our commercial restroom with minimal downtime."</p>
        </div>

        <div class="testimonial">
          <strong>Mark B.</strong> <small style="color:#9fb0b9">— Round Rock, TX</small>
          <p style="margin-top:8px">"The repipe was managed professionally. Project completed on time and the crew left the site spotless."</p>
        </div>
      </div>

      <aside class="card" style="padding:16px">
        <h4 style="margin:0 0 8px; color:var(--gold)">Certifications</h4>
        <p style="margin:0 0 6px"><strong>TSBPE RMP-44391</strong></p>
        <p style="margin:0 0 8px">Verified vendor partners available for financing and equipment warranties.</p>
        <iframe
          title="Google Maps - Service Area"
          width="100%" height="220" style="border:0; border-radius:10px"
          loading="lazy"
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3353.1234567890123!2d-97.7431!3d30.2672!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8644b595b1b1b1b1%3A0x0!2sAustin%2C%20TX!5e0!3m2!1sen!2sus!4v0000000000000" >
        </iframe>
      </aside>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="wrap" aria-labelledby="contact-title">
    <h2 id="contact-title">Request a Consultation</h2>

    <div class="card contact-grid" role="region" aria-label="Contact form and info">
      <div>
        <h4>Contact Info</h4>
        <p><strong>Serving:</strong> Greater Texas Region</p>
        <p><strong>Phone:</strong> <a href="tel:+15125387628" style="color:var(--gold); text-decoration:none">512-538-7628</a></p>
        <p><strong>Email:</strong> <a href="mailto:info@paradigmplumbing.com" style="color:var(--gold); text-decoration:none">info@paradigmplumbing.com</a></p>
        <p style="margin-top:12px">Prefer direct scheduling? Call the number above or use the mobile "Call" button.</p>
        <p style="font-size:0.85rem; color:#9fb0b9; margin-top:14px">We aim to respond within 24 business hours for consultation requests.</p>
      </div>

      <form id="contact-form" aria-label="Contact form (EmailJS)">
        <input type="text" id="c-name" name="user_name" placeholder="Your name" required>
        <input type="email" id="c-email" name="user_email" placeholder="Your email" required>
        <input type="tel" id="c-phone" name="user_phone" placeholder="Phone (optional)">
        <input type="text" id="c-service" name="service_needed" placeholder="Service needed (e.g., Water heater repair)" required>
        <textarea id="c-message" name="message" rows="4" placeholder="Describe the issue or request" required></textarea>
        <div style="display:flex; gap:8px; align-items:center">
          <button id="send-btn" type="submit" class="btn primary"><i class="fas fa-paper-plane"></i> Send Message</button>
          <a class="btn ghost" href="mailto:info@paradigmplumbing.com"><i class="fas fa-envelope"></i> Email Directly</a>
          <div id="send-status" style="margin-left:auto; color:#9fb0b9; font-size:0.95rem"></div>
        </div>
        <div style="margin-top:10px; font-size:0.9rem; color:#9fb0b9">We protect your data and will never sell contact details.</div>
      </form>
    </div>
  </section>

  <div class="wrap" style="margin-top:12px">
    <div class="card" style="padding:12px; text-align:center">
      <small>© <span id="year"></span> Paradigm Plumbing Partners LLC · TSBPE RMP-44391</small>
    </div>
  </div>

  <footer aria-hidden="false" style="margin-top:18px">
    <div class="wrap">
      <small style="color:#8fa3ab">Paradigm Plumbing Partners LLC — Serving the Greater Texas Region · <a href="#" style="color:var(--gold)">Service Areas</a> · <a href="#" style="color:var(--gold)">TSBPE Verification</a></small>
    </div>
  </footer>
</main>

<!-- Floating Action Buttons -->
<div class="fab" role="navigation" aria-label="Quick actions">
  <a href="tel:+15125387628" title="Call now" aria-label="Call now"><i class="fas fa-phone"></i></a>
  <button class="back-top" id="backTop" title="Back to top" aria-label="Back to top"><i class="fas fa-arrow-up"></i></button>
</div>
</div>

<!-- Scripts (deferred) -->
<script defer src="https://cdn.jsdelivr.net/npm/glightbox/dist/js/glightbox.min.js"></script>
<script defer src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/js/all.min.js"></script>

<script>
/* Minimal DOM helpers */
const $ = s => document.querySelector(s);
const $$ = s => Array.from(document.querySelectorAll(s));

/* YEAR */
document.getElementById('year').textContent = new Date().getFullYear();

/* NAV MOBILE */
const hamb = document.getElementById('hamb-toggle');
const nav = document.getElementById('main-nav');
hamb.addEventListener('click', e => {
  const expanded = hamb.getAttribute('aria-expanded') === 'true';
  hamb.setAttribute('aria-expanded', (!expanded).toString());
  nav.classList.toggle('nav-open');
  // simple visual open/close for smaller screens
  if (nav.style.display === 'flex') nav.style.display = 'none';
  else nav.style.display = 'flex';
});

/* SMOOTH SCROLL + SCROLLSPY */
document.querySelectorAll('[data-link]').forEach(a => {
  a.addEventListener('click', e => {
    e.preventDefault();
    const id = a.getAttribute('href');
    document.querySelector(id).scrollIntoView({behavior:'smooth', block:'start'});
    // close mobile nav
    if (window.innerWidth < 720) { nav.style.display = 'none'; hamb.setAttribute('aria-expanded','false')}
  });
});
const sections = $$('main section');
const navLinks = $$('nav a[data-link]');
const obs = new IntersectionObserver(entries => {
  entries.forEach(ent => {
    if (ent.isIntersecting) {
      const id = '#' + ent.target.id;
      navLinks.forEach(a => a.classList.toggle('active', a.getAttribute('href') === id));
    }
  });
},{threshold:0.45});
sections.forEach(s => obs.observe(s));

/* GLIGHTBOX */
document.addEventListener('DOMContentLoaded', () => {
  const lightbox = GLightbox({ selector: '.glightbox' });
});

/* SCROLL ANIMATIONS - lightweight */
const animTargets = $$('section, .card, .service, .hero-card');
const animObserver = new IntersectionObserver(entries => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      e.target.style.transform = 'translateY(0)';
      e.target.style.opacity = 1;
      animObserver.unobserve(e.target);
    }
  });
},{threshold:0.15});
animTargets.forEach(t => {
  t.style.transition = 'transform 620ms var(--transition), opacity 620ms ease';
  t.style.transform = 'translateY(12px)';
  t.style.opacity = 0;
  animObserver.observe(t);
});



/* CONTACT FORM - EmailJS (client-side) */
/*
  This uses EmailJS. Create free account at https://www.emailjs.com/
  1) Create an EmailJS service (e.g., service_xxx)
  2) Create a template with fields: user_name, user_email, user_phone, service_needed, message
  3) Get your user (public) key (REPLACE_ME_USERID) and fill service/template IDs below
*/
const EMAILJS_SERVICE_ID = 'REPLACE_ME_SERVICE_ID';
const EMAILJS_TEMPLATE_ID = 'REPLACE_ME_TEMPLATE_ID';
const EMAILJS_USER_ID = 'REPLACE_ME_USERID'; // public key

// lazy load emailjs when user interacts with form
let emailjsLoaded = false;
function loadEmailJS(){
  if (emailjsLoaded) return Promise.resolve();
  emailjsLoaded = true;
  return new Promise((res,rej) => {
    const s = document.createElement('script');
    s.src = 'https://cdn.jsdelivr.net/npm/emailjs-com@3/dist/email.min.js';
    s.onload = () => {
      if (window.emailjs) {
        emailjs.init(EMAILJS_USER_ID);
        res(true);
      } else rej('EmailJS failed to load');
    };
    s.onerror = e => rej(e);
    document.body.appendChild(s);
  });
}

const contactForm = document.getElementById('contact-form');
const sendStatus = document.getElementById('send-status');

contactForm.addEventListener('submit', async (e) => {
  e.preventDefault();
  sendStatus.textContent = 'Sending...';
  try {
    await loadEmailJS();

    const payload = {
      user_name: $('#c-name').value,
      user_email: $('#c-email').value,
      user_phone: $('#c-phone').value,
      service_needed: $('#c-service').value,
      message: $('#c-message').value
    };

    // If placeholders haven't been replaced, fall back to mailto
    if (EMAILJS_USER_ID.startsWith('REPLACE_ME') || EMAILJS_SERVICE_ID.startsWith('REPLACE_ME')) {
      // fallback: open mailto with prefilled content
      const subject = encodeURIComponent('Paradigm Plumbing Inquiry — ' + payload.service_needed);
      const body = encodeURIComponent(`Name: ${payload.user_name}\nEmail: ${payload.user_email}\nPhone: ${payload.user_phone}\n\n${payload.message}`);
      window.location.href = `mailto:info@paradigmplumbing.com?subject=${subject}&body=${body}`;
      sendStatus.textContent = 'Fallback: opening mail client...';
      return;
    }

    const resp = await window.emailjs.send(EMAILJS_SERVICE_ID, EMAILJS_TEMPLATE_ID, payload);
    sendStatus.textContent = 'Message sent — we will respond shortly.';
    contactForm.reset();
  } catch (err) {
    console.error(err);
    sendStatus.textContent = 'Unable to send via EmailJS. Opening mail client as fallback.';
    // fallback mailto
    const payload = {
      user_name: $('#c-name').value,
      user_email: $('#c-email').value,
      user_phone: $('#c-phone').value,
      service_needed: $('#c-service').value,
      message: $('#c-message').value
    };
    const subject = encodeURIComponent('Paradigm Plumbing Inquiry — ' + payload.service_needed);
    const body = encodeURIComponent(`Name: ${payload.user_name}\nEmail: ${payload.user_email}\nPhone: ${payload.user_phone}\n\n${payload.message}`);
    setTimeout(()=> window.location.href = `mailto:info@paradigmplumbing.com?subject=${subject}&body=${body}`, 800);
  }
});

/* Back to top */
$('#backTop').addEventListener('click', () => window.scrollTo({top:0, behavior:'smooth'}));


</script>
</body>
</html>
