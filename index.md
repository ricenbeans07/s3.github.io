
<html lang="en">
<head>

  <title>The Order - #1 online food delivery app</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"></script>
</head>

<style>
  
.a {
  background-color: #000000
</style>



<!DOCTYPE html>
<html>
<title></title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Oswald">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open Sans">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
h1,h2,h3,h4,h5,h6 {font-family: "Oswald"}
body {font-family: "Open Sans"}
</style>
<body class="w3-light-grey">
<body>

  <!-- Header -->
  <header class="w3-container w3-center w3-padding-48 w3-red">
    <h1 class="w3-xxxlarge"><b> The Order</b></h1>
    <h2><span class="w3-tag">Made In Ranchi</span></h2>
  </header>

<button onclick="getLocation()">Turn on Location</button>

<p id="demo"></p>

<script>
var x = document.getElementById("demo");

function getLocation() {
  if (navigator.geolocation) {
    navigator.geolocation.getCurrentPosition(showPosition, showError);
  } else { 
    x.innerHTML = "Geolocation is not supported by this browser.";
  }
}

function showPosition(position) {
  x.innerHTML = "Latitude: " + position.coords.latitude + 
  "<br>Longitude: " + position.coords.longitude;
}

function showError(error) {
  switch(error.code) {
    case error.PERMISSION_DENIED:
      x.innerHTML = "User denied the request for Geolocation."
      break;
    case error.POSITION_UNAVAILABLE:
      x.innerHTML = "Location information is unavailable."
      break;
    case error.TIMEOUT:
      x.innerHTML = "The request to get user location timed out."
      break;
    case error.UNKNOWN_ERROR:
      x.innerHTML = "An unknown error occurred."
      break;
  }
}
</script>


<div class="container">
<p>Restraunts :</p>
</div>

<style>

</style>
  
<div class="container">
  <div class="row">
    <div class="col-sm-4">
    	<img src="https://b.zmtcdn.com/data/pictures/3/18388053/3d806806f2728ba207b4b2f325032a50.jpg" width="300" height="200">
      <h2>The Best</h2>
      <a href="file:///E:/Pages/fd/The%20Best.html">Open Menu</a>
      <p>The Best is a family friendly vegetarian restraunt 
      which has a large menu to chose from</p>
    </div>
    <div class="col-sm-4">
    	<img src="https://res.cloudinary.com/swiggy/image/upload/f_auto,q_auto,fl_lossy/ng0sp3z6yskznvbnabmv" width="300" height="200">
      <h2>Fassos</h2>
      <a href="file:///E:/Pages/fd/Fassos.html">Open Menu</a>
      <p>An Indian Fast food chain restraunt which offers 
      a great amounts of wraps and Plates.</p>
    </div>
    <div class="col-sm-4">
    	<img src="https://res.cloudinary.com/swiggy/image/upload/fl_lossy,f_auto,q_auto,w_508,h_320,c_fill/jskj3ofhhtjizlvxlqvq" width="300" height="200">
      <h2>Ruin House</h2>
      <a href="file:///E:/Pages/fd/Ruin%20House.html">Open Menu</a>
      <p>Classy</p>
    </div>
     <div class="col-sm-4">
    	<img src="https://download.logo.wine/logo/KFC/KFC-Logo.wine.png" width="300" height="200">
      <h2>KFC</h2>
      <a href="file:///E:/Pages/fd/KFC.html#menu">Open Menu</a>
        <p>Colonel's wings near you. Order now!</p>
    </div>
    <div class="col-sm-4">
    	<img src="https://www.southgate-plaza.com/wp-content/uploads/2018/03/dominos.jpg" width="300" height="200">
      <h2>Domino's Pizza</h2>
      <a href="file:///E:/Pages/fd/Domino's%20Pizza.html">Open Menu</a>
      <p>Surplus amounts of pizza, sides, beverages.</p>
    </div>
    <div class="col-sm-4">
    	<img src="https://res.cloudinary.com/swiggy/image/upload/fl_lossy,f_auto,q_auto,w_508,h_320,c_fill/ae4jbmd4rd9sxvewf0jz" width="300" height="200">
      <h2>Dumpling Momo</h2>
      <a href="file:///E:/Pages/fd/Dumpling%20Momos.html">Open Menu </a>
      <p>A taste haven for momo lovers.</p>
    </div>

     </div>
</div>

</body>
</html>
