# Ex02 Commercial Website
## Date:13/05/2026
## NAME:PRASANNA I
## REG NO:212223220079

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

### HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MobileZone - Your Smartphone Store</title>
    <link rel="stylesheet" href="index.css">

</head>
<body>

    <header>
        <div class="logo">MobileZone</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Mobiles</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>


    <section id="home" class="hero">
        <h1>Latest Smartphones, Best Prices</h1>
        <p>Shop the latest iPhones, Samsung Galaxy, OnePlus & more at unbeatable prices.</p>
    </section>

    <section id="products" class="products">
        <h2>Our Top Mobiles</h2>
        <div class="product-container">
            <div class="product-card">
                <img src="iphone.jpeg" alt="iPhone 15 Pro">
                <h3>iPhone 15 Pro</h3>
                <p>₹1,29,900</p>
            </div>
            <div class="product-card">
                <img src="samsung.jpeg" alt="Samsung S24 Ultra">
                <h3>Samsung S24 Ultra</h3>
                <p>₹1,19,999</p>
            </div>
            <div class="product-card">
                <img src="onepluse.jpeg" alt="OnePluse">
                <h3>OnePlus 12</h3>
                <p>₹64,999</p>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <h2>About MobileZone</h2>
        <p>MobileZone is your trusted online store for the latest smartphones. 
           We offer 100% genuine products, exclusive deals, and fast delivery across India. 
           Our mission is to provide high-quality smartphones at competitive prices, ensuring a smooth shopping experience. 
           We partner directly with top brands to bring you authentic devices and accessories. 
           Customer satisfaction is our top priority, and we continuously work to improve our service.</p>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:support@mobilezone.com">support@mobilezone.com</a></p>
        <p>Phone: +91 8778719448</p>
        <p>Address: MobileZone HQ, Chennai, Tamil Nadu, India</p>
    </section>


    <footer>
        <div class="socials">
            <a href="#">Facebook</a> |
            <a href="#">Instagram</a> |
            <a href="#">Twitter</a>
        </div>
        <p>© PRASANNA I [212223220079]</p>
    </footer>

</body>
</html>
```

### CSS
```

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
    background: #f9f9f9;
    color: #333;
    scroll-behavior: smooth;
}

header {
    background: #111;
    color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    position: sticky;
    top: 0;
    z-index: 1000;
}

.logo {
    font-size: 1.5em;
    font-weight: bold;
    color: #f4b400;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #f4b400;
}


.hero {
    background: url('bg-image.jpg') center/cover no-repeat;
    color: white;
    text-align: center;
    padding: 80px 20px;
}


.products {
    padding: 40px;
    text-align: center;
}

.product-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.product-card {
    background: #fff;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    width: 200px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.product-card:hover {
    transform: scale(1.05);
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}

.product-card img {
    width: 100%;
    height: 250px; 
    object-fit: contain; 
    background: #fff; 
    border-radius: 5px;
    padding: 1px;
}

.about, .contact {
    padding: 40px;
    text-align: center;
    background: white;
    margin: 20px;
    border-radius: 8px;
}

footer {
    background: #222;
    color: #ccc;
    text-align: center;
    padding: 15px;
}

footer .socials a {
    color: #ccc;
    margin: 0 5px;
    text-decoration: none;
}

footer .socials a:hover {
    color: #f4b400;
}

```
## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/23831ffb-6b15-41bf-9360-9699568f6bf6" />




## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
