<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
a {
  color:hotpink;
  text-decoration: none;
	}
	
#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: grey;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}

#myBtn:hover {
  background-color: #555;
}
	
* {box-sizing: border-box;}
table, th, td {
  border:0px solid #464646;
  text-align: center;
  border-collapse: collapse}


	th, td {
  text-align: center;
  padding: 1px;
}

th {
  background-color:#505c5e;
}

body { 
  height: 100%;
  color: #777;
  line-height: 1.8;
  margin:0px;
  font-family: Constantia, "Lucida Bright", "DejaVu Serif", Georgia, "serif";
  font-size: 20px;
  background-size:auto;
  background-repeat:no-repeat;
  text-align: justify;
}
	
.header {
  overflow: inherit;
  background-color: #505c5e;
  padding: 70px;
}

.header a {
  float: left;
  color: whitesmoke;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px; 
  line-height: 25px;
  border-radius: 4px;
}

.header a:hover {
  background-color: #ddd;
  color: black;
}

.header a.active {
  background-color: darkgray;
	color: white;
	}

.header-right {
  float: right;
}

@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
  
  .header-right {
    float: none;
  }
</style>
</head>

<body background="pierre-yves-vauzelle-clean.gif">
<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>
<div class="header">
  <div class="header-right">
	  
	<a href="PAGE 1.html"> Home </a>
	<a href="PAGE 1.html"> About</a>
	<a href="PAGE 2.html"> Academic </a>
	  <a href="PAGE 3.html"> Contact</a>
	  </div>
		 
	<script>

let mybutton = document.getElementById("myBtn");

window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}

function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>

 
 </div>
<center>
<br>
	
<table>
  
  <tr>
    <td><a href="PAGE 1.html"><img src="1.jpg" height="200" width="200" alt="about"></a></td>
	<td><a href="PAGE 2.html"><img src="2.jpg" height="200" width="200" alt=" academic"></a></td>
	<td><a href="PAGE 3.html"> <img src="3.jpg" height="200" width="200" alt="social"></a></td>
}

</tr>
</table>
</center>	
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
a {
  color:hotpink;
  text-decoration: none;
	}
	
#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: grey;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}

#myBtn:hover {
  background-color: #555;
}
	
* {box-sizing: border-box;}
table, th, td {
  border:0px solid #464646;
  text-align: center;
  border-collapse: collapse}


	th, td {
  text-align: center;
  padding: 1px;
}

th {
  background-color:#505c5e;
}

body { 
  height: 100%;
  color: #777;
  line-height: 1.8;
  margin:0px;
  font-family: Constantia, "Lucida Bright", "DejaVu Serif", Georgia, "serif";
  font-size: 20px;
  background-size: cover;
  background-repeat: no-repeat;
  text-align: justify;
}
	
.header {
  overflow: inherit;
  background-color: #505c5e;
  padding: 70px;
}

.header a {
  float: left;
  color: whitesmoke;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px; 
  line-height: 25px;
  border-radius: 4px;
}

.header a:hover {
  background-color: #ddd;
  color: black;
}

.header a.active {
  background-color: darkgray;
	color: white;
	}

.header-right {
  float: right;
}

@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
  
  .header-right {
    float: none;
  }
</style>
</head>

<body background="952195.jpg">
<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>
<div class="header">
  <div class="header-right">
	  
	<script>

let mybutton = document.getElementById("myBtn");

window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}

function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>

  
    <a href="HOME PAGE.html"> Home </a>
	<a href="PAGE 1.html"> About</a>
	<a href="PAGE 2.html"> Academic </a>
	<a href="PAGE 3.html"> Contact</a>
 
 </div>
</div>
	

	
   <div class="header-right"> 
	   <img src="bnm.jpg" alt="Photo of Me" width="350" height="430">
</div>


<h1> Little things about me...</h1> 
<div class="active" align="left">
<ul><i>
<li> Name: Nur Atikah Binti Akmal</li>
<li> Nickname: Atie/Jia </li>
<li>Age: 21 years old</li>
<li>Date of birth: 13 June 2002</li>
<li> Hobbies: Jogging, reading, watching movies </li>
<li>Likes: Spicy foods, kdrama, cdrama, anime, cats</li>
<li>Dislikes: lizard</li>
</i></ul>
</div>
<br>
<br>
<br>
<center>
<h3> Fun Fact about me...</h3>
<p align="justify"> I enjoy travelling, thrift store shopping, and watching the sunset. If I had the opportunity, I would adore travelling the entire world. I love coffee, and anything with caramel is my all-time favourite drink. I grew up in Sepang and was born in Kajang. I like to doodle and draw. I once participated in a project that required me to paint a mural at primary school in Chengkau. </p>
<br>
<br>
<h5><a href="https://www.instagram.com/atiiekahh/"> Instagram .</a> <a href="https://twitter.com/jiaieka"> Twitter.</a> <a href="https://www.tiktok.com/@tjiali?lang=en"> Tik Tok.</a>&nbsp;</h5>

</center>	
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>	
a {
  color:saddlebrown;
  text-decoration: none;
	}
#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: grey;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}

#myBtn:hover {
  background-color: #555;
}
	
* {box-sizing: border-box;}
table, th, td {
  border:0px solid #464646;
  text-align: center;
  border-collapse: collapse}


	th, td {
  text-align: center;
  padding: 1px;
}

th {
  background-color:#505c5e;
}

body { 
  height: 100%;
  color: #777;
  line-height: 1.8;
  margin:0px;
  font-family: Constantia, "Lucida Bright", "DejaVu Serif", Georgia, "serif";
  font-size: 20px;
  background-size: cover;
  background-repeat: no-repeat;
  text-align: justify;
}
	
.header {
  overflow: inherit;
  background-color: #505c5e;
  padding: 70px;
}

.header a {
  float: left;
  color: whitesmoke;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px; 
  line-height: 25px;
  border-radius: 4px;
}

.header a:hover {
  background-color: #ddd;
  color: black;
}

.header a.active {
  background-color: darkgray;
	color: white;
	}

.header-right {
  float: right;
}

@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
  
  .header-right {
    float: none;
  }
</style>
</head>

<body background="952195.jpg">
<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>
<div class="header">
  <div class="header-right">
	  
	<script>

let mybutton = document.getElementById("myBtn");

window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}

function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>

  
    <a href="HOME PAGE.html"> Home </a>
	<a href="PAGE 1.html"> About</a>
	<a href="PAGE 2.html"> Academic </a>
	<a href="PAGE 3.html"> Contact</a>
 
 </div>
</div>
	
<center>
<h1> Academic Background</h1>
<table>
<tr>
<td> <a href="https://ms.wikipedia.org/wiki/Sekolah_Kebangsaan_Bandar_Baru_Salak_Tinggi"><img src="Sekolah_Kebangsaan_Bandar_Baru_Salak_Tinggi.jpg" height="150" alt="sebati"><br>SK BANDAR BARU SALAK TINGGI (seBATI) </a></td>	
<td> I started my primary education at Sekolah Kebangsaan Bandar Baru Salak Tinggi (SKBBST) in 2009 and finished in 2014.In addition to the acronym SKBBST, this school is also known as seBati.</td>
</tr>
<tr>
<td>After completing primary education, I continued my studies at Sekolah Menengah Kebangsaan Seri Sepang in 2015 until 2019..</td>
<td> <a href="https://ms.wikipedia.org/wiki/Sekolah_Menengah_Kebangsaan_Seri_Sepang"> <img src="Sekolah_Menengah_Kebangsaan_Seri_Sepang.jpeg" height="150" alt="smkss"><br>SMK SERI SEPANG (SMKSS) </a></td>	
</tr>
<tr>
<td> <a href="https://www.google.com/maps/dir//uitm+rembau/data=!4m6!4m5!1m1!4e2!1m2!1m1!1s0x31cdfd8ea33825ad:0x5aa3255f8a169f1c?sa=X&ved=2ahUKEwippu70sKeAAxUnxDgGHQwXCjUQ9Rd6BAhDEAA&ved=2ahUKEwippu70sKeAAxUnxDgGHQwXCjUQ9Rd6BAhLEAU"><img src="UiTM-Logo.png" height="150" alt="sebati"><br>UITM REMBAU CAMPUS </a></td>	
<td>After completing my studies at the secondary level, I intend to continue my studies at the Diploma level. In 2021, I will continue my studies at UiTM Rembau campus. Now as a final year diploma student, I intend to continue my studies to a higher level.</td>
</tr>
</table>	

</center>	
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
	
  
  
  a {
  color:saddlebrown;
  text-decoration: none;
	}
#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: grey;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}

#myBtn:hover {
  background-color: #555;
}
	
* {box-sizing: border-box;}
table, th, td {
  border:0px solid #464646;
  text-align: center;
  border-collapse: collapse}


	th, td {
  text-align: center;
  padding: 1px;
}

th {
  background-color:#505c5e;
}

body { 
  height: 100%;
  color: #777;
  line-height: 1.8;
  margin:0px;
  font-family: Constantia, "Lucida Bright", "DejaVu Serif", Georgia, "serif";
  font-size: 20px;
  background-size: cover;
  background-repeat: no-repeat;
  text-align: justify;
}
	
.header {
  overflow: inherit;
  background-color: #505c5e;
  padding: 70px;
}

.header a {
  float: left;
  color: whitesmoke;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px; 
  line-height: 25px;
  border-radius: 4px;
}

.header a:hover {
  background-color: #ddd;
  color: black;
}

.header a.active {
  background-color: darkgray;
	color: white;
	}

.header-right {
  float: right;
}

@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
  
  .header-right {
    float: none;
  }
</style>
</head>

<body background="952195.jpg">
<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>
<div class="header">
  <div class="header-right">
	  
	<script>

let mybutton = document.getElementById("myBtn");

window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}

function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>

  
    <a href="HOME PAGE.html"> Home </a>
	<a href="PAGE 1.html"> About</a>
	<a href="PAGE 2.html"> Academic </a>
	<a href="PAGE 3.html"> Contact</a>
 
 </div>
</div>
<center>
<h1> Contact me via ;</h1>
<table>
<tr>
<td> <a href="https://www.instagram.com/atiiekahh/"><img src="Instagram_logo_2016.svg.png" height="150" alt="ig"><br> @ atiiekahh </a></td>
<br>
<td> <a href="https://twitter.com/jiaieka"><img src="Logo_of_Twitter.svg.png" height="150" alt="ig"> <br> @jiaieka </a></td>
<br>
<td> <a href="https://www.tiktok.com/@tjiali?lang=en"><img src="627bb8132bc3a3762a1d0b98.png" height="150" alt="ig"> <br> @tjiali </a></td>	
</tr>
</table>	

</center>	
</body>
</html>
