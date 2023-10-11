<!DOCTYPE html>
<html>
<head>
  <title>The Band</title>
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <style>
    /* Add your custom CSS styles here */
  </style>
</head>
<body>

<!-- Navbar -->
<div class="w3-top">
  <div class="w3-bar w3-black w3-card">
    <a class="w3-bar-item w3-button w3-padding-large" href="#home">Home</a>
    <a class="w3-bar-item w3-button w3-padding-large" href="#about">About</a>
    <a class="w3-bar-item w3-button w3-padding-large" href="#tour">Tour</a>
    <a class="w3-bar-item w3-button w3-padding-large" href="#contact">Contact</a>
  </div>
</div>

<!-- Header -->
<header class="w3-container w3-center w3-padding-32">
  <h1><b>The Band</b></h1>
  <p>Welcome to our website!</p>
</header>

<!-- Band Members -->
<div class="w3-container w3-padding-64" id="band">
  <h2 class="w3-center">The Band Members</h2>
  <div class="w3-row-padding w3-padding-32" style="margin:0 -16px">
    <div class="w3-third w3-margin-bottom">
      <img src="img_bandmember.jpg" alt="Band Member" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <h3>John Doe</h3>
        <p class="w3-opacity">Lead Guitar</p>
        <p>Some text about John Doe. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <p><button class="w3-button w3-black w3-margin-bottom">Contact</button></p>
      </div>
    </div>
    <div class="w3-third w3-margin-bottom">
      <img src="img_bandmember.jpg" alt="Band Member" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <h3>Jane Smith</h3>
        <p class="w3-opacity">Bass Guitar</p>
        <p>Some text about Jane Smith. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <p><button class="w3-button w3-black w3-margin-bottom">Contact</button></p>
      </div>
    </div>
    <div class="w3-third w3-margin-bottom">
      <img src="img_bandmember.jpg" alt="Band Member" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <h3>Mike Johnson</h3>
        <p class="w3-opacity">Drums</p>
        <p>Some text about Mike Johnson. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <p><button class="w3-button w3-black w3-margin-bottom">Contact</button></p>
      </div>
    </div>
  </div>
</div>

<!-- Tour Dates -->
<div class="w3-container w3-light-grey w3-padding-64" id="tour">
  <h2 class="w3-center">Tour Dates</h2>
  <p class="w3-center w3-large">Upcoming tour dates for The Band:</p>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-third">
      <h3>London</h3>
      <p class="w3-opacity">Fri 27 Nov 2022</p>
      <p>Some text about the concert in London. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      <p><button class="w3-button w3-black w3-margin-bottom">Buy Tickets</button></p>
    </div>
    <div class="w3-third">
      <h3>Paris</h3>
      <p class="w3-opacity">Sat 28 Nov 2022</p>
      <p>Some text about the concert in Paris. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      <p><button class="w3-button w3-black w3-margin-bottom">Buy Tickets</button></p>
    </div>
    <div class="w3-third">
      <h3>Tokyo</h3>
      <p class="w3-opacity">Sun 29 Nov 2022</p>
      <p>Some text about the concert in Tokyo. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      <p><button class="w3-button w3-black w3-margin-bottom">Buy Tickets</button></p>
    </div>
  </div>
</div>

<!-- Contact Section -->
<div class="w3-container w3-padding-64" id="contact">
  <h2 class="w3-center">Contact</h2>
  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-half">
      <p>Drop us a message and we'll get back to you as soon as possible.</p>
      <form action="/action_page.php" target="_blank">
        <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
        <input class="w3-input w3-section w3-border" type="text" placeholder="Email" required name="Email">
        <input class="w3-input w3-section w3-border" type="text" placeholder="Subject" required name="Subject">
        <input class="w3-input w3-section w3-border" type="text" placeholder="Message" required name="Message">
        <button class="w3-button w3-black w3-margin-bottom" type="submit">Send Message</button>
      </form>
    </div>
    <div class="w3-half">
      <p>Connect with us on social media:</p>
      <a href="#" class="w3-button w3-black w3-margin-bottom"><i class="fa fa-facebook-official"></i> Facebook</a>
      <a href="#" class="w3-button w3-black w3-margin-bottom"><i class="fa fa-instagram"></i> Instagram</a>
      <a href="#" class="w3-button w3-black w3-margin-bottom"><i class="fa fa-snapchat"></i> Snapchat</a>
      <a href="#" class="w3-button w3-black w3-margin-bottom"><i class="fa fa-pinterest-p"></i> Pinterest</a>
      <a href="#" class="w3-button w3-black w3-margin-bottom"><i class="fa fa-twitter"></i> Twitter</a>
      <a href="#" class="w3-button w3-black w3-margin-bottom"><i class="fa fa-linkedin"></i> LinkedIn</a>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-center w3-opacity">
  <div class="w3-xlarge w3-padding-32">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>
</footer>

</body>
</html>
