<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  margin: 8px;
}

.about-section {
  padding: 50px;
  text-align: center;
  background-color: #474e5d;
  color: white;
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}
</style>
</head>
<body>

<div class="about-section">
  <h1>About Us</h1>
  <p>SV-Restaurant Hotels is a chain of luxury hotels and a subsidiary of the Indian Hotels 
    Company Limited,headquartered at Express Towers, Nariman Point, Mumbai. Incorporated 
    by the founder of the Tata Group, Jamsetji Tata,the company is a part of the 
    Tata Group, one of India's largest business conglomerates.</p>
</div>

  <div class="column">
    <div class="card">
      <img src="Sasi.jpg" alt="Mike" style="width: 100%;">
      <div class="container">
        <h2>Sasi</h2>
        <p class="title">Owner</p>
        <p>We came to SV Restaurant after a 14-hr long drive and it was probably the best place we 
        could have found to unwind! From mouth-watering food to exceptional service
        We trieds his best to show us a great time.</p>
        <p>sasisasi9766@gmail.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="card">
      <img src="photo1.jpg" alt="John" width="360px">
      <div class="container">
        <h2>Varshit</h2>
