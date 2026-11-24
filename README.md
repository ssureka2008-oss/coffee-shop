<!DOCTYPE html>
<html>
<head>
    <title>My Coffee Shop</title>
    <style>
        body {
            margin: 0;
            font-family: Arial;
            background-color: #f5e6d3;
            text-align: center;
        }

        header {
            background-color: #4b2e20;
            color: white;
            padding: 20px;
        }

        nav {
            background-color: #8b5e3c;
            padding: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 20px;
            font-weight: bold;
        }

        section {
            padding: 35px;
        }

        .menu {
            background-color: white;
            margin: 15px auto;
            padding: 15px;
            width: 60%;
            border-radius: 10px;
        }

        footer {
            background-color: #4b2e20;
            color: white;
            padding: 15px;
        }
    </style>
</head>

<body>

<header>
    <h1>☕ Coffee Corner</h1>
    <p>Fresh Coffee, Happy Moments!</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <h2>Welcome to Coffee Corner</h2>
    <p>Enjoy the best coffee with a relaxing atmosphere.</p>
    <img src="https://placehold.co/600x250/8b5e3c/ffffff?text=Coffee+Corner"
         width="60%" alt="Coffee shop">
</section>

<section id="about">
    <h2>About Us</h2>
    <p>We serve delicious coffee made with fresh
       ingredients and love.</p>
</section>

<section id="menu">
    <h2>Our Coffee Menu</h2>

    <div class="menu">
        <h3>Espresso</h3>
        <p>Price: ₹100</p>
    </div>

    <div class="menu">
        <h3>Cappuccino</h3>
        <p>Price: ₹150</p>
    </div>

    <div class="menu">
        <h3>Cold Coffee</h3>
        <p>Price: ₹120</p>
    </div>

    <div class="menu">
        <h3>Latte</h3>
        <p>Price: ₹180</p>
    </div>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Email: coffeecorner@gmail.com</p>
    <p>Phone: 9876543210</p>
    <a href="mailto:coffeecorner@gmail.com">
        Send Email
    </a>
</section>

<footer>
    <p>© 2026 Coffee Corner. All Rights Reserved.</p>
</footer>

</body>
</html>