# Watch Shop Website Source Code

## index.html

``` html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Luxury Watch</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
<h1>Luxury Watch</h1>
<nav>
<a href="index.html">Home</a>
<a href="shop.html">Shop</a>
<a href="product.html">Products</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
</nav>
</header>

<section class="hero">
<h2>Premium Watches Collection</h2>
<p>Luxury, Style, Precision.</p>
<a class="btn" href="shop.html">Shop Now</a>
</section>

<footer>
<p>©2026 Luxury Watch</p>
</footer>
</body>
</html>
```

## shop.html

``` html
<!DOCTYPE html>
<html>
<head>
<title>Shop</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<h1>Our Collection</h1>

<div class="products">
<div class="card">
<img src="images/watch1.jpg">
<h3>Rolex Classic</h3>
<p>$850</p>
<a href="product.html">View</a>
</div>

<div class="card">
<img src="images/watch2.jpg">
<h3>Omega</h3>
<p>$720</p>
<a href="product.html">View</a>
</div>

<div class="card">
<img src="images/watch3.jpg">
<h3>Cartier</h3>
<p>$990</p>
<a href="product.html">View</a>
</div>
</div>
</body>
</html>
```

## product.html

``` html
<!DOCTYPE html>
<html>
<head>
<title>Product</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<h1>Rolex Classic</h1>
<img src="images/watch1.jpg" width="350">
<p>Premium Swiss movement with sapphire crystal glass, stainless steel body, and 5-year warranty.</p>
<h2>$850</h2>
<button>Add to Cart</button>
</body>
</html>
```

## about.html

``` html
<!DOCTYPE html>
<html>
<head>
<title>About</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<h1>About Luxury Watch</h1>
<p>Luxury Watch offers premium timepieces from the world's most prestigious brands.</p>
</body>
</html>
```

## contact.html

``` html
<!DOCTYPE html>
<html>
<head>
<title>Contact</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<h1>Contact Us</h1>
<form>
<input type="text" placeholder="Your Name">
<input type="email" placeholder="Email">
<textarea placeholder="Message"></textarea>
<button>Send</button>
</form>
</body>
</html>
```

## style.css

``` css
body{font-family:Arial;margin:0;background:#111;color:#fff}
header{background:#000;padding:20px;text-align:center}
nav a{color:#fff;margin:15px;text-decoration:none}
.hero{height:90vh;display:flex;flex-direction:column;justify-content:center;align-items:center;background:#222}
.btn{padding:15px 35px;background:gold;color:#000;text-decoration:none;font-weight:bold}
.products{display:flex;justify-content:center;gap:30px;padding:50px;flex-wrap:wrap}
.card{background:#222;padding:20px;border-radius:10px;text-align:center}
.card img{width:220px}
input,textarea{display:block;width:300px;padding:12px;margin:15px auto}
button{padding:12px 25px;background:gold;border:none;cursor:pointer}
```
