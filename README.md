<!DOCTYPE html>
<html>
<head>
<title>Add Car</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>Add Car</h1>

<nav>
<a href="index.html">Home</a>
<a href="add-car.html">Add Car</a>
</nav>

</header>

<form id="addCarForm">

<input type="text" id="name" placeholder="Car Name" required>

<input type="number" id="year" placeholder="Year" required>

<input type="text" id="price" placeholder="Price" required>

<input type="text" id="images" placeholder="Image URLs (comma separated)" required>

<input type="text" id="contact" placeholder="Seller Contact" required>

<button type="submit">Add Car</button>

</form>

<script src="script.js"></script>

</body>
</html>
