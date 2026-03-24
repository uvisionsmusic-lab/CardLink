#   
  
<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>Moxify — Never Miss Another Lead</title>  
  
<style>  
:root {  
  --green:#1f7a4d;  
  --green-light:#2ecc71;  
  --black:#0a0a0a;  
  --dark:#141414;  
  --white:#ffffff;  
  --gray:#b5b5b5;  
  --gold:#d4af37;  
}  
  
*{margin:0;padding:0;box-sizing:border-box;}  
  
body{  
  font-family:Arial,sans-serif;  
  background:var(--black);  
  color:var(--white);  
  line-height:1.6;  
}  
  
/* NAV */  
nav{  
  position:fixed;  
  width:100%;  
  display:flex;  
  justify-content:space-between;  
  padding:20px 40px;  
  background:rgba(0,0,0,0.95);  
  z-index:100;  
}  
  
.logo{  
  color:var(--green-light);  
  font-weight:700;  
  letter-spacing:3px;  
}  
  
.nav-cta{  
  background:var(--green);  
  padding:10px 20px;  
  text-decoration:none;  
  color:white;  
}  
  
/* HERO */  
.hero{  
  padding:160px 40px 80px;  
  max-width:900px;  
}  
  
h1{  
  font-size:58px;  
  margin-bottom:20px;  
}  
  
.highlight{  
  color:var(--green-light);  
}  
  
.sub{  
  font-size:20px;  
  color:var(--gray);  
  margin-bottom:30px;  
}  
  
.btn{  
  display:inline-block;  
  padding:16px 30px;  
  background:var(--green);  
  color:white;  
  text-decoration:none;  
  margin-right:10px;  
  font-weight:bold;  
}  
  
.btn-secondary{  
  border:1px solid var(--gold);  
  color:var(--gold);  
  background:none;  
}  
  
/* TRUST */  
.trust{  
  padding:40px;  
  background:var(--dark);  
  text-align:center;  
  color:var(--gray);  
}  
  
/* SECTION */  
.section{  
  padding:80px 40px;  
  max-width:900px;  
}  
  
h2{  
  font-size:40px;  
  margin-bottom:20px;  
}  
  
p{  
  color:var(--gray);  
  margin-bottom:20px;  
}  
  
/* CTA */  
.cta{  
  background:var(--green);  
  padding:60px 40px;  
  text-align:center;  
}  
  
.cta input{  
  padding:14px;  
  width:250px;  
  border:none;  
  margin:10px;  
}  
  
.cta button{  
  padding:14px 20px;  
  background:var(--black);  
  color:white;  
  border:none;  
  font-weight:bold;  
}  
  
/* FOOTER */  
footer{  
  text-align:center;  
  padding:20px;  
  color:var(--gray);  
}  
</style>  
</head>  
  
<body>  
  
<nav>  
  <div class="logo">MOXIFY</div>  
  <a href="#cta" class="nav-cta">Book Demo</a>  
</nav>  
  
<section class="hero">  
  <h1>You’re Losing <span class="highlight">$100K+ Per Year</span> in Missed Calls</h1>  
  <p class="sub">  
    While you're busy, your leads are calling someone else.    
    Moxify answers every call, qualifies the lead, and books appointments — automatically.  
  </p>  
  
  <a href="#cta" class="btn">Book Free Demo</a>  
  <a href="#problem" class="btn btn-secondary">See How It Works</a>  
</section>  
  
<div class="trust">  
  Trusted by agents closing 6–7 figures • Works 24/7 • No missed opportunities  
</div>  
  
<section class="section" id="problem">  
  <h2>The Problem</h2>  
  <p>  
    40% of calls go unanswered.    
    78% of buyers work with the first agent who responds.    
    That means if you miss the call — you lose the deal.  
  </p>  
  
  <p>  
    Every missed call isn’t just a lead…    
    it’s thousands of dollars gone.  
  </p>  
</section>  
  
<section class="section">  
  <h2>The Solution</h2>  
  <p>  
    Moxify gives you a 24/7 AI voice assistant that:  
  </p>  
  
  <p>✔ Answers instantly</p>  
  <p>✔ Qualifies leads</p>  
  <p>✔ Books appointments</p>  
  <p>✔ Sends you summaries</p>  
  
  <p>  
    You focus on closing.    
    We handle everything else.  
  </p>  
</section>  
  
<section class="cta" id="cta">  
  <h2>Book Your Free Demo</h2>  
  <p>Enter your number and we’ll call you within 24 hours</p>  
  
  <form onsubmit="handleForm(event)">  
    <input id="phone" placeholder="Phone Number">  
    <button type="submit">Book Demo</button>  
  </form>  
  
  <p id="msg"></p>  
</section>  
  
<footer>  
  © 2026 Moxify • hello@moxify.com  
</footer>  
  
<script>  
function handleForm(e){  
  e.preventDefault();  
  let phone=document.getElementById('phone').value;  
  let msg=document.getElementById('msg');  
  
  if(phone.replace(/\D/g,'').length>=10){  
    msg.innerText="✅ You're booked. We'll contact you shortly.";  
    msg.style.color="lightgreen";  
  } else {  
    msg.innerText="Enter a valid phone number";  
    msg.style.color="red";  
  }  
}  
</script>  
  
</body>  
</html>  
