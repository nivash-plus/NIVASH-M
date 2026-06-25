
<!DOCTYPE html>
<html>
<head>
<title>Nivash Profile</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Trebuchet MS', sans-serif;
}

body{
    background:url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?w=1600') no-repeat center center/cover;
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
}

.container{
    width:90%;
    max-width:1000px;
    padding:20px;
}

h1{
    text-align:center;
    color:white;
    font-size:45px;
    margin-bottom:25px;
    text-shadow:0 0 15px cyan;
}

.boxes{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.box{
    background:rgba(255,255,255,0.15);
    backdrop-filter:blur(10px);
    border:2px solid rgba(255,255,255,0.3);
    border-radius:20px;
    padding:20px;
    color:lite blue;
    box-shadow:0 0 20px rgba(0,255,255,0.5);
    transition:0.4s;
}

.box:hover{
    transform:translateY(-10px) scale(1.03);
    box-shadow:0 0 30px cyan;
}

.box h2{
    color:#ffcc00;
    margin-bottom:10px;
    text-align:center;
    text-shadow:0 0 10px cyan;
}

.box p, .box li{
    font-size:18px;
    line-height:1.8;
}

ul{
    list-style:none;
}
</style>
</head>

<body>

<div class="container">

<h1>✨ Nivash Profile ✨</h1>

<div class="boxes">

<div class="box">
<h2>👤 Personal Details</h2>
<p><b>Name:</b> Nivash M</p>
<p><b>DOB:</b> 17/05/2009</p>
<p><b>Course:</b> B.Sc Cyber Security</p>
<p><b>College:</b> RD National Arts & Science College</p>
<p><b>Place:</b> Erode</p>
</div>

<div class="box">
<h2>📖 About Me</h2>
<p>
I am Nivash, a Cyber Security student at RD National Arts & Science College.
I am interested in technology, ethical hacking, coding and learning new cybersecurity skills.
</p>
</div>

<div class="box">
<h2>💻 Skills</h2>
<ul>
<li>HTML</li>
<li>Basic Python</li>
<li>Cyber Security Basics</li>
<li>Problem Solving</li>
<li>Communication</li>
</ul>
</div>

<div class="box">
<h2>❤️ Favourite</h2>
<ul>
<li>Technology</li>
<li>Cyber Security</li>
<li>Coding</li>
<li>Gaming</li>
<li>Music</li>
</ul>
</div>

</div>
</div>

</body>
</html>
