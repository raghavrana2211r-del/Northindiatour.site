# Northindiatour.site
Official website of north India tours and travels 
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Rana Tours & Travels | Chandigarh Taxi Service</title>
  <meta name="description" content="Rana Tours & Travels - Chandigarh taxi and tour services. Innova Crysta, Ertiga, Rumion and Dzire available for local and outstation trips." />
  <meta name="theme-color" content="#172554" />

  <!-- Open Graph / Social -->
  <meta property="og:title" content="Rana Tours & Travels | Chandigarh Taxi Service" />
  <meta property="og:description" content="Reliable Taxi & Tour Services from Chandigarh — Comfortable Cars • Affordable Rates • Outstation Trips" />
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="Rana Tours & Travels" />
  <!-- Replace with your site's canonical URL -->
  <meta property="og:url" content="https://example.com/" />
  <!-- Replace with a real image URL for social previews -->
  <meta property="og:image" content="https://example.com/preview.jpg" />

  <!-- Twitter card -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Rana Tours & Travels | Chandigarh Taxi Service" />
  <meta name="twitter:description" content="Reliable Taxi & Tour Services from Chandigarh — Comfortable Cars • Affordable Rates • Outstation Trips" />
  <meta name="twitter:image" content="https://example.com/preview.jpg" />

  <!-- JSON-LD LocalBusiness schema -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "LocalBusiness",
    "name": "Rana Tours & Travels",
    "telephone": "+917973111509",
    "description": "Taxi and tour services from Chandigarh — Innova, Ertiga, Rumion, Dzire and Tempo Traveller for local and outstation trips.",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Chandigarh",
      "addressRegion": "CH",
      "addressCountry": "IN"
    },
    "url": "https://example.com/",
    "areaServed": ["Chandigarh","Punjab","Himachal Pradesh","Uttarakhand"]
  }
  </script>

  <link rel="icon" href="/favicon.ico" />

  <style>
    :root{
      --bg:#f5f7fa;
      --text:#111827;
      --accent:#1e40af;
      --cta:#fbbf24;
      --success:#16a34a;
    }

    *{box-sizing:border-box;margin:0;padding:0;font-family:Arial,system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',sans-serif;scroll-behavior:smooth}
    html,body{height:100%;background:var(--bg);color:var(--text);line-height:1.6}

    header{
      background:#111827;color:#fff;padding:12px 5%;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:1000;
    }
    .logo{font-size:20px;font-weight:700;display:flex;align-items:center;gap:8px}
    nav{display:flex;gap:12px;align-items:center}
    nav a{color:inherit;text-decoration:none;margin-left:10px;font-weight:700}
    nav a:hover{color:#fbbf24}
    .nav-toggle{display:none;background:transparent;border:1px solid rgba(255,255,255,0.08);color:#fff;padding:8px;border-radius:8px}
    .nav-toggle:focus{outline:3px solid rgba(251,191,36,0.25)}

    .hero{min-height:72vh;display:flex;align-items:center;justify-content:center;text-align:center;padding:48px 20px;background:linear-gradient(135deg,#172554,#1e40af);color:#fff}
    .hero h1{font-size:44px;margin-bottom:12px}
    .hero p{font-size:18px;margin-bottom:18px}
    .btn{display:inline-block;padding:12px 20px;border-radius:10px;text-decoration:none;font-weight:800;margin:6px;background:var(--cta);color:#111827}
    .btn.whatsapp{background:#22c55e;color:#fff}
    .btn:focus{outline:3px solid rgba(25, 103, 210, 0.25);outline-offset:2px}

    section{padding:60px 7%}
    .section-title{text-align:center;font-size:30px;margin-bottom:28px;color:var(--accent)}

    .about{max-width:900px;margin:0 auto;font-size:18px;text-align:center}
    .fleet{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:22px}
    .car{background:#fff;padding:20px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.06);text-align:center}
    .car h3{font-size:20px;margin-bottom:8px}
    .price{font-size:20px;font-weight:700;color:var(--accent);margin:12px 0}

    .services{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px}
    .service{background:#fff;padding:18px;border-radius:10px;box-shadow:0 4px 14px rgba(0,0,0,0.06);text-align:center}

    .routes{display:flex;flex-wrap:wrap;justify-content:center;gap:10px}
    .route{background:#fff;padding:10px 16px;border-radius:20px;box-shadow:0 3px 10px rgba(0,0,0,0.06);font-weight:700}

    form{max-width:700px;margin:0 auto;background:#fff;padding:26px;border-radius:12px;box-shadow:0 6px 20px rgba(0,0,0,0.06)}
    label{display:block;font-weight:700;margin-bottom:6px}
    input,textarea,select{width:100%;padding:12px;margin-bottom:14px;border:1px solid #ddd;border-radius:8px;font-size:15px}
    textarea{min-height:110px}
    button[type="submit"]{border:none;cursor:pointer;width:100%;padding:14px;background:var(--success);color:#fff;border-radius:8px;font-size:16px;font-weight:800}
    .contact{padding:60px 7%;text-align:center;background:#111827;color:#fff}
    footer{text-align:center;background:#030712;color:#fff;padding:18px}

    .sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0,0,0,0);white-space:nowrap;border:0}

    /* Focus states */
    a:focus, button:focus, input:focus, select:focus, textarea:focus{outline:3px solid rgba(30,64,175,0.14);outline-offset:2px}

    /* Mobile nav */
    @media(max-width:760px){
      header{flex-direction:row;gap:6px}
      nav{position:absolute;left:0;right:0;top:60px;background:#0b1220;flex-direction:column;padding:12px 5%;display:none}
      nav a{margin:8px 0}
      .nav-toggle{display:inline-block}
      nav.open{display:flex}
      .hero h1{font-size:32px}
      .hero p{font-size:16px}
    }
  </style>
</head>
<body>

<header>
  <div class="logo" aria-label="Rana Tours & Travels logo">🚖 <strong>Rana Tours & Travels</strong></div>

  <button class="nav-toggle" id="navToggle" aria-controls="mainNav" aria-expanded="false" aria-label="Toggle navigation">☰ Menu</button>

  <nav id="mainNav" role="navigation" aria-label="Main navigation">
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#fleet">Fleet</a>
    <a href="#services">Services</a>
    <a href="#routes">Routes</a>
    <a href="#booking">Booking</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>

  <!-- HOME -->
  <section class="hero" id="home" role="region" aria-label="Home">
    <div>
      <h1>Rana Tours & Travels</h1>
      <p>Reliable Taxi & Tour Services from Chandigarh</p>
      <p>Comfortable Cars • Affordable Rates • Outstation Trips</p>

      <a class="btn" href="#booking">Book Now</a>

      <a class="btn whatsapp"
         href="https://wa.me/917973111509?text=Hello%20Rana%20Tours%20%26%20Travels%2C%20I%20want%20to%20book%20a%20taxi."
         target="_blank" rel="noopener noreferrer">
         WhatsApp
      </a>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" role="region" aria-label="About">
    <h2 class="section-title">About Us</h2>
    <div class="about">
      <p>
        Welcome to <strong>Rana Tours & Travels</strong>. We provide comfortable and reliable taxi services from Chandigarh for local and outstation journeys.
      </p>

      <p style="margin-top:14px">
        Our fleet includes comfortable cars for family trips, airport transfers, sightseeing and long-distance tours.
      </p>

      <p style="margin-top:14px">📍 Based in Chandigarh</p>
    </div>
  </section>

  <!-- FLEET -->
  <section id="fleet" role="region" aria-label="Fleet and rates">
    <h2 class="section-title">Our Fleet & Rates</h2>

    <div class="fleet">

      <div class="car" aria-labelledby="crystaTitle">
        <h3 id="crystaTitle">🚘 Toyota Innova Crysta</h3>
        <p>Comfortable premium car for family and outstation trips.</p>
        <div class="price">₹20 / KM</div>
        <p>Day Package: ₹5,500</p>
        <a class="btn whatsapp" href="https://wa.me/917973111509?text=I%20want%20to%20book%20Innova%20Crysta." target="_blank" rel="noopener noreferrer">Book</a>
      </div>

      <div class="car" aria-labelledby="ertigaTitle">
        <h3 id="ertigaTitle">🚐 Maruti Suzuki Ertiga</h3>
        <p>Spacious and comfortable family taxi.</p>
        <div class="price">₹18 / KM</div>
        <p>Day Package: ₹4,500</p>
        <a class="btn whatsapp" href="https://wa.me/917973111509?text=I%20want%20to%20book%20Ertiga." target="_blank" rel="noopener noreferrer">Book</a>
      </div>

      <div class="car" aria-labelledby="rumionTitle">
        <h3 id="rumionTitle">🚐 Toyota Rumion</h3>
        <p>Comfortable MPV for family and group travel.</p>
        <div class="price">₹18 / KM</div>
        <p>Day Package: ₹4,500</p>
        <a class="btn whatsapp" href="https://wa.me/917973111509?text=I%20want%20to%20book%20Toyota%20Rumion." target="_blank" rel="noopener noreferrer">Book</a>
      </div>

      <div class="car" aria-labelledby="dzireTitle">
        <h3 id="dzireTitle">🚗 Maruti Suzuki Dzire</h3>
        <p>Economical and comfortable taxi for small groups.</p>
        <div class="price">₹16 / KM</div>
        <p>Day Package: ₹4,000</p>
        <a class="btn whatsapp" href="https://wa.me/917973111509?text=I%20want%20to%20book%20Dzire." target="_blank" rel="noopener noreferrer">Book</a>
      </div>

      <div class="car" aria-labelledby="tempoTitle">
        <h3 id="tempoTitle">🚌 Tempo Traveller</h3>
        <p>Perfect for large groups and family tours.</p>
        <div class="price">Contact for Price</div>
        <a class="btn whatsapp" href="https://wa.me/917973111509?text=I%20want%20to%20book%20Tempo%20Traveller." target="_blank" rel="noopener noreferrer">Enquire</a>
      </div>

    </div>
  </section>

  <!-- SERVICES -->
  <section id="services" role="region" aria-label="Services">
    <h2 class="section-title">Our Services</h2>
    <div class="services">
      <div class="service"><h3>🚕 Local Taxi</h3><p>Taxi services around Chandigarh.</p></div>
      <div class="service"><h3>✈️ Airport Transfer</h3><p>Airport pickup and drop services.</p></div>
      <div class="service"><h3>🏔️ Hill Station Tours</h3><p>Comfortable trips to Himachal Pradesh.</p></div>
      <div class="service"><h3>🛣️ Outstation Taxi</h3><p>Long-distance taxi services.</p></div>
      <div class="service"><h3>👨‍👩‍👧‍👦 Family Tours</h3><p>Comfortable vehicles for family trips.</p></div>
      <div class="service"><h3>🏢 Corporate Travel</h3><p>Taxi services for business travel.</p></div>
    </div>
  </section>

  <!-- ROUTES -->
  <section id="routes" role="region" aria-label="Popular routes">
    <h2 class="section-title">Popular Routes</h2>
    <div class="routes" role="list">
      <div class="route" role="listitem">Chandigarh → Delhi</div>
      <div class="route" role="listitem">Chandigarh → Shimla</div>
      <div class="route" role="listitem">Chandigarh → Manali</div>
      <div class="route" role="listitem">Chandigarh → Amritsar</div>
      <div class="route" role="listitem">Chandigarh → Dharamshala</div>
      <div class="route" role="listitem">Chandigarh → Dalhousie</div>
      <div class="route" role="listitem">Chandigarh → Jammu</div>
      <div class="route" role="listitem">Chandigarh → Katra</div>
      <div class="route" role="listitem">Chandigarh → Haridwar</div>
      <div class="route" role="listitem">Chandigarh → Rishikesh</div>
    </div>
  </section>

  <!-- BOOKING -->
  <section id="booking" role="region" aria-label="Booking">
    <h2 class="section-title">Book Your Taxi</h2>

    <form id="bookingForm" onsubmit="sendBooking(event)" novalidate>
      <div id="formStatus" aria-live="polite" style="margin-bottom:14px;min-height:20px"></div>

      <label for="name">Your Name</label>
      <input id="name" name="name" type="text" placeholder="Enter your name" required autocomplete="name" aria-required="true" />

      <label for="phone">Mobile Number</label>
      <input id="phone" name="phone" type="tel" placeholder="Enter mobile number" required aria-required="true" pattern="^[6-9]\d{9}$" title="Enter a valid 10-digit Indian mobile number, starting with 6-9" autocomplete="tel" />

      <label for="vehicle">Vehicle</label>
      <select id="vehicle" name="vehicle" required aria-required="true">
        <option value="">Select Vehicle</option>
        <option>Innova Crysta</option>
        <option>Maruti Ertiga</option>
        <option>Toyota Rumion</option>
        <option>Maruti Dzire</option>
        <option>Tempo Traveller</option>
      </select>

      <label for="pickup">Pickup Location</label>
      <input id="pickup" name="pickup" type="text" placeholder="Pickup location" required autocomplete="street-address" />

      <label for="destination">Destination</label>
      <input id="destination" name="destination" type="text" placeholder="Destination" required autocomplete="address-level2" />

      <label for="date">Travel Date</label>
      <input id="date" name="date" type="date" required />

      <label for="message">Message</label>
      <textarea id="message" name="message" placeholder="Tell us about your trip"></textarea>

      <button type="submit" id="sendBtn">Send Booking on WhatsApp</button>

      <p style="font-size:13px;margin-top:10px;color:#555">By clicking, your details will be sent to WhatsApp for quick booking confirmation.</p>
    </form>

    <noscript style="display:block;margin-top:12px;text-align:center">
      <strong>JavaScript is disabled.</strong>
      <p>Please call us at <a href="tel:+917973111509">+91 79731 11509</a> or message on <a href="https://wa.me/917973111509" target="_blank" rel="noopener noreferrer">WhatsApp</a>.</p>
    </noscript>
  </section>

  <!-- CONTACT -->
  <section class="contact" id="contact" role="region" aria-label="Contact">
    <h2 class="section-title">Contact Us</h2>
    <p>📍 Chandigarh, India</p>
    <p style="margin-top:10px">Call us for taxi booking and tour enquiries.</p>

    <a class="btn" href="tel:+917973111509">📞 Call Now</a>

    <a class="btn whatsapp" href="https://wa.me/917973111509" target="_blank" rel="noopener noreferrer">💬 WhatsApp</a>
  </section>

</main>

<footer>
  <p>© 2026 Rana Tours & Travels. All Rights Reserved.</p>
  <p>Chandigarh Taxi & Tour Services</p>
</footer>

<script>
  // Configuration - phone in international format for wa.me (no plus, no spaces)
  const WHATSAPP_NUMBER = "917973111509";

  // Toggle mobile nav
  (function(){
    const btn = document.getElementById('navToggle');
    const nav = document.getElementById('mainNav');
    btn.addEventListener('click', function(){
      const open = nav.classList.toggle('open');
      btn.setAttribute('aria-expanded', open ? 'true' : 'false');
    });
  })();

  // Booking form behavior
  function showStatus(message, isError) {
    const status = document.getElementById('formStatus');
    status.textContent = message;
    status.style.color = isError ? '#b91c1c' : '#065f46'; // red or green
  }

  function validatePhone(phone) {
    // Indian 10-digit phone starting with 6-9
    return /^[6-9]\d{9}$/.test(phone.replace(/\s+/g,''));
  }

  function sendBooking(event) {
    event.preventDefault();

    const name = document.getElementById("name").value.trim();
    const phone = document.getElementById("phone").value.replace(/\s+/g,'').trim();
    const vehicle = document.getElementById("vehicle").value;
    const pickup = document.getElementById("pickup").value.trim();
    const destination = document.getElementById("destination").value.trim();
    const date = document.getElementById("date").value;
    const message = document.getElementById("message").value.trim();

    // Basic client-side validation
    if (!name || !phone || !vehicle || !pickup || !destination || !date) {
      showStatus("Please fill all required fields.", true);
      return;
    }

    if (!validatePhone(phone)) {
      showStatus("Please enter a valid 10-digit Indian mobile number (starts with 6-9).", true);
      return;
    }

    const text =
`🚕 *New Taxi Booking*

Name: ${name}
Phone: ${phone}
Vehicle: ${vehicle}
Pickup: ${pickup}
Destination: ${destination}
Date: ${date}
Message: ${message || '-'}
`;

    const url = "https://wa.me/" + WHATSAPP_NUMBER + "?text=" + encodeURIComponent(text);

    // Open WhatsApp in a new tab/window
    window.open(url, "_blank", "noopener");

    // UI feedback
    showStatus("Opening WhatsApp to send your booking — please confirm the message in WhatsApp.", false);
    const sendBtn = document.getElementById('sendBtn');
    sendBtn.disabled = true;
    sendBtn.textContent = "Opening WhatsApp...";

    // Re-enable after a short delay in case user returns
    setTimeout(function(){
      sendBtn.disabled = false;
      sendBtn.textContent = "Send Booking on WhatsApp";
    }, 5000);
  }
</script>

</body>
</html>
