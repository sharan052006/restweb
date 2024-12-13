# Ex.07 Restaurant Website
## Date:

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<html>
<head>
    <title>Frost & Whisk</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #e6f7ff;
            scroll-behavior: smooth;
        }

        header {
            background-color: #1667b2;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        header img {
            width: 100px;
            height: auto;
            margin-top: 10px;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            text-align: center;
            background-color: #06111B;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        .banner {
            background-image: url(image.png);
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            color: rgb(4, 4, 4);
            text-align: center;
            padding: 125px 20px;
        }

        .banner h1 {
            font-size: 3rem;
        }

        .sections {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            text-align: center;
            flex-wrap: wrap;
        }

        .section {
            background-color: #93bbea;
            border: 1px solid #ddd;
            padding: 20px;
            margin: 10px;
            flex: 1;
            max-width: 300px;
        }

        .section img {
            width: 100%;
            height: auto;
        }

        footer {
            background-color: #06111B;
            color: white;
            text-align: center;
        }

        .highlight {
            color: orange;
            font-weight: bold;
        }

        .about-section {
            background-color: #e6f7ff;
            padding: 20px;
            text-align: center;
        }

        .menu-section {
            text-align: center;
            padding: 20px;
        }

        .menu-items {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .menu-item {
            width: 200px;
            text-align: center;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 10px;
        }

        .menu-item img {
            width: 100%;
            border-radius: 5px;
        }

        .administration-section {
            text-align: center;
            padding: 20px;
        }

        .administration-members {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .administration-member {
            width: 200px;
            text-align: center;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 10px;
        }

        .administration-member img {
            width: 100%;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<header>
    <h1>Frost & Whisk</h1>
    <img src="logoooo...jpg" alt="Frost & Whisk Logo">
</header>

<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#administration">Administration</a></li>
    </ul>
</nav>

<div id="home" class="banner">
    <p>.</p>
</div>

<section id="about" class="about-section">
    <h1>About Us</h1>
    <h3>Welcome to Frost and Whisk, where we blend the creamy delight of ice creams with the elegance of continental desserts. Indulge in our innovative creations and timeless favorites, crafted to satisfy every sweet craving. Discover dessert like never before!</h3>
</section>

<section class="sections">
    <div class="section">
        <h2>Our New Menu</h2>
        <p>Explore our delicious new offerings, freshly made every day.</p>
    </div>

    <div class="section">
        <h2>Book a Table</h2>
        <p>Reserve your spot now and enjoy an unforgettable dining experience.</p>
    </div>

    <div class="section">
        <h2>Opening Hours</h2>
        <p>
            <span class="highlight">Mon-Fri:</span> 2pm - 10pm<br>
            <span class="highlight">Sat:</span> 2pm - 11pm<br>
            <span class="highlight">Sun:</span> 2pm - 9pm
        </p>
    </div>
</section>

<section id="menu" class="menu-section">
    <h2>Our Menu</h2>
    <div class="menu-items">
        <div class="menu-item">
            <img src="sundae.jpg" alt="Ice Cream Sundae">
            <h3>Ice Cream Sundae</h3>
            <p>Rs.250</p>
        </div>
        <div class="menu-item">
            <img src="lava.jpg" alt="Chocolate Lava Cake">
            <h3>Chocolate Lava Cake</h3>
            <p>Rs.120</p>
        </div>
        <div class="menu-item">
            <img src="fruit.jpeg" alt="Fruit Parfait">
            <h3>Fruit Parfait</h3>
            <p>Rs.350</p>
        </div>
        <div class="menu-item">
            <img src="cheese.jpg" alt="Continental Cheesecake">
            <h3>Continental Cheesecake</h3>
            <p>Rs.150</p>
        </div>
    </div>
</section>

<section id="administration" class="administration-section">
    <h2>Administration</h2>
    <div class="administration-members">
        <div class="administration-member">
            <img src="monishhhhhhhhh.jpg" alt="MD">
            <h3>MONISH I</h3>
            <h3>MD</h3>
        </div>
        <div class="administration-member">
            <img src="sharannnnnnnnnnnnnnnnnnnnnnnnnnnnnn.jpg" alt="CEO">
            <h3>SHARAN I</h3>
            <h3>CEO</h3>
        </div>
        <div class="administration-member">
            <img src="shiyammmmmmmm.jpg" alt="MANAGER">
            <h3>SHIYAM</h3>
            <h3>MANAGER</h3>
        </div>
        <div class="administration-member">
            <img src="prajan.jpg" alt="ASSISTANT-MANAGER">
            <h3>PRAJAN</h3>
            <h3>ASSISTANT MANAGER</h3>
        </div>
    </div>
</section>

<footer>
    <p>Website developed by Sharan I 24010956</p>
</footer>

</body>
</html>

 

```

## OUTPUT:

![alt text](<Screenshot (63).png>)
![alt text](<Screenshot (64).png>)
![alt text](<Screenshot (65).png>)  



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
