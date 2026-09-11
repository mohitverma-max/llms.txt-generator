<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LLMs.txt Generator</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:'Inter',sans-serif;background:linear-gradient(160deg,#DEE7F7 0%,#EEF2FB 55%,#FFFFFF 100%);color:#0F172A;padding:28px 80px}
.wrapper{max-width:1320px;margin:auto}

.navbar{background:#fff;border-radius:20px;padding:16px 28px;display:flex;align-items:center;justify-content:space-between;margin-bottom:36px;box-shadow:0 8px 24px rgba(37,99,235,.06)}
.navbar .logo{display:flex;align-items:center;gap:8px;font-weight:800;font-size:15px;color:#0F172A;white-space:nowrap}
.navbar .logo .badge{background:#0F2A4A;color:#fff;padding:5px 10px;border-radius:8px;font-size:10.5px;font-weight:800;letter-spacing:.04em}
.navbar nav{display:flex;gap:26px;font-size:14px;font-weight:600;color:#334155}
.navbar .enroll{background:#F4C542;color:#111;padding:10px 20px;border-radius:10px;font-weight:800;font-size:13px;border:none;cursor:pointer;font-family:inherit}

.hero{text-align:center;margin-bottom:36px}
.eyebrow{display:inline-flex;align-items:center;gap:6px;color:#2563EB;font-weight:800;font-size:12px;letter-spacing:.08em;text-transform:uppercase;margin-bottom:20px}
.hero-icon{width:66px;height:66px;border-radius:18px;background:linear-gradient(135deg,#16305A,#0B5A8A);display:flex;align-items:center;justify-content:center;margin:0 auto 22px;font-size:30px;box-shadow:0 12px 26px rgba(15,42,74,.28)}
.hero h1{font-size:48px;font-weight:800;letter-spacing:-.01em;margin-bottom:14px}
.hero h1 .grad{background:linear-gradient(90deg,#2563EB,#0EA5A5);-webkit-background-clip:text;background-clip:text;color:transparent}
.hero p{color:#64748B;font-size:16px;max-width:560px;margin:0 auto}

.grid{display:grid;grid-template-columns:47% 53%;gap:22px}
.card{background:rgba(255,255,255,.86);backdrop-filter:blur(18px);border-radius:22px;padding:26px 28px;border:1px solid rgba(255,255,255,.7);box-shadow:0 12px 30px rgba(37,99,235,.08)}
h2{font-size:24px;margin-bottom:6px}
.sub{color:#64748B;font-size:13.5px;margin-bottom:20px}

.field{margin-bottom:18px}
label{display:block;font-size:11.5px;font-weight:700;color:#475569;margin-bottom:8px;text-transform:uppercase;letter-spacing:.03em}
input[type=text]{width:100%;padding:13px 14px;border:1px solid #D8E4FF;border-radius:12px;background:#fff;font-size:14px;font-family:inherit;color:#0F172A}
input[type=text]:focus{outline:none;border-color:#2563EB}
.field.invalid input{border-color:#DC2626}
.error{display:none;color:#DC2626;font-size:12px;margin-top:6px;font-weight:600}
.field.invalid .error{display:block}

.section-title{font-size:15.5px;font-weight:800;margin:6px 0 5px}
.desc{font-size:12.5px;color:#64748B;margin-bottom:14px}
.options{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:20px}
.option{display:flex;gap:8px;align-items:flex-start;padding:12px;border:1px solid #D8E4FF;border-radius:14px;background:#fff;cursor:pointer}
.option h4{font-size:13px}
.option p{font-size:11px;color:#64748B;margin-top:2px}
.option input{margin-top:2px}

.primary{width:100%;display:flex;align-items:center;justify-content:center;gap:8px;background:linear-gradient(90deg,#F7CE5B,#F4C542);color:#3A2A00;border:none;padding:15px;border-radius:12px;font-weight:800;font-size:15px;cursor:pointer;font-family:inherit}
.primary:hover{filter:brightness(1.03)}

.output-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:16px}
.actions button{margin-left:8px;padding:10px 14px;border:none;border-radius:10px;font-weight:700;cursor:pointer;font-family:inherit;font-size:13.5px}
.copy{background:#fff;border:1px solid #D8E4FF}
.download{background:#F4C542}
pre{background:#F8FBFF;border:1px solid #D8E4FF;border-radius:14px;padding:16px;min-height:300px;white-space:pre-wrap;line-height:1.7;font-family:'SFMono-Regular',Consolas,monospace;font-size:13px;color:#334155}

.learn-more{margin-top:22px;padding-top:20px;border-top:1px solid #E7EEFB;text-align:center}
.learn-btn{display:inline-flex;align-items:center;gap:8px;background:linear-gradient(90deg,#2563EB,#0B75C8);color:#fff;border:none;padding:14px 26px;border-radius:12px;font-weight:800;font-size:14.5px;cursor:pointer;font-family:inherit;box-shadow:0 10px 22px rgba(37,99,235,.25)}
.learn-btn:hover{filter:brightness(1.04)}
.learn-sub{font-size:12px;color:#64748B;margin-top:10px}

.modal-overlay{position:fixed;inset:0;background:rgba(15,23,42,.45);backdrop-filter:blur(3px);display:flex;align-items:center;justify-content:center;padding:20px;z-index:1000}
.modal-overlay[hidden]{display:none}
.modal-card{background:#fff;border-radius:20px;padding:32px;max-width:420px;width:100%;position:relative;box-shadow:0 24px 60px rgba(15,23,42,.25)}
.modal-close{position:absolute;top:16px;right:16px;width:30px;height:30px;border-radius:50%;border:none;background:#F1F5F9;color:#334155;font-size:14px;cursor:pointer;font-family:inherit}
.modal-card h3{font-size:20px;font-weight:800;margin-bottom:8px}
.modal-sub{font-size:13px;color:#64748B;margin-bottom:20px;line-height:1.5}
.modal-card .field{margin-bottom:16px}
.modal-submit{width:100%;margin-top:4px;padding:14px;border-radius:12px;font-weight:800;font-size:14.5px;border:none;cursor:pointer;font-family:inherit;background:linear-gradient(90deg,#2563EB,#0B75C8);color:#fff}
.modal-submit:disabled{opacity:.6;cursor:not-allowed}
.success-check{width:52px;height:52px;border-radius:50%;background:#ECFDF5;color:#059669;font-size:26px;display:flex;align-items:center;justify-content:center;margin:0 auto 16px;font-weight:800}
#modalSuccessView{text-align:center}

@media(max-width:1100px){body{padding:20px}.grid{grid-template-columns:1fr}.options{grid-template-columns:repeat(2,1fr)}.navbar nav{display:none}}
@media(max-width:700px){.options{grid-template-columns:1fr}.hero h1{font-size:34px}}
</style>
</head>
<body>
<div class="wrapper">

  <div class="navbar">
    <div class="logo">MOHIT'S <span class="badge">SEO TRAINING</span></div>
    <nav>
      <span>Home</span><span>Courses</span><span>Bangalore</span><span>Services</span><span>Blog</span><span>About</span>
    </nav>
    <button class="enroll" type="button">Enroll Now</button>
  </div>

  <div class="hero">
    <div class="eyebrow">🔧 FREE SEO TOOL</div>
    <div class="hero-icon">🤖</div>
    <h1>LLM<span class="grad">.txt</span> <span class="grad">Generator</span></h1>
    <p>Tell ChatGPT, Claude and Perplexity exactly how to use your site — in seconds.</p>
  </div>

  <div class="grid">

    <div class="card">
      <h2>Your site</h2>
      <p class="sub">Enter your website details and choose the pages you don't want AI models to reference.</p>

      <div class="field" id="siteNameField">
        <label for="siteName">Site Name</label>
        <input id="siteName" type="text" placeholder="Acme Inc.">
        <small class="error">Please enter your site name.</small>
      </div>
      <div class="field">
        <label for="domain">Domain (with https://)</label>
        <input id="domain" type="text" placeholder="https://acme.com">
      </div>
      <div class="field">
        <label for="summary">One-line summary</label>
        <input id="summary" type="text" placeholder="Acme builds developer tools for...">
      </div>

      <div class="section-title">Which pages should AI models skip?</div>
      <p class="desc">Select the pages you don't want ChatGPT, Claude and other AI assistants to reference.</p>
      <div class="options">
        <label class="option"><input type="checkbox" value="/wp-admin/"><div><h4>WP Admin Pages</h4><p>/wp-admin/</p></div></label>
        <label class="option"><input type="checkbox" value="/checkout/"><div><h4>Checkout Pages</h4><p>/checkout/</p></div></label>
        <label class="option"><input type="checkbox" value="/otp/"><div><h4>OTP Page</h4><p>/otp/</p></div></label>
        <label class="option"><input type="checkbox" value="/tag/"><div><h4>Tag Pages</h4><p>/tag/</p></div></label>
        <label class="option"><input type="checkbox" value="/category/"><div><h4>Category Pages</h4><p>/category/</p></div></label>
        <label class="option"><input type="checkbox" value="/search/"><div><h4>Search Pages</h4><p>/search/</p></div></label>
        <label class="option"><input type="checkbox" value="/author/"><div><h4>Author Pages</h4><p>/author/</p></div></label>
        <label class="option"><input type="checkbox" value="/*?*"><div><h4>URL Parameter Pages</h4><p>/*?*</p></div></label>
        <label class="option"><input type="checkbox" value="/feed/"><div><h4>Feed URLs</h4><p>/feed/</p></div></label>
      </div>

      <button type="button" class="primary" id="generateBtn">Generate llms.txt ✨</button>
    </div>

    <div class="card">
      <div class="output-head">
        <h2 style="font-size:22px">Your llms.txt</h2>
        <div class="actions">
          <button class="copy" type="button" id="copyBtn">Copy</button>
          <button class="download" type="button" id="downloadBtn">Download</button>
        </div>
      </div>
      <pre id="output">Fill in the form on the left and click Generate to preview your llms.txt here.</pre>

      <div class="learn-more">
        <button type="button" class="learn-btn" id="learnBtn">🚀 Learn Advanced AI SEO</button>
        <p class="learn-sub">Takes 10 seconds — leave your details and we'll reach out.</p>
      </div>
    </div>

  </div>
</div>

<div class="modal-overlay" id="leadOverlay" hidden>
  <div class="modal-card">
    <button type="button" class="modal-close" id="modalClose" aria-label="Close">✕</button>

    <div id="modalFormView">
      <h3>Learn Advanced AI SEO</h3>
      <p class="modal-sub">Leave your details and our team will send you personalised tips on optimising your site for AI search.</p>

      <div class="field" id="leadNameField">
        <label for="leadName">Name</label>
        <input id="leadName" type="text" placeholder="Your full name">
        <small class="error">Please enter your name.</small>
      </div>
      <div class="field" id="leadEmailField">
        <label for="leadEmail">Email</label>
        <input id="leadEmail" type="text" placeholder="you@example.com">
        <small class="error">Please enter a valid email address.</small>
      </div>
      <div class="field" id="leadPhoneField">
        <label for="leadPhone">Phone Number</label>
        <input id="leadPhone" type="text" placeholder="+91 98765 43210">
        <small class="error">Please enter a valid phone number.</small>
      </div>

      <button type="button" class="modal-submit" id="leadSubmitBtn">Submit</button>
    </div>

    <div id="modalSuccessView" hidden>
      <div class="success-check">✓</div>
      <h3>Thanks, you're all set!</h3>
      <p class="modal-sub">We've received your details — our team will reach out shortly with tips on Advanced AI SEO.</p>
      <button type="button" class="modal-submit" id="modalDoneBtn">Close</button>
    </div>
  </div>
</div>

<script>
function byId(id){return document.getElementById(id)}
function val(id){return byId(id).value.trim()}
function normalizeUrl(u){
  u=(u||"").trim();
  if(!u) return "";
  if(!/^https?:\/\//i.test(u)) u="https://"+u;
  return u.replace(/\/+$/,"");
}
function markError(fieldId){
  const wrap=byId(fieldId+"Field");
  wrap.classList.add("invalid");
  byId(fieldId).focus();
}
function clearError(fieldId){
  byId(fieldId+"Field").classList.remove("invalid");
}
byId("siteName").addEventListener("input",()=>clearError("siteName"));

function buildLlmsTxt(){
  const siteName=val("siteName");
  const domain=normalizeUrl(val("domain"));
  const summary=val("summary");
  let txt="# "+siteName+"\n";
  if(summary) txt+="> "+summary+"\n";
  txt+="\n";
  if(domain) txt+="Domain: "+domain+"\n\n";
  txt+="Allow: /\n";
  const excluded=Array.from(document.querySelectorAll(".option input:checked")).map(i=>i.value);
  if(excluded.length){
    txt+="\n";
    excluded.forEach(p=>txt+="Disallow: "+p+"\n");
  }
  return txt.trim()+"\n";
}

function generate(){
  if(!val("siteName")){markError("siteName");return}
  clearError("siteName");
  byId("output").textContent=buildLlmsTxt();
}
byId("generateBtn").addEventListener("click",generate);

function copyText(){
  const text=byId("output").textContent;
  const btn=byId("copyBtn");
  const label=btn.textContent;
  const flash=(msg)=>{btn.textContent=msg;setTimeout(()=>btn.textContent=label,1400)};
  if(navigator.clipboard && window.isSecureContext){
    navigator.clipboard.writeText(text).then(()=>flash("Copied!")).catch(()=>flash("Copy failed"));
  }else{
    try{
      const ta=document.createElement("textarea");
      ta.value=text;ta.style.position="fixed";ta.style.opacity="0";
      document.body.appendChild(ta);ta.select();
      document.execCommand("copy");
      document.body.removeChild(ta);
      flash("Copied!");
    }catch(e){flash("Copy failed")}
  }
}
byId("copyBtn").addEventListener("click",copyText);

function downloadTxt(){
  const blob=new Blob([byId("output").textContent],{type:"text/plain"});
  const url=URL.createObjectURL(blob);
  const a=document.createElement("a");
  a.href=url;a.download="llms.txt";a.click();
  setTimeout(()=>URL.revokeObjectURL(url),1000);
}
byId("downloadBtn").addEventListener("click",downloadTxt);

function openLeadModal(){
  byId("modalFormView").hidden=false;
  byId("modalSuccessView").hidden=true;
  byId("leadOverlay").hidden=false;
}
function closeLeadModal(){
  byId("leadOverlay").hidden=true;
}
byId("learnBtn").addEventListener("click",openLeadModal);
byId("modalClose").addEventListener("click",closeLeadModal);
byId("modalDoneBtn").addEventListener("click",closeLeadModal);
byId("leadOverlay").addEventListener("click",function(e){ if(e.target.id==="leadOverlay") closeLeadModal(); });

function validEmail(v){return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(v)}
function validPhone(v){return /^[0-9+\-\s()]{7,20}$/.test(v)}
function markLeadError(id){byId(id+"Field").classList.add("invalid")}
function clearLeadError(id){byId(id+"Field").classList.remove("invalid")}
["leadName","leadEmail","leadPhone"].forEach(id=>byId(id).addEventListener("input",()=>clearLeadError(id)));

function showLeadSuccess(){
  byId("modalFormView").hidden=true;
  byId("modalSuccessView").hidden=false;
}

function submitLead(){
  const name=val("leadName");
  const email=val("leadEmail");
  const phone=val("leadPhone");
  let ok=true;
  if(!name){markLeadError("leadName");ok=false}else clearLeadError("leadName");
  if(!validEmail(email)){markLeadError("leadEmail");ok=false}else clearLeadError("leadEmail");
  if(!validPhone(phone)){markLeadError("leadPhone");ok=false}else clearLeadError("leadPhone");
  if(!ok) return;

  const btn=byId("leadSubmitBtn");
  const originalLabel=btn.textContent;
  btn.disabled=true;btn.textContent="Sending...";

  const website=normalizeUrl(val("domain"))||"(not provided)";
  const payload={
    name:name,
    email:email,
    phone:phone,
    website:website,
    _subject:"New Advanced AI SEO lead — LLMs.txt Generator",
    _template:"table"
  };

  fetch("https://formsubmit.co/ajax/mohitsseotraining2021@gmail.com",{
    method:"POST",
    headers:{"Content-Type":"application/json","Accept":"application/json"},
    body:JSON.stringify(payload)
  }).then(res=>{
    if(!res.ok) throw new Error("request failed");
    return res.json();
  }).then(()=>{
    showLeadSuccess();
  }).catch(()=>{
    const subject="New Advanced AI SEO lead — LLMs.txt Generator";
    const body="Name: "+name+"\nEmail: "+email+"\nPhone: "+phone+"\nWebsite: "+website;
    window.location.href="mailto:mohitsseotraining2021@gmail.com?subject="+encodeURIComponent(subject)+"&body="+encodeURIComponent(body);
    showLeadSuccess();
  }).finally(()=>{
    btn.disabled=false;btn.textContent=originalLabel;
  });
}
byId("leadSubmitBtn").addEventListener("click",submitLead);
</script>
</body>
</html>
