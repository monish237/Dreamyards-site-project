<template >
  <a name = "top"></a>
  <div class = "header">
      <div class = "header-container">
        <a href = "#top">
          <img src = "./assets/logo.png" class = "logo header-content"/>
        </a>
        <div class = "header-content">
          <a href = "#top" style = "text-decoration: none" class = "header-content header-text"> HOME </a>
          <a href = "#apps" style = "text-decoration: none" class = "header-content header-text"> APP </a>
          <a href = "#about" style = "text-decoration: none" class = "header-content header-text"> ABOUT </a>
          <a href = "#privacy" style = "text-decoration: none" class = "header-content header-text"> PRIVACY </a>
          <a href = "https://mail.google.com/mail/u/0/?fs=1&tf=cm&source=mailto&su=Feedback+Mail&to=contactus@dreamyards.io">
            <a class = "header-content header-text"> CONTACT </a>
          </a>
        </div>
        <a href = "https://www.facebook.com/dreamyardsllc">
          <img src = "https://www.dreamyards.io/images/facebook.png" class = "twitter-header header-content"/>
        </a>
        <a href = "https://twitter.com/dream_yards">
          <img src = "https://www.dreamyards.io/images/twitter.png" class = "facebook-header header-content"/>
        </a>
      </div>
  </div>
  <div class = "app-icons-header">
    <div class = "infite-background-container">
      <div class = "infite-background"></div>
    </div>
    <a href = "https://apps.apple.com/us/app/kurious/id1515898989">
      <img src = "https://www.dreamyards.io/images/ios-badge.svg" class = "appstore store-banner-margin"/>
    </a>
    <a href = "https://play.google.com/store/apps/details?id=com.dreamyards.kurious">
      <img src = "https://www.dreamyards.io/images/google-play-badge.png" class = "googleplay store-banner-margin"/>
    </a>
  </div>
  <div class = "apps-container">
      <h2 class = "apps-title">Apps</h2>
      <a name = "apps"></a>
      <div>
        <img src = "https://www.dreamyards.io/images/kurious-phone.png" class = "phone" />
      </div>
      <p class = "app-paragraph-title">Kurious</p>
      <div class = "apps-text">
        <p class = "app-paragraph-text">Kurious is the perfect opportunity to encourage your little one to hone their reading skills within a bright and interactive learning environment. Download Kurious TODAY!
                                        <br>
                                        There are so many stories to explore in KURIOUS, the new interactive book reading platform from DreamYards!
                                        <br>
                                        At DreamYards, we know that reading is one of the best ways for kids to develop a lifelong love of learning and imagination. Anything is possible in a book: blast off to outer space, hike through the rainforest, build a brand-new invention, conduct a science experiment, and more. The books available within Kurious are designed to create a fun, engaging experience for kids while also helping them to become more confident and independent readers.</p>
      </div>
  </div>
  <div class = "app-icons-apps ">
    <a href = "https://apps.apple.com/us/app/kurious/id1515898989">
      <img src = "https://www.dreamyards.io/images/ios-badge.svg" class = "appstore-apps margin-up"/>
    </a>
    <a href = "https://play.google.com/store/apps/details?id=com.dreamyards.kurious">
      <img src = "https://www.dreamyards.io/images/google-play-badge.png" class = "googleplay-apps"/>
    </a>
  </div>
  <div class = "footer">
      <a name = "about"></a>
      <h1 class = "footer-title">About DreamYards</h1>
      <div class = "footer-address">
        <a href = "https://www.google.com/maps/place/739+Bryant+St,+San+Francisco,+CA+94107/@37.776906,-122.4031433,17z/data=!3m1!4b1!4m5!3m4!1s0x808f7fd54ec9cc5d:0x167b2e88d10b14be!8m2!3d37.7769018!4d-122.4009546"><img src = "https://www.dreamyards.io/images/location.png" class = "footer-pinpoint" /></a>
        <a href = "https://www.google.com/maps/place/739+Bryant+St,+San+Francisco,+CA+94107/@37.776906,-122.4031433,17z/data=!3m1!4b1!4m5!3m4!1s0x808f7fd54ec9cc5d:0x167b2e88d10b14be!8m2!3d37.7769018!4d-122.4009546" style = "text-decoration: none" class = "footer-address-text"> 739 Bryant St, San Francisco, CA</a>
      </div>
      <div class = "footer-description">
        <p class= "footer-description"> DreamYards was started as an idea born from the desire to make learning as much fun and an interactive experience for the kids. Dream Yards brings together a team of designers, programmers, musicians, artists and creative members collectively from across the globe with a prime focus to build innovative learning apps for kids. Our goal is inspired by the imaginative world of the kids; who we know is in dire need of such information and to unite their efforts to improve their presence and learning ability via user-friendly learning apps. Our team is continuously working to deliver a promising learning experience for kids combined with innovative technology.</p>
      </div>
  </div>
  <div>
    <div class = "bottom-footer-text">
      <a href = "#top" style = "text-decoration: none" class = "footer-content"> 2021 ⒸDreamYards  </a>
      <h3 class = "footer-content"> Privacy Policy </h3>
      <a href = "https://mail.google.com/mail/u/0/?fs=1&tf=cm&source=mailto&su=Feedback+Mail&to=contactus@dreamyards.io"><a class = "footer-content"> Contact </a></a>
      <a href = "https://www.facebook.com/dreamyardsllc">
        <img src = "./assets/facebook-logo.png" class = "facebook-footer header-content"/>
      </a>
      <a href = "https://twitter.com/dream_yards">
        <img src = "https://logos-world.net/wp-content/uploads/2020/04/Twitter-Logo.png" class = "twitter-footer header-content"/>
      </a>
    </div>
  </div>
</template>

<script>

</script>

<style>

  html{
    scroll-behavior: smooth;/*Adds scrolling effect*/
    width: 100%;
    margin: 0px;
    padding: 0px;
    overflow-x: hidden;/*Deletes Excess*/
  }
  a:hover{
    color: lightblue;
  }
  @keyframes slide {
    0% {
      transform: translate3d(0, 0, 0);
    }
    100% {
      transform: translate3d(-1717px /*Width*/, 0, 0); 
    }
  }
  .infite-background-container{
    overflow: hidden;
  }
  .infite-background{
    background: url("./assets/Dreamyards-homepage-First-Pic1.png") repeat-x;
    height: 500px;
    width: 300%;
    animation: slide 20s/*Loop time*/ linear infinite;
  }
  .app-icons-header{
    position: relative;
    padding-top: 5%;
  }
  .header-content{
    display: inline-block;
    padding-top: 0.9%;
  }
  .twitter-footer{
    display: inline-block;
    width: 25px;
    height: auto;
    margin-right: 15px;
  }
  .facebook-footer{
    display: inline-block;
    width: 17px;
    height: auto;
    margin-right: 15px;
  }
  .bottom-footer-text{
    text-align: center;
  }
  .footer-content{
    display: inline-block;
    margin-right: 250px;
    padding-top: 10px;
    font-family: 'Baloo Paaji', Monospace;
    font-size: 20px;
    color: #410094;
  }
  .app-icons-apps{
    padding-top:100px;
    text-align: center;
    position: relative;
    left: 12%;
  }
  .footer-description{
    width: 55%;
    display: inline-block;
    color: white;
    text-align: left;
    position: relative;
    left: 16%;
  }
  .footer-address{
    display: inline-block;
    left: 19%;
    padding-right: 200px;
  }
  .footer-address-text{
    color:white;
    font-weight:500;
    display: inline-block;
    margin: 15px;
    position: relative;
    left: 122%;
    bottom: 180px;
    
  }
  .footer-pinpoint{
    display: inline-block;
    position: relative;
    left: 122%;
    top: -150px;
  }
  .header-text{
    margin-right: 25px;
    font-family: 'Baloo Paaji', Monospace;
    font-size: 20px;
    color: #410094;
    position: relative;
    top: -20px;
    left: 20px;

  }
  .header-container{
    text-align: center;
    position: relative;
    left: 10px;
  }
  .apps-text{
    float: left;
    width: 30%;
  }
  .apps-container{
    padding-bottom: 200px;
  }
  .app-paragraph-text{
    width: 100%;
    text-align: left;
    font-family:	'Baloo Paaji', sans-serif;
    font-weight: lighter;
  }
  .app-paragraph-title{
    text-align: left;
    font-family: 'Baloo Paaji', Monospace;
    font-size: 30px;
    color: #410094;
  }
  .phone{
    float:left;
    width: 30%;
    padding-left: 20%;
  }
  .apps-title{
    font-family: 'Baloo Paaji', cursive;
    font-size: 40px;
    font-weight:700;
    color: #3F0069;
    padding-bottom: 30px;
  }
  .footer-title{
    font-family: 'Baloo Paaji', cursive;
    font-size: 20px;
    font-weight:700;
    text-align: center;
    color: #ffffff;
    padding-top: 25px;
    padding-bottom: 20px;
  }
  .facebook-header{
    position: relative;
    top: -10px;
    margin-left: 10px;

  }
  .twitter-header{
    position: relative;
    top: -10px;
    margin-left: 350px;
  }
  .header{
    position:fixed;
    left:0; 
    top:0;  
    width:100vw; 
    z-index:200; 
    height:100px; 
    background-color: white;
    border-style: solid bottom;
    border-width: 1px;
    scroll-behavior: smooth;
  }
  .logo{
    height: 70px;
    margin-right: 325px;
  }
  .headerpicture{
    background-size: cover;
    width: 101%;
    height: auto;
    margin-left: -8px;
  }
  .googleplay{
    float: right;
    position: relative;
    width:10%;
    height:100%;
    padding-right: 38%;
  }
  .appstore{
    float: left;
    position: relative;
    width:10%;
    height:100%;
    padding-left: 38%;
  }
  .store-banner-margin{
    position: relative;
    top: -80px;
    padding-bottom: -80px;
  }
  .googleplay-apps{
    position: relative;
    width:10%;
    height:100%;
    margin-left: 20px;
  }
  .appstore-apps{
    position: relative;
    width:10%;
    height:100%;
    padding-left: 40px;
  }
  .footer-title{
    font-family: 'Baloo Paaji', cursive;
    font-size: 35px;
    font-weight:700;
    color: rgb(255, 255, 255);
  }
  .footer{
    background-color: #3F0069;
    width: 100%;
    height: 100%;
  }
  body{
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }
</style>
