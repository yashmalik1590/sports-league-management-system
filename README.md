<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sports leauge management platform</title>
</head>
<link rel="stylesheet" href="css/style.css">
<style>
    @font-face {
        font-family: myfirstfont;
        src: url(/YoungSerif-Regular.ttf);
    }
    #bar{
        background-color: rgb(215, 215, 215);
        border-style: groove;
        margin-top: -20px;
        height: 60px;
        border-radius: 5px;

    }
    #bar , .btn{
        font-family: myfirstfont;
     }
    body{
        background-color: rgb(67, 66, 66);
        background-repeat: no-repeat;
    }
    .left{
        position: absolute;
        left: 34px;
        display: inline-block;
    }
    .mid{
        width: 40%;
        margin: auto;
        height: 10px;
        padding-top: 2px;
    }
    .right{
        position: absolute;
        right: 34px;
        display: inline-block;
        padding-top: 4px;
        padding-right: -15px;
    }
    .navbar{
        display: inline-block;

    }
    .navbar li{
        display: inline-block;
        font-size: 20px;
    }
    .navbar li a{
        color: rgb(51 0 0);
        text-decoration: none;
        padding: 34px 23px;
    }
    .navbar li a:hover, .navbar li a.active{
        text-decoration: underline;
        color: rgb(239, 239, 239);
    }
    .left img{
        width: 50px;
        padding-top: 8px;
    }
    .btn{
        margin: 0px 9px;
        background-color: rgb(164, 163, 163);
        color: rgb(51 0 0);
        padding: 4px;
        border: 2px solid grey;
        font-size: 15px;
        cursor: pointer;
    }
    .btn:hover{
        color: rgb(235, 228, 228);
    }
    .event-container{
        background-image: url(/ft2.jpg);
        background-size: 500px;
        font-size: 15px;
        color: rgb(16, 16, 16);
        height: 420px;
        padding-left: 20px;
       width: 350px;
       border: 1px solid rgb(197, 193, 193);
        margin-top: 30px;
        margin-left: 200px;
        border-radius: 4px;
    }
    .upc{
        color: white;
        margin-top: 100px;
        font-size: 23px;
        border: 1px solid rgb(110, 120, 123);
        padding-left:60px;
        background-color: rgb(127, 135, 137);
        padding-top: 10px;
        border-radius: 5px;
        margin-left: 700px;
        margin-right: 600px;
    }
    .line1{
        margin-right: 550px;
    }
    #paragraph{
        color: rgb(15, 14, 14);
        font-style: italic;
    }
    .event-container2{
        background-image: url(/cr.jpeg);
        background-size: 500px;
        font-size: 15px;
        color: rgb(202, 202, 202);
        height: 420px;
        padding-left: 20px;
       width: 350px;
       border: 1px solid rgb(197, 193, 193);
        margin-top: -420px;
        margin-left: 600px;
        border-radius: 4px;
    }
    .event-container3{
        background-image: url(/chess.jpeg);
        background-size: 500px;
        font-size: 15px;
        color: rgb(202, 202, 202);
        height: 420px;
        padding-left: 20px;
       width: 350px;
       border: 1px solid rgb(197, 193, 193);
        margin-top: -420px;
        margin-left: 1000px;
        border-radius: 4px;
    }
    .mid img{
        width: 1400px;
        height: 620px;
        margin-left: -400px;
        margin-top: 18px;
    }
    .aboutus{
        margin-top: 50px;
    }
</style>
<body>
    <div id="bar"> 
    <header class="header">
        <div class="left">
            <img src="/logo3.jpg">
        </div>
        <div class="mid">
            <ul class="navbar">
                <li><a href="#">Home</a></li>
                <li><a href="/categories.html">Categories</a></li>
                <li><a href="/events.html">Events</a></li>
                <li><a href="/contact.html">Contact Us</a></li>
            </ul>
        </div>
        <div class="right">
                <button class="btn">call us now</button>
                <button class="btn">email us</button>
        </div>
    </header>
</div>
    
    <br> 
    <div class="mid img">
        <img src="/blur.jpg">
    </div>
    <div class="upc">UPCOMING MATCHES</div>
    
    <div class="event-container" >
        <div class="event">
            <h2>Football matches</h2>
            <h3>Match 1</h3>
            <p>Date: October 15, 2023</p>
            <p>Time: 3:00 PM</p>
            <p>Location: lpu stadium</p>
            <p>Teams: Team A vs. Team B</p>
            </div>
            
        <div class="event">
        <h2>Match 2 </h2>
        <p>Date: October 20, 2023</p>
        <p>Time: 7:30 PM</p>
        <p>Location: lpu basketball ground</p>
        <p>Teams: Team X vs. Team Y</p>
            </div>
</div>
<div class="event-container2" >
        <div class="event2">
            <h2>Cricket matches</h2>
            <h3>Match 1</h3>
            <p>Date: October 16, 2023</p>
            <p>Time: 3:00 PM</p>
            <p>Location: lpu stadium</p>
            <p>Teams: Team A vs. Team B</p>
                </div>
                    
            <div class="event2">
            <h2>Match 2</h2>
            <p>Date: October 25, 2023</p>
            <p>Time: 7:30 PM</p>
            <p>Location: lpu ground 1</p>
            <p>Teams: Team X vs. Team Y</p>
                </div>
</div>
                
<div class="event-container3" >
    <div class="event3">
        <h2>Chess matches</h2>
        <h3>Match 1</h3>
        <p>Date: October 16, 2023</p>
        <p>Time: 3:00 PM</p>
        <p>Location: lpu indoor sports complex</p>
        <p>Teams: Team A vs. Team B</p>
            </div>
                
        <div class="event3">
        <h2>Match 2</h2>
        <p>Date: October 25, 2023</p>
        <p>Time: 7:30 PM</p>
        <p>Location: lpu indoor sports complex</p>
        <p>Teams: Team X vs. Team Y</p>
            </div>
</div>
<div class="aboutus">
    <p>ABOUT US
        <br>
    We are dedicated to revolutionizing the way sports leagues are organized and managed.Our platform provides a comprehensive solution for league administrators,
     coaches, players, and fans. Whether you're running a local youth league or managing 
     a professional sports organization, we've got you covered.Key features of our platform include:Efficient league scheduling and fixture management
    Player registration and team management tools
    Fan engagement and live updates
    Our mission is to simplify the process of running sports leagues, so you can focus on what matters most: the game. We are passionate about sports and
    technology, and we're excited to be part of your sports journey.Thank you for choosing our Sports League Management Platform. We look forward to helping you create memorable and successful sports seasons!
    <br>@copyright all rights reserved </p>
</div>
</body>
</html>
