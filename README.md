<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Gurbani Kaur 💖</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
background:linear-gradient(135deg,#ffd6e8,#fff5f8,#ffe8f2);
overflow:hidden;
}

.card{
background:white;
padding:35px;
border-radius:25px;
box-shadow:0 15px 40px rgba(255,105,180,.25);
text-align:center;
width:350px;
position:relative;
}

h1{
color:#ff4f8b;
font-size:28px;
margin-bottom:10px;
}

p{
color:#666;
margin-bottom:25px;
font-size:18px;
}

.heart{
font-size:60px;
animation:beat 1s infinite;
margin-bottom:15px;
}

@keyframes beat{
50%{
transform:scale(1.15);
}
}

.buttons{
position:relative;
height:120px;
}

button{
padding:12px 28px;
border:none;
border-radius:30px;
font-size:18px;
cursor:pointer;
transition:.25s;
}

#yes{
background:#ff6fa5;
color:white;
}

#yes:hover{
transform:scale(1.08);
}

#no{
background:#ddd;
position:absolute;
left:180px;
top:0;
}

#message{
margin-top:20px;
font-size:22px;
color:#ff4f8b;
font-weight:bold;
display:none;
}
</style>
</head>

<body>

<div class="card">
<div class="heart">💖</div>

<h1>Hi Gurbani Kaur 🌸</h1>

<p>Will you be my friend? 🥹</p>

<div class="buttons">
<button id="yes">Yes 💕</button>
<button id="no">No 🙈</button>
</div>

<div id="message">
Yay!! 💖<br>
You made my day! 🌷
</div>

</div>

<script>

const no=document.getElementById("no");

function moveButton(){
const x=Math.random()*220;
const y=Math.random()*80;
no.style.left=x+"px";
no.style.top=y+"px";
}

no.addEventListener("mouseover",moveButton);
no.addEventListener("touchstart",function(e){
e.preventDefault();
moveButto
