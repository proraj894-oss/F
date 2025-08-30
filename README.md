<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Essentials -->
  <meta charset="utf-8" />
  <meta name="google-site-verification" content="jjs9qAzIG90qDMvYVQ7_bRJ3otQwU3P_jZHwovlIu7k" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />

  <!-- Title & SEO -->
  <title>Fin – SIP, GST & Loan EMI Calculators (Fast & Accurate)</title>
  <meta name="description" content="Fin is a free toolkit with SIP, GST, and Loan EMI calculators. Get instant results, amortization schedule, and clear breakdowns. Works on mobile and desktop." />
  <meta name="keywords" content="EMI calculator, SIP calculator, GST calculator, loan calculator, amortization, interest, finance tools, tax calculator" />
  <meta name="robots" content="index, follow, max-snippet:-1, max-image-preview:large, max-video-preview:-1" />

  <!-- Ownership / Monetization -->
  <meta name="google-adsense-account" content="ca-pub-8648198938608752" />
  <!-- Replace XXXXX with your real Search Console code -->
  <meta name="google-site-verification" content="XXXXX" />

  <!-- Canonical & Sitemap Hint -->
  <link rel="canonical" href="https://proraj894-oss.github.io/Fin/" />
  <link rel="sitemap" type="application/xml" title="Sitemap" href="https://proraj894-oss.github.io/Fin/sitemap.xml" />

  <!-- Open Graph -->
  <meta property="og:title" content="Fin – SIP, GST & Loan EMI Calculators" />
  <meta property="og:description" content="Free online calculators for SIP, GST, and Loan EMI. No sign-up, no data collection. Fast and accurate." />
  <meta property="og:url" content="https://proraj894-oss.github.io/Fin/" />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://proraj894-oss.github.io/Fin/preview.png" />

  <!-- Twitter Card -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Fin – SIP, GST & Loan EMI Calculators" />
  <meta name="twitter:description" content="Instant SIP, GST, and EMI calculations with amortization schedule." />
  <meta name="twitter:image" content="https://proraj894-oss.github.io/Fin/preview.png" />

  <!-- Theme color for mobile -->
  <meta name="theme-color" content="#0a66c2" />

  <!-- Favicon (SVG data URI) -->
  <link
    rel="icon"
    href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='64' height='64' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='14' fill='%230a66c2'/%3E%3Ctext x='50%25' y='58%25' font-size='38' text-anchor='middle' fill='white' font-family='Arial,Helvetica,sans-serif'%3E%E2%82%B9%3C/text%3E%3C/svg%3E"
  />

  <!-- Styles -->
  <style>
    :root{
      --bg:#0b1020;
      --card:#111735;
      --muted:#9aa3c7;
      --text:#eef2ff;
      --brand:#0a66c2;
      --accent:#4f7cff;
      --ok:#22c55e;
      --danger:#ef4444;
      --ring:rgba(79,124,255,.35);
      --radius:16px;
      --shadow:0 10px 30px rgba(0,0,0,.35);
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,"Apple Color Emoji","Segoe UI Emoji";
      color:var(--text);
      background: radial-gradient(1200px 800px at 70% -10%, #1a245a 0%, var(--bg) 40%);
    }
    a{color:#dbe8ff;text-decoration:none}
    a:hover{text-decoration:underline}

    header{
      position:sticky;top:0;z-index:10;
      backdrop-filter:blur(8px);
      background:linear-gradient(180deg, rgba(11,16,32,.9), rgba(11,16,32,.6));
      border-bottom:1px solid rgba(255,255,255,.08);
    }
    .wrap{max-width:1100px;margin:0 auto;padding:14px 16px}
    .row{display:flex;align-items:center;justify-content:space-between;gap:12px;flex-wrap:wrap}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:36px;height:36px;display:grid;place-items:center;
      border-radius:12px;background:linear-gradient(135deg,var(--brand),#8aa6ff);box-shadow:var(--shadow);font-weight:800
    }
    nav{display:flex;gap:10px;align-items:center;flex-wrap:wrap}
    .pill{display:inline-block;padding:6px 12px;border-radius:999px;background:#10173a;border:1px solid rgba(255,255,255,.12);color:#cbd5ff}
    .pill:hover{border-color:var(--accent)}

    main.wrap{padding:20px 16px}
    .grid{display:grid;gap:16px;grid-template-columns:1fr}
    @media(min-width:980px){.grid{grid-template-columns:1.12fr .88fr}}

    .card{
      background:linear-gradient(180deg, rgba(255,255,255,.03), rgba(255,255,255,.015));
      border:1px solid rgba(255,255,255,.1);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      padding:16px;
    }
    h1{margin:8px 0 6px;font-size:clamp(26px,3.2vw,38px)}
    .lead{color:var(--muted);margin:0 0 12px;line-height:1.6}

    label{display:block;font-size:14px;color:#c0c8ea;margin-bottom:6px}
    input,select,button{
      width:100%;border-radius:12px;
      border:1px solid rgba(255,255,255,.12);
      background:#0e1430;color:var(--text);
      padding:12px 14px;outline:none;
      transition:border .2s ease, box-shadow .2s ease;
    }
    input:focus,select:focus{
      border-color:var(--accent);
      box-shadow:0 0 0 4px var(--ring);
    }
    .inputs{display:grid;grid-template-columns:1fr;gap:12px}
    @media(min-width:680px){.inputs{grid-template-columns:1fr 1fr}}
    .btn{
      display:inline-flex;align-items:center;justify-content:center;gap:10px;
      background:linear-gradient(180deg,var(--accent),#2d57ff);border:0;
      color:white;font-weight:700;cursor:pointer;
    }
    .btn.secondary{background:linear-gradient(180deg, rgba(255,255,255,.07), rgba(255,255,255,.03));border:1px solid rgba(255,255,255,.14);color:#e5ebff}
    .btn:disabled{opacity:.6;cursor:not-allowed}

    .kpi{display:grid;grid-template-columns:1fr;gap:12px;margin-top:12px}
    @media(min-width:560px){.kpi{grid-template-columns:repeat(3,1fr)}}
    .tile{background:#0e1430;border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:14px}
    .tile small{display:block;color:#aab3da;margin-bottom:6px}
    .tile strong{font-size:20px}

    .table-wrap{overflow:auto;max-height:360px;border-radius:12px;border:1px solid rgba(255,255,255,.08)}
    table{width:100%;border-collapse:collapse;font-size:14px}
    th,td{padding:10px;border-bottom:1px solid rgba(255,255,255,.08);text-align:right}
    th:first-child,td:first-child{text-align:left}
    tbody tr:hover{background:rgba(255,255,255,.03)}

    .note{color:var(--muted);font-size:14px}
    .ad-slot{border:2px dashed rgba(255,255,255,.18);border-radius:14px;padding:16px;text-align:center;color:var(--muted)}

    footer{color:#aeb6db;text-align:center;padding:28px 16px 60px}

    /* Utility */
    .mt-12{margin-top:12px}.mt-16{margin-top:16px}.mt-18{margin-top:18px}.mt-24{margin-top:24px}
    .flex{display:flex}.gap-10{gap:10px}.wrap-controls{flex-wrap:wrap}
    .right{justify-content:flex-end}
  </style>

  <!-- FAQ Schema (JSON-LD) -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"FAQPage",
    "mainEntity":[
      {"@type":"Question","name":"What is EMI?","acceptedAnswer":{"@type":"Answer","text":"EMI (Equated Monthly Installment) is the fixed amount paid every month until a loan is repaid."}},
      {"@type":"Question","name":"How is EMI calculated?","acceptedAnswer":{"@type":"Answer","text":"EMI = P × r × (1 + r)^n / ((1 + r)^n − 1), where P is principal, r is monthly interest rate, and n is number of months."}},
      {"@type":"Question","name":"Do you store my data?","acceptedAnswer":{"@type":"Answer","text":"No. All calculations run locally in your browser; nothing is uploaded."}}
    ]
  }
  </script>
</head>
<body>
  <header>
    <div class="wrap row">
      <div class="brand">
        <div class="logo">₹</div>
        <div>
          <strong>Fin Calculators</strong><br />
          <span class="note">SIP • GST • Loan EMI</span>
        </div>
      </div>
      <nav>
        <a class="pill" href="#emi">EMI</a>
        <a class="pill" href="#sip">SIP</a>
        <a class="pill" href="#gst">GST</a>
        <a class="pill" href="#faq">FAQ</a>
      </nav>
    </div>
  </header>

  <main class="wrap">
    <div class="grid">
      <!-- Left: Calculators -->
      <section class="card" id="emi">
        <h1>Loan EMI Calculator</h1>
        <p class="lead">Calculate your monthly EMI, total interest, and total payment. See the amortization for the first 12 months.</p>

        <div class="inputs mt-12">
          <div>
            <label>Loan Amount (₹)</label>
            <input id="emiAmount" type="number" min="0" step="1000" placeholder="e.g., 500000" />
          </div>
          <div>
            <label>Annual Interest Rate (%)</label>
            <input id="emiRate" type="number" min="0" step="0.01" placeholder="e.g., 10.5" />
          </div>
          <div>
            <label>Tenure</label>
            <input id="emiTenure" type="number" min="1" step="1" placeholder="e.g., 60" />
          </div>
          <div>
            <label>Tenure Unit</label>
            <select id="emiUnit">
              <option value="months">Months</option>
              <option value="years">Years</option>
            </select>
          </div>
        </div>

        <div class="flex gap-10 wrap-controls mt-16">
          <button class="btn" id="emiCalcBtn">Calculate EMI</button>
          <button class="btn secondary" id="emiShareBtn">Share</button>
          <button class="btn secondary" id="emiCopyBtn">Copy</button>
        </div>

        <div class="kpi mt-16">
          <div class="tile"><small>Monthly EMI</small><strong id="emiOut">—</strong></div>
          <div class="tile"><small>Total Interest</small><strong id="emiInterest">—</strong></div>
          <div class="tile"><small>Total Payment</small><strong id="emiTotal">—</strong></div>
        </div>

        <h3 class="mt-18">Amortization (first 12 months)</h3>
        <div class="table-wrap mt-12">
          <table>
            <thead>
              <tr>
                <th>Month</th>
                <th>EMI (₹)</th>
                <th>Interest (₹)</th>
                <th>Principal (₹)</th>
                <th>Balance (₹)</th>
              </tr>
            </thead>
            <tbody id="emiTable"></tbody>
          </table>
        </div>

        <div class="ad-slot mt-16">
          Ad space — paste Google AdSense unit code here after approval.
        </div>
      </section>

      <!-- Right: Side card with SIP/GST quick tools -->
      <aside class="card">
        <section id="sip">
          <h2>SIP Calculator</h2>
          <p class="note">Estimate maturity for monthly investments.</p>
          <div class="inputs mt-12">
            <div>
              <label>Monthly Investment (₹)</label>
              <input id="sipAmt" type="number" min="0" step="100" placeholder="e.g., 5000" />
            </div>
            <div>
              <label>Period (years)</label>
              <input id="sipYears" type="number" min="1" step="1" placeholder="e.g., 10" />
            </div>
            <div>
              <label>Expected Return p.a. (%)</label>
              <input id="sipRate" type="number" min="0" step="0.1" placeholder="e.g., 12" />
            </div>
          </div>
          <div class="flex right gap-10 wrap-controls mt-12">
            <button class="btn" id="sipCalcBtn">Calculate</button>
          </div>
          <div class="kpi mt-12">
            <div class="tile"><small>Maturity Value</small><strong id="sipOut">—</strong></div>
            <div class="tile"><small>Total Invested</small><strong id="sipInvested">—</strong></div>
            <div class="tile"><small>Total Gain</small><strong id="sipGain">—</strong></div>
          </div>
        </section>

        <hr style="border:none;border-top:1px solid rgba(255,255,255,.12);margin:18px 0" />

        <section id="gst">
          <h2>GST Calculator</h2>
          <p class="note">Compute GST amount and total price.</p>
          <div class="inputs mt-12">
            <div>
              <label>Amount (₹)</label>
              <input id="gstAmt" type="number" min="0" step="1" placeholder="e.g., 1000" />
            </div>
            <div>
              <label>GST Rate (%)</label>
              <input id="gstRate" type="number" min="0" step="0.1" placeholder="e.g., 18" />
            </div>
          </div>
          <div class="flex right gap-10 wrap-controls mt-12">
            <button class="btn" id="gstCalcBtn">Calculate</button>
          </div>
          <div class="kpi mt-12">
            <div class="tile"><small>GST</small><strong id="gstOnly">—</strong></div>
            <div class="tile"><small>Total (incl. GST)</small><strong id="gstTotal">—</strong></div>
            <div class="tile"><small>Net Amount</small><strong id="gstNet">—</strong></div>
          </div>

          <div class="ad-slot mt-16">
            Tip: Place affiliate or AdSense unit here too.
          </div>
        </section>
      </aside>
    </div>

    <!-- FAQ & Contact -->
    <section class="card mt-18" id="faq">
      <h2>FAQ</h2>
      <details>
        <summary>What is EMI?</summary>
        <p class="note">EMI is the fixed monthly amount you pay towards your loan until full repayment.</p>
      </details>
      <details>
        <summary>How accurate are these calculations?</summary>
        <p class="note">Formulas are standard finance math. Actual bank terms may vary due to fees, rounding, and rate changes.</p>
      </details>
      <details>
        <summary>Do you store my inputs?</summary>
        <p class="note">No. Everything runs locally in your browser.</p>
      </details>
    </section>

    <section class="card mt-18" id="contact">
      <h2>Contact</h2>
      <p class="note">Feedback or partnerships: <a href="mailto:you@example.com">you@example.com</a></p>
    </section>
  </main>

  <footer>
    <div>© <span id="year"></span> Fin Calculators. All rights reserved.</div>
    <div class="mt-12 note">Made for quick, private, and accurate calculations.</div>
  </footer>

  <!-- AdSense loader (ads show after approval) -->
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-8648198938608752" crossorigin="anonymous"></script>

  <!-- App Logic -->
  <script>
    // Helpers
    const fmt = (n) => (isFinite(n) ? Number(n).toLocaleString("en-IN", { maximumFractionDigits: 2 }) : "—");

    // --- EMI ---
    function calcEMI() {
      const P = parseFloat(document.getElementById("emiAmount").value);
      const annual = parseFloat(document.getElementById("emiRate").value);
      let n = parseInt(document.getElementById("emiTenure").value, 10);
      const unit = document.getElementById("emiUnit").value;
      if (unit === "years") n = n * 12;

      if (!P || !annual || !n) {
        document.getElementById("emiOut").textContent = "—";
        document.getElementById("emiInterest").textContent = "—";
        document.getElementById("emiTotal").textContent = "—";
        document.getElementById("emiTable").innerHTML = "";
        return;
      }

      const r = annual / 12 / 100;
      const pow = Math.pow(1 + r, n);
      const EMI = (P * r * pow) / (pow - 1);
      const total = EMI * n;
      const interest = total - P;

      document.getElementById("emiOut").textContent = `₹ ${fmt(EMI)}`;
      document.getElementById("emiInterest").textContent = `₹ ${fmt(interest)}`;
      document.getElementById("emiTotal").textContent = `₹ ${fmt(total)}`;

      // Table (first 12 months)
      const tb = document.getElementById("emiTable");
      tb.innerHTML = "";
      let balance = P;
      for (let i = 1; i <= Math.min(12, n); i++) {
        const interestComp = balance * r;
        const principalComp = EMI - interestComp;
        balance = Math.max(0, balance - principalComp);
        const tr = document.createElement("tr");
        tr.innerHTML = `
          <td>${i}</td>
          <td>₹ ${fmt(EMI)}</td>
          <td>₹ ${fmt(interestComp)}</td>
          <td>₹ ${fmt(principalComp)}</td>
          <td>₹ ${fmt(balance)}</td>
        `;
        tb.appendChild(tr);
      }

      // Shareable URL
      const params = new URLSearchParams({ amount: P, rate: annual, tenure: n });
      history.replaceState(null, "", `${location.pathname}?${params.toString()}`);
    }

    // --- SIP ---
    function calcSIP() {
      const A = parseFloat(document.getElementById("sipAmt").value);
      const Y = parseFloat(document.getElementById("sipYears").value);
      const R = parseFloat(document.getElementById("sipRate").value);
      if (!A || !Y || !R) {
        document.getElementById("sipOut").textContent = "—";
        document.getElementById("sipInvested").textContent = "—";
        document.getElementById("sipGain").textContent = "—";
        return;
      }
      const r = R / 100 / 12;
      const n = Y * 12;
      const maturity = A * ((Math.pow(1 + r, n) - 1) / r) * (1 + r);
      const invested = A * n;
      const gain = maturity - invested;

      document.getElementById("sipOut").textContent = `₹ ${fmt(maturity)}`;
      document.getElementById("sipInvested").textContent = `₹ ${fmt(invested)}`;
      document.getElementById("sipGain").textContent = `₹ ${fmt(gain)}`;
    }

    // --- GST ---
    function calcGST() {
      const amt = parseFloat(document.getElementById("gstAmt").value);
      const rate = parseFloat(document.getElementById("gstRate").value);
      if (!amt || !rate) {
        document.getElementById("gstOnly").textContent = "—";
        document.getElementById("gstTotal").textContent = "—";
        document.getElementById("gstNet").textContent = "—";
        return;
      }
      const gst = amt * (rate / 100);
      const total = amt + gst;

      document.getElementById("gstOnly").textContent = `₹ ${fmt(gst)}`;
      document.getElementById("gstTotal").textContent = `₹ ${fmt(total)}`;
      document.getElementById("gstNet").textContent = `₹ ${fmt(amt)}`;
    }

    // Buttons
    document.getElementById("emiCalcBtn").addEventListener("click", calcEMI);
    document.getElementById("sipCalcBtn").addEventListener("click", calcSIP);
    document.getElementById("gstCalcBtn").addEventListener("click", calcGST);

    // Copy / Share
    document.getElementById("emiCopyBtn").addEventListener("click", async () => {
      const e = document.getElementById("emiOut").textContent;
      const i = document.getElementById("emiInterest").textContent;
      const t = document.getElementById("emiTotal").textContent;
      const text = `EMI Result\n${e}\nTotal Interest: ${i}\nTotal Payment: ${t}`;
      try { await navigator.clipboard.writeText(text); alert("Copied to clipboard!"); } catch { alert("Copy failed."); }
    });
    document.getElementById("emiShareBtn").addEventListener("click", async () => {
      const url = location.href;
      const title = "EMI Calculator Result";
      const text = "Check out this EMI calculation.";
      if (navigator.share) {
        try { await navigator.share({ title, text, url }); } catch {}
      } else {
        try { await navigator.clipboard.writeText(url); alert("Link copied!"); } catch { alert(url); }
      }
    });

    // Prefill from URL for EMI
    function prefillEMI() {
      const q = new URLSearchParams(location.search);
      const A = q.get("amount"), R = q.get("rate"), N = q.get("tenure");
      if (A) document.getElementById("emiAmount").value = A;
      if (R) document.getElementById("emiRate").value = R;
      if (N) {
        document.getElementById("emiTenure").value = N;
        document.getElementById("emiUnit").value = "months";
      }
      if (A && R && N) calcEMI();
    }

    // Footer year + init
    document.getElementById("year").textContent = new Date().getFullYear();
    prefillEMI();
  </script>
</body>
</html>
