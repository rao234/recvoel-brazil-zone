# recvoel-brazil-zone
<!DOCTYPE html>
<html>
<head>
<title>Recvoel Brazil Zone</title>

<style>

body{
background:#0f0f0f;
color:white;
font-family:Arial;
text-align:center;
}

h1{
color:red;
font-size:40px;
}

.search{
margin:20px;
}

input{
padding:12px;
width:80%;
border-radius:20px;
border:none;
}

.card{
background:#1c1c1c;
margin:20px;
padding:20px;
border-radius:15px;
box-shadow:0 0 15px red;
}

h2{
color:#00eaff;
}

</style>

<script>

function searchDevice(){
let input=document.getElementById("search").value.toLowerCase();
let cards=document.getElementsByClassName("card");

for(let i=0;i<cards.length;i++){
let text=cards[i].innerText.toLowerCase();

if(text.includes(input)){
cards[i].style.display="block";
}
else{
cards[i].style.display="none";
}
}
}

</script>

</head>

<body>

<h1>🔥 RECVOEL BRAZIL ZONE</h1>

<p>Best Free Fire Sensitivity (0-200)</p>

<div class="search">

<input id="search" onkeyup="searchDevice()" placeholder="Search your device">

</div>

<div class="card">

<h2>🇧🇷 Brazil Pro Sensitivity</h2>

General: 180<br>
Red Dot: 170<br>
2x Scope: 160<br>
4x Scope: 150<br>
AWM Scope: 130<br>
Free Look: 140

</div>

<div class="card">

<h2>📱 Low End Phones</h2>

General: 200<br>
Red Dot: 190<br>
2x Scope: 180<br>
4x Scope: 170<br>
AWM Scope: 150<br>
Free Look: 160

</div>

<div class="card">

<h2>📱 Redmi 12</h2>

General: 195<br>
Red Dot: 185<br>
2x Scope: 175<br>
4x Scope: 165<br>
AWM Scope: 145<br>
Free Look: 150

</div>

</body>
</html>
