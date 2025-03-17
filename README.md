# Ex02 Commercial Website
## Date:

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
```
index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechNova Solutions</title>
    <link rel="stylesheet" href="style.css">
    <style>
        html {
            scroll-behavior: smooth;
        }
    </style>
    
</head>
<body>
    <header>
        <h1>TechNova Solutions</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#account">User Account</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to TechNova Solutions</h2>
        <p>Empowering businesses with AI, cloud, and web solutions.</p>
        <img src="tech.png" alt="TechNova Solutions">
    </section>

    <section id="products">
        <h2>Our Products & Services</h2>
        <div class="product">
            <h3>AI Chatbots</h3>
            <p>Automate customer service with AI-powered chatbots.</p>
        </div>
        <div class="product">
            <h3>Web & Mobile Development</h3>
            <p>Custom-built websites and mobile applications.</p>
        </div>
        <div class="product">
            <h3>Cybersecurity Solutions</h3>
            <p>Secure your business with cutting-edge security solutions.</p>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>TechNova Solutions is a startup dedicated to innovative tech services, bridging businesses with technology.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: contact@technovasolutions.com</p>
        <p>Phone: +123 456 7890</p>
    </section>

    <section id="account">
        <h2>User Account</h2>
        <p>Login or sign up to access exclusive services.</p>
        <button>Login</button>
        <button>Sign Up</button>
    </section>

    <footer>
        <p>Follow us on:</p>
        <a href="#">Facebook</a> | 
        <a href="#">Twitter</a> | 
        <a href="#">LinkedIn</a>
        <p>&copy; 2025 TechNova Solutions. All rights reserved.</p>
    </footer>
</body>
</html>

style.css

/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f4f4f4;
    color: #333;
    display: flex;
    flex-direction: column;
}

/* Header */
header {
    background-color: #0073e6;
    color: white;
    padding: 20px;
    text-align: center;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

/* Navigation */
nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    background: #005bb5;
    padding: 10px;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #ffcc00;
}

/* Full Screen Sections */
section {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 20px;
}

/* Section Background Colors */
#home { background-color: #e3f2fd; }
#products { background-color: #fbe9e7; }
#about { background-color: #e8f5e9; }
#contact { background-color: #f3e5f5; }
#account { background-color: #ede7f6; }

/* Product Section */
#products {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.product {
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 300px;
    text-align: center;
    transition: transform 0.3s ease-in-out;
}

.product:hover {
    transform: scale(1.05);
}

/* User Account Buttons */
button {
    padding: 10px 20px;
    background: #0073e6;
    color: white;
    border: none;
    cursor: pointer;
    margin: 10px;
    transition: 0.3s;
}

button:hover {
    background: #005bb5;
}

/* Footer */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 20px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

footer a {
    color: #ffcc00;
    text-decoration: none;
    margin: 0 10px;
}

footer a:hover {
    text-decoration: underline;
}

/* Responsive Design */
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
        text-align: center;
    }

    #products {
        flex-direction: column;
        align-items: center;
    }
}
```
## OUTPUT

![alt text](<Screenshot (82).png>)

![alt text](<Screenshot (83).png>)

![alt text](<Screenshot (84).png>)

![alt text](<Screenshot (85).png>)

![alt text](<Screenshot (86).png>)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
