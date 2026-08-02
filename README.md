<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Zainab Amin · Pharm.D., Health Services Research</title>
<meta name="description" content="Zainab Amin, Pharm.D., aspiring public health PhD researcher. Systematic review methodology, community health interventions, and health services research." />
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,450;0,9..144,600;1,9..144,400;1,9..144,500&family=Inter:wght@400;500;600;700&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --paper: #EEF1EA;
    --paper-deep: #E4E9DF;
    --ink: #172A22;
    --ink-soft: #45564C;
    --teal: #1F4D45;
    --teal-deep: #123531;
    --coral: #E1552B;
    --gold: #D6A23C;
    --line: rgba(23,42,34,0.14);
    --card: #F7F8F3;
    --max: 1120px;
  }
  *{box-sizing:border-box; margin:0; padding:0;}
  html{scroll-behavior:smooth;}
  body{
    background:var(--paper);
    color:var(--ink);
    font-family:'Inter', sans-serif;
    line-height:1.6;
    -webkit-font-smoothing:antialiased;
    overflow-x:hidden;
  }
  ::selection{ background:var(--gold); color:var(--teal-deep); }
  a{ color:inherit; text-decoration:none; }
  img{max-width:100%; display:block;}
  .wrap{ max-width:var(--max); margin:0 auto; padding:0 32px; }
  h1,h2,h3,h4{ font-family:'Fraunces', serif; font-weight:450; line-height:1.08; letter-spacing:-0.01em; }
  em{ font-style:italic; font-weight:500; color:var(--teal); }
  .mono{ font-family:'IBM Plex Mono', monospace; }
  .eyebrow{
    font-family:'IBM Plex Mono', monospace;
    font-size:12.5px;
    letter-spacing:0.14em;
    text-transform:uppercase;
    color:var(--coral);
    display:flex; align-items:center; gap:10px;
    margin-bottom:18px;
  }
  .eyebrow::before{ content:""; width:22px; height:1px; background:var(--coral); display:inline-block; }
  .visually-hidden{ position:absolute; width:1px; height:1px; overflow:hidden; clip:rect(0 0 0 0); }

  @media (prefers-reduced-motion: reduce){
    *{ animation-duration:0.001ms !important; animation-iteration-count:1 !important; transition-duration:0.001ms !important; scroll-behavior:auto !important; }
  }

  /* ---------- NAV ---------- */
  header.site{
    position:sticky; top:0; z-index:100;
    background:rgba(238,241,234,0.86);
    backdrop-filter:blur(10px);
    border-bottom:1px solid var(--line);
  }
  nav{ display:flex; align-items:center; justify-content:space-between; padding:18px 32px; max-width:var(--max); margin:0 auto; }
  .brand{ font-family:'Fraunces', serif; font-size:19px; font-weight:500; }
  .brand span{ color:var(--coral); }
  .navlinks{ display:flex; gap:30px; font-size:14.5px; font-weight:500; }
  .navlinks a{ position:relative; padding:4px 0; color:var(--ink-soft); transition:color .2s; }
  .navlinks a:hover, .navlinks a:focus-visible{ color:var(--teal-deep); }
  .navlinks a::after{
    content:""; position:absolute; left:0; bottom:0; width:0; height:1.5px; background:var(--coral);
    transition:width .25s ease;
  }
  .navlinks a:hover::after, .navlinks a:focus-visible::after{ width:100%; }
  .navtoggle{ display:none; background:none; border:none; cursor:pointer; padding:6px; }
  .navtoggle span{ display:block; width:22px; height:2px; background:var(--ink); margin:5px 0; }
  @media (max-width:820px){
    .navlinks{
      position:fixed; top:64px; right:0; left:0; background:var(--paper);
      flex-direction:column; gap:0; padding:8px 32px 20px; border-bottom:1px solid var(--line);
      transform:translateY(-8px); opacity:0; pointer-events:none; transition:all .22s ease;
    }
    .navlinks.open{ transform:translateY(0); opacity:1; pointer-events:auto; }
    .navlinks a{ padding:12px 0; border-bottom:1px solid var(--line); }
    .navtoggle{ display:block; }
  }

  /* ---------- HERO ---------- */
  .hero{ padding:88px 0 60px; position:relative; }
  .hero-grid{ display:grid; grid-template-columns:1.15fr 0.85fr; gap:56px; align-items:center; }
  @media (max-width:900px){ .hero-grid{ grid-template-columns:1fr; } }
  .hero h1{ font-size:clamp(36px, 5.4vw, 60px); margin-bottom:22px; }
  .hero p.lede{ font-size:18px; color:var(--ink-soft); max-width:52ch; margin-bottom:32px; }
  .cta-row{ display:flex; gap:14px; flex-wrap:wrap; margin-bottom:44px; }
  .btn{
    font-family:'IBM Plex Mono', monospace; font-size:13.5px; letter-spacing:0.02em;
    padding:13px 22px; border-radius:2px; display:inline-flex; align-items:center; gap:8px;
    transition:all .2s ease; border:1px solid var(--teal-deep);
  }
  .btn-solid{ background:var(--teal-deep); color:var(--paper); }
  .btn-solid:hover{ background:var(--teal); transform:translateY(-1px); }
  .btn-ghost{ color:var(--teal-deep); }
  .btn-ghost:hover{ background:var(--card); transform:translateY(-1px); }

  .quickfacts{ display:grid; grid-template-columns:1fr 1fr; gap:1px; background:var(--line); border:1px solid var(--line); }
  .qf{ background:var(--paper); padding:16px 18px; }
  .qf .num{ font-family:'Fraunces', serif; font-size:22px; color:var(--teal-deep); display:block; }
  .qf .lbl{ font-family:'IBM Plex Mono', monospace; font-size:11px; text-transform:uppercase; letter-spacing:0.06em; color:var(--ink-soft); }

  /* population dot visual */
  .dotfield{
    background:var(--teal-deep); border-radius:4px; padding:34px 28px; position:relative;
    box-shadow: 8px 8px 0 var(--gold);
  }
  .dotfield h3{ color:var(--paper); font-size:15px; font-family:'IBM Plex Mono', monospace; font-weight:400; text-transform:uppercase; letter-spacing:0.08em; margin-bottom:22px; opacity:0.85; }

  .barchart{ display:flex; flex-direction:column; gap:20px; }
  .barrow .barlabel{ display:flex; justify-content:space-between; align-items:baseline; font-family:'IBM Plex Mono', monospace; font-size:12px; color:var(--paper); margin-bottom:7px; }
  .barrow .barlabel .bnum{ font-family:'Fraunces', serif; font-size:17px; color:var(--gold); }
  .barrow .barlabel .blbl{ color:#BFD1C4; text-align:right; max-width:60%; }
  .bartrack{ height:8px; background:rgba(238,241,234,0.14); border-radius:2px; overflow:hidden; }
  .barfill{ height:100%; width:0%; border-radius:2px; background:var(--gold); transition:width 1.1s cubic-bezier(.2,.8,.2,1); }

  /* ---------- SECTION SHELL ---------- */
  section{ padding:96px 0; border-top:1px solid var(--line); }
  section:first-of-type{ border-top:none; }
  .section-head{ display:flex; justify-content:space-between; align-items:flex-end; gap:24px; margin-bottom:52px; flex-wrap:wrap; }
  .section-head h2{ font-size:clamp(28px, 3.6vw, 40px); max-width:16ch; }
  .section-head p{ color:var(--ink-soft); max-width:34ch; font-size:15px; }

  /* ---------- ABOUT ---------- */
  .about-grid{ display:grid; grid-template-columns:1.3fr 0.9fr; gap:60px; }
  @media (max-width:860px){ .about-grid{ grid-template-columns:1fr; } }
  .about-grid p{ margin-bottom:18px; color:var(--ink-soft); font-size:16px; }
  .about-grid p strong{ color:var(--ink); font-weight:600; }
  blockquote{
    font-family:'Fraunces', serif; font-style:italic; font-size:22px; color:var(--teal-deep);
    border-left:2px solid var(--coral); padding-left:22px; margin:30px 0;
  }
  .factcard{ background:var(--card); border:1px solid var(--line); padding:26px; }
  .factcard dl{ display:grid; grid-template-columns:auto 1fr; gap:10px 14px; font-size:14px; }
  .factcard dt{ font-family:'IBM Plex Mono', monospace; color:var(--ink-soft); font-size:12px; text-transform:uppercase; letter-spacing:0.04em; padding-top:2px; }
  .factcard dd{ font-weight:500; }
  .factcard h4{ font-size:16px; margin-bottom:16px; text-transform:uppercase; letter-spacing:0.05em; font-family:'IBM Plex Mono', monospace; font-weight:500; color:var(--teal-deep); }
  .taglist{ display:flex; flex-wrap:wrap; gap:8px; margin-top:20px; }
  .tag{
    font-family:'IBM Plex Mono', monospace; font-size:11.5px; padding:6px 11px; border:1px solid var(--line);
    background:var(--paper); color:var(--ink-soft);
  }

  /* ---------- RESEARCH ---------- */
  .research-callout{
    background:var(--teal-deep); color:var(--paper); padding:38px 36px; margin-bottom:44px;
    display:grid; grid-template-columns:1fr; gap:8px;
  }
  .research-callout .eyebrow{ color:var(--gold); }
  .research-callout .eyebrow::before{ background:var(--gold); }
  .research-callout p{ font-size:16.5px; color:#DCE6DF; max-width:76ch; }
  .research-list{ display:grid; grid-template-columns:1fr 1fr; gap:2px; background:var(--line); border:1px solid var(--line); }
  @media (max-width:800px){ .research-list{ grid-template-columns:1fr; } }
  .rcard{ background:var(--card); padding:30px 28px; }
  .rcard .stage{ font-family:'IBM Plex Mono', monospace; font-size:11px; color:var(--coral); text-transform:uppercase; letter-spacing:0.06em; margin-bottom:10px; }
  .rcard h3{ font-size:20px; margin-bottom:12px; }
  .rcard p{ color:var(--ink-soft); font-size:14.5px; margin-bottom:14px; }
  .rcard .method{ display:flex; flex-wrap:wrap; gap:6px; }

  /* ---------- EXPERIENCE (timeline) ---------- */
  .timeline{ position:relative; padding-left:28px; border-left:1px solid var(--line); }
  .trow{ position:relative; padding-bottom:46px; }
  .trow:last-child{ padding-bottom:0; }
  .trow::before{
    content:""; position:absolute; left:-33px; top:5px; width:9px; height:9px; border-radius:50%;
    background:var(--paper); border:2px solid var(--coral);
  }
  .trow .when{ font-family:'IBM Plex Mono', monospace; font-size:12px; color:var(--ink-soft); text-transform:uppercase; letter-spacing:0.05em; margin-bottom:6px; display:block; }
  .trow h3{ font-size:20px; margin-bottom:4px; }
  .trow .org{ color:var(--teal-deep); font-weight:600; font-size:14.5px; margin-bottom:10px; }
  .trow p{ color:var(--ink-soft); font-size:15px; max-width:70ch; }

  /* ---------- IMPACT (cards) ---------- */
  .impact-grid{ display:grid; grid-template-columns:repeat(3,1fr); gap:2px; background:var(--line); border:1px solid var(--line); }
  @media (max-width:860px){ .impact-grid{ grid-template-columns:1fr 1fr; } }
  @media (max-width:560px){ .impact-grid{ grid-template-columns:1fr; } }
  @media (max-width:700px){ .camp-gallery{ grid-template-columns:1fr !important; } }
  .icard{ background:var(--card); padding:28px 24px; }
  .icard .big{ font-family:'Fraunces', serif; font-size:34px; color:var(--coral); display:block; margin-bottom:8px; }
  .icard h4{ font-size:15.5px; font-family:'Inter'; font-weight:600; margin-bottom:8px; }
  .icard p{ font-size:13.8px; color:var(--ink-soft); }

  /* ---------- LEADERSHIP ---------- */
  .lead-grid{ display:grid; grid-template-columns:repeat(3,1fr); gap:24px; }
  @media (max-width:820px){ .lead-grid{ grid-template-columns:1fr; } }
  .lcard{ border:1px solid var(--line); padding:26px; background:var(--card); position:relative; }
  .lcard .role{ font-family:'IBM Plex Mono', monospace; font-size:11.5px; text-transform:uppercase; color:var(--coral); letter-spacing:0.05em; margin-bottom:10px; }
  .lcard h3{ font-size:18px; margin-bottom:4px; }
  .lcard .org{ font-size:13.5px; color:var(--ink-soft); margin-bottom:14px; }
  .lcard p{ font-size:14px; color:var(--ink-soft); }

  /* ---------- HONORS ---------- */
  .honors{ columns:2; column-gap:48px; }
  @media (max-width:700px){ .honors{ columns:1; } }
  .honors li{ list-style:none; padding:14px 0; border-bottom:1px solid var(--line); break-inside:avoid; display:flex; justify-content:space-between; gap:14px; font-size:14.5px; }
  .honors li .yr{ font-family:'IBM Plex Mono', monospace; color:var(--coral); font-size:12.5px; white-space:nowrap; }

  /* ---------- PUBLICATIONS ---------- */
  .pub{ border:1px solid var(--line); background:var(--card); padding:26px 28px; margin-bottom:16px; }
  .pub .kind{ font-family:'IBM Plex Mono', monospace; font-size:11px; text-transform:uppercase; letter-spacing:0.06em; color:var(--teal-deep); margin-bottom:8px; }
  .pub h3{ font-size:17px; margin-bottom:6px; font-weight:600; font-family:'Inter'; }
  .pub p{ font-size:13.8px; color:var(--ink-soft); }
  .conflist{ margin-top:30px; display:flex; flex-wrap:wrap; gap:10px; }
  .conflist span{ font-family:'IBM Plex Mono', monospace; font-size:12px; border:1px solid var(--line); padding:8px 12px; color:var(--ink-soft); }

  /* ---------- CERTIFICATIONS ---------- */
  .cert-grid{ display:grid; grid-template-columns:repeat(3,1fr); gap:2px; background:var(--line); border:1px solid var(--line); }
  @media (max-width:860px){ .cert-grid{ grid-template-columns:1fr 1fr; } }
  @media (max-width:560px){ .cert-grid{ grid-template-columns:1fr; } }
  .certcard{ background:var(--card); padding:26px 24px; display:flex; flex-direction:column; }
  .certcard .stage{ font-family:'IBM Plex Mono', monospace; font-size:11px; color:var(--coral); text-transform:uppercase; letter-spacing:0.06em; margin-bottom:10px; }
  .certcard h3{ font-size:16.5px; margin-bottom:6px; font-family:'Inter'; font-weight:600; }
  .certcard p{ font-size:13.5px; color:var(--ink-soft); margin-bottom:16px; }
  .certcard a{ margin-top:auto; font-family:'IBM Plex Mono', monospace; font-size:12.5px; color:var(--teal-deep); border-bottom:1px solid var(--teal-deep); align-self:flex-start; padding-bottom:2px; }
  .certcard a:hover{ color:var(--coral); border-color:var(--coral); }

  /* ---------- SKILLS ---------- */
  .skills-grid{ display:grid; grid-template-columns:repeat(4,1fr); gap:2px; background:var(--line); border:1px solid var(--line); }
  @media (max-width:860px){ .skills-grid{ grid-template-columns:1fr 1fr; } }
  @media (max-width:520px){ .skills-grid{ grid-template-columns:1fr; } }
  .skillcol{ background:var(--card); padding:26px 22px; }
  .skillcol h4{ font-family:'IBM Plex Mono', monospace; font-size:12px; text-transform:uppercase; letter-spacing:0.05em; color:var(--coral); margin-bottom:16px; }
  .skillcol ul{ list-style:none; }
  .skillcol li{ font-size:14px; color:var(--ink-soft); padding:6px 0; border-bottom:1px dashed var(--line); }
  .skillcol li:last-child{ border-bottom:none; }

  /* ---------- CONTACT ---------- */
  .contact{ background:var(--teal-deep); color:var(--paper); border-top:none; }
  .contact h2{ color:var(--paper); font-size:clamp(30px,4.6vw,48px); max-width:20ch; }
  .contact p.lede{ color:#CBD8CE; max-width:54ch; margin:18px 0 40px; font-size:16.5px; }
  .contact-links{ display:flex; flex-wrap:wrap; gap:16px; }
  .clink{
    border:1px solid rgba(238,241,234,0.35); padding:16px 22px; display:flex; align-items:center; gap:10px;
    font-family:'IBM Plex Mono', monospace; font-size:13.5px; transition:all .2s;
  }
  .clink:hover{ background:rgba(238,241,234,0.08); border-color:var(--gold); }

  footer{ padding:30px 0; text-align:center; font-family:'IBM Plex Mono', monospace; font-size:12px; color:var(--ink-soft); }

  .reveal{ opacity:0; transform:translateY(18px); transition:opacity .6s ease, transform .6s ease; }
  .reveal.in{ opacity:1; transform:translateY(0); }

  /* micro-interactions */
  .rcard, .icard, .lcard, .pub, .factcard, .qf, .certcard{
    transition: transform .22s ease, box-shadow .22s ease, border-color .22s ease;
  }
  .rcard:hover, .icard:hover, .lcard:hover, .pub:hover, .certcard:hover{
    transform: translateY(-4px);
    box-shadow: 0 10px 24px rgba(23,42,34,0.08);
    position:relative; z-index:2;
  }
  .qf:hover{ background:var(--card); }
  .tag{ transition: background .18s ease, color .18s ease, border-color .18s ease; }
  .tag:hover{ background:var(--teal-deep); color:var(--paper); border-color:var(--teal-deep); }
  .btn{ transition: all .2s ease, transform .15s ease; }
  .btn:hover{ transform: translateY(-2px); }

  /* conference marquee */
  .marquee{ overflow:hidden; position:relative; margin-top:30px; -webkit-mask-image:linear-gradient(90deg, transparent, #000 8%, #000 92%, transparent); mask-image:linear-gradient(90deg, transparent, #000 8%, #000 92%, transparent); }
  .marquee-track{ display:flex; gap:14px; width:max-content; animation: scroll-left 26s linear infinite; }
  .marquee:hover .marquee-track{ animation-play-state: paused; }
  .marquee-track span{ font-family:'IBM Plex Mono', monospace; font-size:12px; border:1px solid var(--line); padding:8px 14px; color:var(--ink-soft); white-space:nowrap; }
  @keyframes scroll-left{ from{ transform:translateX(0); } to{ transform:translateX(-50%); } }
</style>
</head>
<body>

<header class="site">
  <nav>
    <a class="brand" href="#top">Zainab Amin <span>·</span> PharmD</a>
    <button class="navtoggle" aria-label="Toggle navigation" aria-expanded="false" id="navBtn">
      <span></span><span></span><span></span>
    </button>
    <div class="navlinks" id="navLinks">
      <a href="#about">About</a>
      <a href="#research">Research</a>
      <a href="#experience">Experience</a>
      <a href="#impact">Public Health Impact</a>
      <a href="#leadership">Leadership</a>
      <a href="#skills">Skills</a>
      <a href="#certifications">Certifications</a>
      <a href="#publications">Publications</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>
</header>

<main id="top">

  <!-- HERO -->
  <section class="hero" style="border-top:none;">
    <div class="wrap hero-grid">
      <div>
        <p class="eyebrow">Pharm.D. → Ph.D. in Public Health</p>
        <h1>Where one prescription review becomes <em>population-level</em> evidence.</h1>
        <p class="lede">I'm Zainab, a Pharm.D. graduate from Lahore, Pakistan, moving from bedside pharmacy practice into health services research. I'm looking for a doctoral program in <strong>public health</strong> to dig deeper into <strong>health services research</strong>, <strong>global health</strong>, <strong>implementation science</strong>, <strong>clinical decision support tools</strong>, and <strong>digital health &amp; clinical AI</strong>: how care actually gets delivered, how proven interventions actually reach patients, and how emerging technology can be validated, not just deployed, inside that system.</p>
        <div class="taglist" style="margin-bottom:28px;">
          <span class="tag">Public Health</span>
          <span class="tag">Health Services Research</span>
          <span class="tag">Global Health</span>
          <span class="tag">Implementation Science</span>
          <span class="tag">Clinical Decision Support</span>
          <span class="tag">Digital Health</span>
          <span class="tag">Clinical AI</span>
        </div>
        <div class="cta-row">
          <a class="btn btn-solid" href="#research">Read My Research</a>
          <a class="btn btn-ghost" href="Zainab_Amin_CV.pdf" target="_blank" rel="noopener">Download CV ↗</a>
          <a class="btn btn-ghost" href="#contact">Get in Touch</a>
        </div>
        <div class="quickfacts">
          <div class="qf"><span class="num">3.36 / 4.0</span><span class="lbl">CGPA</span></div>
          <div class="qf"><span class="num">2021–26</span><span class="lbl">Merit Scholar</span></div>
          <div class="qf"><span class="num">UMT</span><span class="lbl">Lahore, Pakistan</span></div>
          <div class="qf"><span class="num">In Review</span><span class="lbl">First Publication</span></div>
        </div>
      </div>
      <div class="dotfield">
        <h3>Fieldwork, by the numbers</h3>
        <div class="barchart">
          <div class="barrow">
            <div class="barlabel"><span class="bnum countup" data-target="100" data-suffix="+">0</span><span class="blbl">Patients screened, community health camps</span></div>
            <div class="bartrack"><div class="barfill" data-width="100" style="background:var(--gold);"></div></div>
          </div>
          <div class="barrow">
            <div class="barlabel"><span class="bnum">50–60</span><span class="blbl">Prescriptions reviewed per hospital shift</span></div>
            <div class="bartrack"><div class="barfill" data-width="60" style="background:#EFE3C4;"></div></div>
          </div>
          <div class="barrow">
            <div class="barlabel"><span class="bnum countup" data-target="20" data-suffix="+">0</span><span class="blbl">Team members led, Pharmacy Student Society</span></div>
            <div class="bartrack"><div class="barfill" data-width="20" style="background:var(--coral);"></div></div>
          </div>
          <div class="barrow">
            <div class="barlabel"><span class="bnum countup" data-target="10" data-suffix="+">0</span><span class="blbl">TB patients, medication adherence campaigns</span></div>
            <div class="bartrack"><div class="barfill" data-width="10" style="background:#9FC9BC;"></div></div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <div class="wrap about-grid">
      <div>
        <p class="eyebrow">Background</p>
        <h2>Trained at the bedside. <em>Thinking at the population level.</em></h2>
        <p>I started pharmacy wanting to understand the body one patient at a time: dosages, interactions, the 7R rule, one chart at a time. Five years in, that instinct hasn't gone away. It's scaled up.</p>
        <p>At <strong>Evercare Hospital</strong>, reviewing 50–60 prescriptions a shift and running tuberculosis adherence campaigns showed me how much of health outcomes is <strong>systems</strong>, not just molecules: access, follow-through, and the education gap between a diagnosis and a patient actually taking their medication. At <strong>Citi Pharma</strong>, I saw the same story from the supply side, how regulatory documentation and quality assurance quietly decide who gets a safe medicine and who doesn't.</p>
        <blockquote>The most interesting question in pharmacy stopped being "what's the right dose" and became "why doesn't the right dose reach the right person."</blockquote>
        <p>My senior thesis, a systematic review on cognitive and language impairments in virtual autism, was my first real attempt to answer questions like that with rigor instead of instinct. That's the work I want to keep doing, at doctoral depth: <strong>health services research</strong> that treats delivery, adherence, and equity as seriously as pharmacology does.</p>
        <p>The same question follows me into digital health. A year embedded with <strong>Voho.AI</strong>, an early-stage startup building AI voice agents for healthcare, put me on the other side of the AI hype cycle: watching how easily a clinical claim can outrun its evidence. I'm increasingly drawn to the scientist's version of that problem, evaluating and validating AI-assisted clinical tools with the same rigor I'd apply to a systematic review, so that "the model says so" is never treated as a substitute for evidence.</p>
      </div>
      <div class="factcard">
        <h4>Research Interests</h4>
        <p style="font-size:14.5px; color:var(--ink-soft); margin-bottom:18px;">Health services research and delivery · global health · implementation science · medication safety and antibiotic stewardship in low-resource settings · community-based public health interventions · systematic review and evidence synthesis methodology · digital health and evidence-based validation of clinical AI tools</p>
        <h4>At a Glance</h4>
        <dl>
          <dt>Degree</dt><dd>Doctor of Pharmacy (Pharm.D.)</dd>
          <dt>Institution</dt><dd>University of Management &amp; Technology, Lahore</dd>
          <dt>Thesis</dt><dd>Cognitive &amp; language impairments in virtual autism: a systematic review</dd>
          <dt>Advisor</dt><dd>Dr. Rabia Altaf</dd>
          <dt>Fellowship</dt><dd>URISE Research Fellow</dd>
        </dl>
        <div class="taglist">
          <span class="tag">Health Services Research</span>
          <span class="tag">Global Health</span>
          <span class="tag">Implementation Science</span>
          <span class="tag">Evidence Synthesis</span>
          <span class="tag">Health Equity</span>
          <span class="tag">Clinical AI Validation</span>
        </div>
      </div>
    </div>
  </section>

  <!-- RESEARCH -->
  <section id="research">
    <div class="wrap">
      <div class="section-head">
        <h2>Evidence, built the slow, correct way.</h2>
        <p>Two research threads: a systematic review on virtual autism, and a community pharmacy study on antibiotic stewardship.</p>
      </div>

      <div class="research-callout">
        <p class="eyebrow">Flagship · Senior Thesis</p>
        <h3 style="color:var(--paper); font-size:24px; margin-bottom:10px;">Comparative Analysis of Cognitive and Language Impairments in Virtual Autism</h3>
        <p>A comprehensive systematic review built on a PICO framework, screening 300+ studies across PubMed and Cochrane, conducted under PRISMA guidelines with evidence synthesis in Rayyan and standardized critical appraisal tools. Selected as a URISE research fellow to present the work at the International Conference of Healthcare Challenges and Innovations in the 21st Century (HCIC), UMT. Currently under review for publication with advisor Dr. Rabia Altaf.</p>
        <div class="cta-row" style="margin:20px 0 0;">
          <a class="btn" style="border-color:var(--gold); color:var(--paper);" href="thesis.pdf" target="_blank" rel="noopener">View Thesis ↗</a>
          <a class="btn" style="border-color:var(--gold); color:var(--paper);" href="poster.pdf" target="_blank" rel="noopener">View Poster ↗</a>
        </div>
      </div>

      <div class="research-list">
        <div class="rcard">
          <p class="stage">Fall 2025 · URISE Fellowship</p>
          <h3>Virtual Autism Systematic Review</h3>
          <p>Designed and executed the review end-to-end: PICO question formulation, database search strategy, PRISMA-compliant screening, and quantitative evidence extraction across 300+ records.</p>
          <div class="method">
            <span class="tag">PRISMA</span><span class="tag">PICO</span><span class="tag">Rayyan</span><span class="tag">PubMed / Cochrane</span>
          </div>
        </div>
        <div class="rcard">
          <p class="stage">Summer 2023 · Research Assistant</p>
          <h3>Antibiotic Stewardship Awareness</h3>
          <p>Supported Dr. Amber Sharif's study on antibiotic stewardship awareness in Pakistan's community pharmacy settings, designing a community-based survey with attention to methodological and ethical rigor across retail pharmacies.</p>
          <div class="method">
            <span class="tag">Survey Design</span><span class="tag">Community Pharmacy</span><span class="tag">Research Ethics</span>
          </div>
        </div>
      </div>

      <div class="research-callout" style="margin-top:28px; margin-bottom:0; background:var(--card); color:var(--ink); border:1px solid var(--line);">
        <p class="eyebrow">Live Project</p>
        <h3 style="font-size:22px; margin-bottom:10px;">Salbutamol Drug Profile</h3>
        <p style="color:var(--ink-soft);">A web-deployed clinical reference covering mechanism of action, indications, adverse effects, drug interactions, and patient counseling guidelines for salbutamol. Ranked 2/86 on the underlying GitHub project.</p>
        <div class="cta-row" style="margin:18px 0 0;">
          <a class="btn btn-solid" href="https://zainabamin2026.github.io/salbutamol/" target="_blank" rel="noopener">View Live Project ↗</a>
        </div>
      </div>
    </div>
  </section>

  <!-- EXPERIENCE -->
  <section id="experience">
    <div class="wrap">
      <div class="section-head">
        <h2>Four internships. Four different views of the same health system.</h2>
        <p>Clinical, industrial, analytical, and strategic: each one reframed how I think about health delivery.</p>
      </div>
      <div class="timeline">
        <div class="trow reveal">
          <span class="when">Jul – Aug 2024</span>
          <h3>Pharmacy Intern</h3>
          <p class="org">Evercare Hospital, Lahore</p>
          <p>Verified 50–60 prescription reviews per shift under the 7R rule, evaluated 100+ patient EHRs via the hospital's HIMS, and joined interprofessional ADR-monitoring sessions with physicians. Delivered TB public-health education and ran medication adherence campaigns for 10+ tuberculosis patients.</p>
        </div>
        <div class="trow reveal">
          <span class="when">Aug – Sep 2025</span>
          <h3>Co-op Intern, Quality Assurance</h3>
          <p class="org">Citi Pharma Industry, Lahore</p>
          <p>Documented QA records across 8 concurrent production batches, validated analytical assays for regulatory submission, and ran spectroscopic analysis on 50 samples to screen for biosecurity threats and drug authenticity. Implemented GMP-aligned SOPs that cut deviations by 5%.</p>
        </div>
        <div class="trow reveal">
          <span class="when">Sep – Oct 2025</span>
          <h3>Data Visualization Remote Trainee</h3>
          <p class="org">Excelerate, Dubai, UAE</p>
          <p>Turned raw datasets into decision-ready dashboards using Excel, Tableau, and Power BI, working with a 12-person international team: the biostatistics-facing counterpart to the clinical fieldwork.</p>
        </div>
        <div class="trow reveal">
          <span class="when">Jul 2024 – Present</span>
          <h3>Creative Strategist</h3>
          <p class="org">Voho.AI, Berlin, Germany</p>
          <p>Embedded in an early-stage founding team building AI voice agents for healthcare, translating complex AI capability into plain language for non-technical stakeholders and running market research on growth opportunities.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- IMPACT -->
  <section id="impact">
    <div class="wrap">
      <div class="section-head">
        <h2>Public health, off the ward.</h2>
        <p>Community screening, disease-specific adherence work, and disaster response: the applied side of the research.</p>
      </div>
      <div class="impact-grid">
        <div class="icard">
          <span class="big"><span class="countup" data-target="100" data-suffix="+">0</span></span>
          <h4>BP &amp; Glucose Screening Camp</h4>
          <p>Poster presentation, Community Pharmacy Service Project Showcase. Screened 100+ rural individuals for hypertension and glucose abnormalities, flagging high-risk cases for early intervention and delivering patient counseling.</p>
        </div>
        <div class="icard">
          <span class="big"><span class="countup" data-target="10" data-suffix="+">0</span></span>
          <h4>TB Adherence Campaigns</h4>
          <p>Ran medication adherence campaigns for tuberculosis outpatients at Evercare Hospital alongside public health education on treatment completion.</p>
        </div>
        <div class="icard">
          <span class="big">50 hrs</span>
          <h4>Community Service, Alkhidmat</h4>
          <p>Flood-relief supply distribution across rural Pakistan, 10+ plantation drives, and medical camp support, 50 hours logged over 2.5 years.</p>
        </div>
      </div>

      <div class="camp-gallery" style="display:grid; grid-template-columns:1fr 1fr; gap:24px; margin-top:44px;">
        <figure style="margin:0;">
          <img src="images/medical-camp-1.png" alt="Zainab and a fellow student recording patient details during a community screening camp" style="width:100%; border:1px solid var(--line);">
          <figcaption class="mono" style="font-size:12px; color:var(--ink-soft); margin-top:10px; text-transform:uppercase; letter-spacing:0.04em;">Documenting patient intake, community screening camp</figcaption>
        </figure>
        <figure style="margin:0;">
          <img src="images/medical-camp-2.png" alt="Team taking blood pressure and vitals at a community medical camp" style="width:100%; border:1px solid var(--line);">
          <figcaption class="mono" style="font-size:12px; color:var(--ink-soft); margin-top:10px; text-transform:uppercase; letter-spacing:0.04em;">On-site vitals screening, rural medical camp</figcaption>
        </figure>
      </div>
    </div>
  </section>

  <!-- LEADERSHIP -->
  <section id="leadership">
    <div class="wrap">
      <div class="section-head">
        <h2>Organizing people, not just data.</h2>
        <p>Doctoral work is a team sport, and this is where I learned to run one.</p>
      </div>
      <div class="lead-grid">
        <div class="lcard">
          <p class="role">Founder &amp; Executive</p>
          <h3>Pharmacy Student Society</h3>
          <p class="org">Oct 2022 – Sep 2025</p>
          <p>Led a 20-person team through health awareness campaigns from planning to execution; recognized as the society's best general body.</p>
        </div>
        <div class="lcard">
          <p class="role">Logistics Director</p>
          <h3>HCIC Conference</h3>
          <p class="org">Aug 2024 – Feb 2025</p>
          <p>Ran venue, scheduling, and volunteer coordination for the largest healthcare international conference in Lahore.</p>
        </div>
        <div class="lcard">
          <p class="role">Campus Director</p>
          <h3>Hult Prize Foundation</h3>
          <p class="org">Aug 2024 – Dec 2024</p>
          <p>One of 20 students nationwide selected to lead the campus chapter, guiding students building social-impact startups for the $1M Hult Prize.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- PUBLICATIONS -->
  <section id="publications">
    <div class="wrap">
      <div class="section-head">
        <h2>Publications &amp; presentations.</h2>
        <p>Peer review, conference posters, and the conferences that shaped the thinking.</p>
      </div>

      <div class="pub">
        <p class="kind">Journal Article · In Review, 2026</p>
        <h3>Comparative Analysis of Cognitive and Language Impairments in Virtual Autism: A Comprehensive Systematic Review</h3>
        <p>Altaf, R., Mazhar, K., Amin, Z., Mir, A. A., Fatima, M., Imran, N., &amp; Mehar, M. H.</p>
      </div>
      <div class="pub">
        <p class="kind">Conference Presentation · Spring 2026</p>
        <h3>Virtual Autism Systematic Review, URISE, Lahore</h3>
        <p>PRISMA-guided evidence synthesis and structured critical appraisal, presented alongside an awareness campaign on virtual autism among adults.</p>
      </div>
      <div class="pub">
        <p class="kind">Poster · Fall 2024</p>
        <h3>Blood Pressure &amp; Glucose Screening Camp in Rural Areas, CPS Showcase, UMT</h3>
        <p>Community-based screening and preventive counseling for 100+ individuals in underserved areas.</p>
      </div>
      <div class="pub">
        <p class="kind">Poster · Spring 2022</p>
        <h3>Innovation in Pharmacy: The Role of Technology, Giving Back to Pharmacy in Pakistan</h3>
        <p>Digital health interventions and pharmacovigilance systems linked to 15–25% reductions in inappropriate prescribing and adverse drug events.</p>
      </div>

      <div class="marquee">
        <div class="marquee-track">
          <span>HCIC 2026</span><span>Pak Pharma &amp; Healthcare Expo 2026</span><span>ICPC 2025</span><span>HCIC 2025</span><span>IPCE, PPA 2024</span><span>GBTPP Conference 2022</span>
          <span aria-hidden="true">HCIC 2026</span><span aria-hidden="true">Pak Pharma &amp; Healthcare Expo 2026</span><span aria-hidden="true">ICPC 2025</span><span aria-hidden="true">HCIC 2025</span><span aria-hidden="true">IPCE, PPA 2024</span><span aria-hidden="true">GBTPP Conference 2022</span>
        </div>
      </div>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <div class="wrap">
      <div class="section-head">
        <h2>Toolkit.</h2>
        <p>What I'd bring into a doctoral program on day one.</p>
      </div>
      <div class="skills-grid">
        <div class="skillcol">
          <h4>Research Methods</h4>
          <ul>
            <li>PRISMA systematic review</li>
            <li>PICO framework</li>
            <li>Rayyan / critical appraisal</li>
            <li>Survey design</li>
            <li>Biostatistics</li>
          </ul>
        </div>
        <div class="skillcol">
          <h4>Data &amp; Informatics</h4>
          <ul>
            <li>R, SPSS</li>
            <li>Excel, Tableau, Power BI</li>
            <li>EHR / HIMS</li>
            <li>Epidemiology</li>
          </ul>
        </div>
        <div class="skillcol">
          <h4>Clinical Practice</h4>
          <ul>
            <li>Pharmacology &amp; therapeutics</li>
            <li>Patient counseling</li>
            <li>Drug interaction review</li>
            <li>Toxicology</li>
          </ul>
        </div>
        <div class="skillcol">
          <h4>Leadership</h4>
          <ul>
            <li>Team &amp; program management</li>
            <li>Scientific communication</li>
            <li>Cross-discipline collaboration</li>
            <li>Public health education</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- CERTIFICATIONS -->
  <section id="certifications">
    <div class="wrap">
      <div class="section-head">
        <h2>Certifications.</h2>
        <p>Formal coursework backing the research and data skills above.</p>
      </div>
      <div class="cert-grid">
        <div class="certcard">
          <p class="stage">Data &amp; Programming</p>
          <h3>Data Analysis with R Programming</h3>
          <p>Google</p>
          <a href="certs/data-analysis-r-google.pdf" target="_blank" rel="noopener">View Certificate ↗</a>
        </div>
        <div class="certcard">
          <p class="stage">Health Informatics</p>
          <h3>The Data Science of Health Informatics</h3>
          <p>Johns Hopkins University</p>
          <a href="certs/health-informatics-jhu.pdf" target="_blank" rel="noopener">View Certificate ↗</a>
        </div>
        <div class="certcard">
          <p class="stage">Clinical Research</p>
          <h3>Good Clinical Practice</h3>
          <p></p>
          <a href="certs/good-clinical-practice.pdf" target="_blank" rel="noopener">View Certificate ↗</a>
        </div>
        <div class="certcard">
          <p class="stage">Public Health</p>
          <h3>The National Institute on Drug Abuse (NIDA)</h3>
          <p>National Institutes of Health (NIH)</p>
          <a href="certs/nida-nih.pdf" target="_blank" rel="noopener">View Certificate ↗</a>
        </div>
        <div class="certcard">
          <p class="stage">Digital Health &amp; AI</p>
          <h3>AI in Healthcare</h3>
          <p>Stanford University</p>
          <a href="certs/ai-in-healthcare-stanford.pdf" target="_blank" rel="noopener">View Certificate ↗</a>
        </div>
        <div class="certcard">
          <p class="stage">Public Health</p>
          <h3>Foundations of Public Health Practice: The Public Health Approach</h3>
          <p>Imperial College London</p>
          <a href="certs/public-health-approach-imperial.pdf" target="_blank" rel="noopener">View Certificate ↗</a>
        </div>
      </div>
    </div>
  </section>

  <!-- HONORS -->
  <section id="honors">
    <div class="wrap">
      <div class="section-head">
        <h2>Honors &amp; awards.</h2>
        <p></p>
      </div>
      <ul class="honors">
        <li><span>Forensic Pharmaceutical Project Competition, 1st Place</span><span class="yr">2026</span></li>
        <li><span>Final Year Thesis Project, 2nd Place</span><span class="yr">2026</span></li>
        <li><span>OSCE Highest Scorer, Top 5%</span><span class="yr">2025</span></li>
        <li><span>Top 10, Co-op Summer Program</span><span class="yr">2025</span></li>
        <li><span>GitHub Drug Profile Project, Rank 2/86</span><span class="yr">2025</span></li>
        <li><span>Best General Secretary Award</span><span class="yr">2024</span></li>
        <li><span>Community Medical Camp, 3rd Place</span><span class="yr">2024</span></li>
        <li><span>Project Narco Check, 3rd Place</span><span class="yr">2023</span></li>
        <li><span>Best Oral Presentation Award</span><span class="yr">2022</span></li>
        <li><span>Outstanding Academic Performer, 3rd Place</span><span class="yr">2021</span></li>
      </ul>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="contact">
    <div class="wrap">
      <p class="eyebrow" style="color:var(--gold);">Let's talk</p>
      <h2>Looking for a doctoral program in public health where evidence turns into delivery.</h2>
      <p class="lede">Research supervisors, admissions committees, or anyone working on health services delivery in low-resource settings, I'd like to hear from you.</p>
      <div class="contact-links">
        <a class="clink" href="mailto:zainabamin.pharmd@gmail.com">✉ zainabamin.pharmd@gmail.com</a>
        <a class="clink" href="https://www.linkedin.com/in/zainab-amin-690407287/" target="_blank" rel="noopener">in LinkedIn</a>
        <a class="clink" href="https://github.com/" target="_blank" rel="noopener">&lt;/&gt; GitHub</a>
      </div>
    </div>
  </section>

</main>

<footer>© 2026 Zainab Amin, Pharm.D., Lahore, Pakistan</footer>

<script>
  // mobile nav
  const navBtn = document.getElementById('navBtn');
  const navLinks = document.getElementById('navLinks');
  navBtn.addEventListener('click', () => {
    const open = navLinks.classList.toggle('open');
    navBtn.setAttribute('aria-expanded', open);
  });
  navLinks.querySelectorAll('a').forEach(a => a.addEventListener('click', () => {
    navLinks.classList.remove('open');
    navBtn.setAttribute('aria-expanded', false);
  }));

  // scroll reveal
  const revealEls = document.querySelectorAll('.reveal');
  const io = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('in'); });
  }, { threshold: 0.15 });
  revealEls.forEach(el => io.observe(el));

  // fieldwork bar chart
  const barFills = document.querySelectorAll('.barfill');
  const barIo = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if(!entry.isIntersecting) return;
      entry.target.style.width = entry.target.dataset.width + '%';
      barIo.unobserve(entry.target);
    });
  }, { threshold: 0.4 });
  barFills.forEach(el => barIo.observe(el));

  // count-up numbers
  const countEls = document.querySelectorAll('.countup');
  const countIo = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if(!entry.isIntersecting) return;
      const el = entry.target;
      const target = parseInt(el.dataset.target, 10);
      const suffix = el.dataset.suffix || '';
      const dur = 900;
      const start = performance.now();
      function tick(now){
        const p = Math.min(1, (now - start) / dur);
        const val = Math.round(target * (1 - Math.pow(1 - p, 3)));
        el.textContent = val + suffix;
        if(p < 1) requestAnimationFrame(tick);
      }
      requestAnimationFrame(tick);
      countIo.unobserve(el);
    });
  }, { threshold: 0.6 });
  countEls.forEach(el => countIo.observe(el));
</script>

</body>
</html>
