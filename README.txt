
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sirat Grow It Agency</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:Arial,sans-serif;background:#f4f7fc;color:#17233d;line-height:1.6}
header{background:#071b3c;color:white;padding:18px 6%;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px}
.logo{font-size:21px;font-weight:bold}
nav a{color:white;text-decoration:none;margin:8px;font-size:14px}
.hero{padding:75px 7%;background:linear-gradient(125deg,#061a3a,#1262b5);color:white;text-align:center}
.hero h1{font-size:clamp(30px,6vw,52px);line-height:1.2;margin-bottom:18px}
.hero p{max-width:650px;margin:0 auto 25px;color:#dceaff}
.btn{display:inline-block;background:#ffbd35;color:#10213d;padding:13px 24px;border-radius:8px;text-decoration:none;font-weight:bold;border:0;cursor:pointer}
section{padding:55px 6%}
.heading{text-align:center;margin-bottom:30px}
.heading h2{font-size:30px;color:#092958}
.heading p{color:#64748b}
.services{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px}
.card{background:white;border-radius:14px;overflow:hidden;box-shadow:0 5px 22px #102b5012}
.poster{height:175px;display:flex;align-items:center;justify-content:center;text-align:center;padding:20px;color:white;font-size:23px;font-weight:bold;background:linear-gradient(135deg,#092957,#1686d9)}
.poster:nth-child(odd){background:linear-gradient(135deg,#10254c,#397bd2)}
.cardbody{padding:19px}
.cardbody h3{margin-bottom:8px}
.cardbody p{color:#64748b;font-size:14px;margin-bottom:15px}
.cardbody button{width:100%;background:#0d4e9b;color:white;padding:11px;border:0;border-radius:7px;font-weight:bold;cursor:pointer}
.about{background:#e8f1fc;text-align:center}
.about p{max-width:750px;margin:auto;color:#52647d}
.reviews{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:15px}
.review{background:white;padding:20px;border-radius:12px}
.review small{color:#b36d00}
.contact{text-align:center;background:#09234a;color:white}
.contact p{margin:8px}
footer{text-align:center;padding:20px;background:#06152e;color:#cbd5e1;font-size:13px}
.modal{display:none;position:fixed;inset:0;background:#0009;z-index:10;align-items:center;justify-content:center;padding:15px}
.modalbox{background:white;padding:25px;border-radius:14px;width:100%;max-width:430px;max-height:90vh;overflow:auto}
.modalbox h2{margin-bottom:12px}
.modalbox select,.modalbox input{width:100%;padding:12px;margin:8px 0;border:1px solid #ccd5e3;border-radius:7px}
.modalbox button{width:100%;padding:12px;margin-top:10px;border:0;border-radius:7px;cursor:pointer;background:#087b48;color:white;font-weight:bold}
.modalbox .close{background:#64748b}
.payments{display:grid;grid-template-columns:repeat(2,1fr);gap:8px;margin:10px 0}
.payments label{border:1px solid #d6dfeb;padding:9px;border-radius:7px;font-size:14px}
@media(max-width:550px){header{justify-content:center;text-align:center}nav{width:100%}.hero{padding:55px 6%}}
</style>
</head>
<body>

<header>
<div class="logo">Sirat Grow It Agency</div>
<nav>
<a href="#home">Home</a>
<a href="#services">Services</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>
</header>

<div class="hero" id="home">
<h1>Grow Your Business Digitally</h1>
<p>Professional Digital Marketing, Social Media Growth, Design and Online Business Services.</p>
<a href="#services" class="btn">Explore Our Services</a>
</div>

<section id="services">
<div class="heading">
<h2>Our Services</h2>
<p>Choose a service and place your order through WhatsApp.</p>
</div>
<div class="services" id="serviceList"></div>
</section>

<section class="about" id="about">
<div class="heading"><h2>About Our Agency</h2></div>
<p>Sirat Grow It Agency provides digital marketing, social media support, creative design and online business solutions. Our goal is to help businesses grow online with professional services.</p>
</section>

<section>
<div class="heading">
<h2>Client Feedback</h2>
<p>Sample testimonials — replace these with genuine customer reviews before publishing.</p>
</div>
<div class="reviews">
<div class="review">⭐⭐⭐⭐⭐<p>Professional service and friendly communication.</p><small>Sample review — not verified</small></div>
<div class="review">⭐⭐⭐⭐⭐<p>Good experience with the service process.</p><small>Sample review — not verified</small></div>
<div class="review">⭐⭐⭐⭐⭐<p>Helpful support and smooth communication.</p><small>Sample review — not verified</small></div>
</div>
</section>

<section class="contact" id="contact">
<h2>Contact Us</h2>
<p>WhatsApp: +8801913022305</p>
<p>Email: siratakanda06@gmail.com</p>
<p>Location: Kishoreganj, Bangladesh</p>
<a class="btn" href="https://wa.me/8801913022305">Chat on WhatsApp</a>
</section>

<footer>© 2026 Sirat Grow It Agency. All rights reserved.</footer>

<div class="modal" id="orderModal">
<div class="modalbox">
<h2>Place Your Order</h2>
<p id="chosenService"></p>
<label>Your Name</label>
<input id="customerName" placeholder="Enter your name">
<label>Select Package</label>
<select id="package">
<option>Basic</option><option>Standard</option><option>Premium</option>
</select>
<label>Amount (BDT)</label>
<input id="amount" type="number" placeholder="Enter agreed amount">
<label>Select Payment Method</label>
<div class="payments">
<label><input type="radio" name="pay" value="bKash"> bKash</label>
<label><input type="radio" name="pay" value="Nagad"> Nagad</label>
<label><input type="radio" name="pay" value="Rocket"> Rocket</label>
<label><input type="radio" name="pay" value="Bank Account"> Bank</label>
<label><input type="radio" name="pay" value="Visa"> Visa</label>
<label><input type="radio" name="pay" value="Binance"> Binance</label>
<label><input type="radio" name="pay" value="Western Union"> Western Union</label>
<label><input type="radio" name="pay" value="Ria"> Ria</label>
<label><input type="radio" name="pay" value="Payoneer"> Payoneer</label>
<label><input type="radio" name="pay" value="PayPal"> PayPal</label>
<label><input type="radio" name="pay" value="MoneyGram"> MoneyGram</label>
</div>
<button onclick="sendOrder()">Order on WhatsApp</button>
<button class="close" onclick="closeModal()">Close</button>
</div>
</div>

<script>
const services=[
["Facebook Marketing","Facebook promotion and business growth."],
["Instagram Marketing","Instagram account growth and promotion."],
["YouTube Services","YouTube channel growth and support."],
["Graphic Design","Creative social media and business designs."],
["Digital Marketing","Professional online marketing solutions."],
["Website Design","Responsive website design and development."],
["Social Media Management","Social media page management."],
["Business Promotion","Digital promotion for your business."]
];

const list=document.getElementById("serviceList");
services.forEach((s,i)=>{
list.innerHTML+=`
<div class="card">
<div class="poster">✦<br>${s[0]}</div>
<div class="cardbody">
<h3>${s[0]}</h3>
<p>${s[1]}</p>
<button onclick="openModal('${s[0]}')">Order Now</button>
</div></div>`;
});

function openModal(name){
document.getElementById("chosenService").textContent="Service: "+name;
document.getElementById("orderModal").style.display="flex";
}
function closeModal(){
document.getElementById("orderModal").style.display="none";
}
function sendOrder(){
const name=document.getElementById("customerName").value;
const service=document.getElementById("chosenService").textContent;
const pack=document.getElementById("package").value;
const amount=document.getElementById("amount").value;
const payment=document.querySelector('input[name="pay"]:checked');
if(!name||!amount||!payment){alert("Please fill in all details and select payment method.");return;}
const msg=`Hello Sirat Grow It Agency!
Name: ${name}
${service}
Package: ${pack}
Amount: ${amount} BDT
Payment: ${payment.value}
I want to place an order.`;
window.open("https://wa.me/8801913022305?text="+encodeURIComponent(msg),"_blank");
}

if(location.hash==="#owner"){
const pin=prompt("Enter owner PIN");
if(pin==="SGIA-OWNER-2026"){
alert("Owner shortcut accepted. This is not secure authentication.");
}else{
history.replaceState(null,"",location.pathname);
alert("Incorrect PIN");
}
}
</script>
</body>
</html>
