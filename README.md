<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - Varloid Ent</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #ffffff;
            color: #000000;
        }
        header {
            background-color: #000000;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #000000;
        }
        nav a {
            color: #ffffff;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #333333;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1920x1080');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #ffffff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        .hero h2 {
            font-size: 2em;
            text-align: center;
        }
        .content {
            padding: 20px;
            text-align: center;
        }
        .product {
            display: inline-block;
            width: 30%;
            margin: 10px;
            vertical-align: top;
            background-color: #f4f4f4;
            border: 1px solid #dddddd;
            padding: 10px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        .product h3 {
            font-size: 1.2em;
        }
        footer {
            background-color: #000000;
            color: #ffffff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Varloid Ent</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="hero">
        <h2>Your Source for Trending TikTok Products</h2>
    </div>
    <div class="content">
        <h2>Featured Products</h2>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product 1">
            <h3>Genius Kitchen Gadget</h3>
            <p>Discover the kitchen tool everyone's talking about.</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product 2">
            <h3>Eco-Friendly Essentials</h3>
            <p>Switch to sustainable living with these must-haves.</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product 3">
            <h3>Skincare Secret</h3>
            <p>Achieve glowing skin with this viral skincare find.</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2023 Varloid Ent. All rights reserved.</p>
    </footer>
</body>
</html>
