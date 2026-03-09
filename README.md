<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Arpit ❤️ Muskan</title>

<style>

body{
margin:0;
padding:0;
font-family: Arial;
background: linear-gradient(45deg,#ff4e8a,#ff9a9e);
text-align:center;
color:white;
}

h1{
margin-top:100px;
font-size:50px;
animation: glow 2s infinite alternate;
}

@keyframes glow{
from{ text-shadow:0 0 10px white;}
to{ text-shadow:0 0 30px red;}
}

.heart{
font-size:100px;
animation: beat 1s infinite;
}

@keyframes beat{
0%{transform:scale(1);}
50%{transform:scale(1.2);}
100%{transform:scale(1);}
}

.message{
font-size:25px;
margin-top:20px;
}

button{
margin-top:40px;
padding:15px 30px;
font-size:18px;
background:red;
border:none;
color:white;
border-radius:30px;
cursor:pointer;
}

button:hover{
background:darkred;
}

</style>
</head>

<body>

<h1>Arpit ❤️ Muskan</h1>

<div class="heart">❤️</div>

<div class="message">
Forever Love Story <br>
Arpit Loves Muskan 💖
</div>

<button onclick="showLove()">Click For Love Message</button>

<script>

function showLove(){
alert("Muskan ❤️ You are my life forever - Arpit");
}

</script>

</body>
</html>
