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
!DOCTYPE html>
<html lang="en">
<head>
    <me<ta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY BUISNESS - COMMERCIAL WEBSITE</title>
    <style>
       
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #407e09;
            color: #3b0525;
        }
        header {
            background: #0b2633;
            color: rgb(230, 246, 10);
            padding: 15px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            background: #164154;
            padding: 10px;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: rgb(18, 70, 9);
            text-decoration: none;
            font-size: 18px;
            padding: 8px 15px;
            transition: 0.3s;
        }
        nav ul li a:hover {
            background: #b6d00d;
            border-radius: 5px;
        }
        .section {
            padding: 40px;
            text-align: center;
            background: rgb(11, 136, 129);
            margin: 20px auto;
            width: 80%;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(60, 17, 52, 0.1);
        }
        button {
            background: #0a5fb0;
            color: rgb(19, 53, 133);
            padding: 12px 20px;
            border: none;
            cursor: pointer;
            font-size: 18px;
            border-radius: 5px;
            transition: 0.3s;
        }
        button:hover {
            background: #24620b;
        }
        footer {
            background: #831674;
            color: rgb(8, 97, 133);
            text-align: center;
            padding: 15px;
            margin-top: 20px;
            font-size: 14px;
        }
        
        .contact-form {
            display: flex;
            flex-direction: column;
            width: 60%;
            margin: auto;
            text-align: left;
        }
        .contact-form label {
            font-weight: bold;
            margin: 5px 0;
        }
        .contact-form input, .contact-form textarea {
            padding: 8px;
            margin-bottom: 10px;
            width: 100%;
            border: 1px solid #385f51;
            border-radius: 5px;
        }
        
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                text-align: center;
            }
            .section {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <header>
        IT SERVICES
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#account">Account</a></li>
        </ul>
    </nav>

    <section id="home" class="section">
        <h2>"Upgrade your business with cutting-edge IT solutions—secure, scalable, and reliable."</h2>
        <p>"Your success, powered by technology—custom IT solutions built for growth."</p>
        <button onclick="alert('Welcome to My Business!')">Learn More</button>
    </section>

    <section id="services" class="section">
        <h2>Our Services</h2>
        <p>We offer a various services to enhance the experience of shopping and provide value-added benefits:</p>
        <ul>
            <li><strong>Discounts:</strong> Get amazing deals and exclusive discounts on your favorite products.</li>
            <li><strong>Device Exchange:</strong> Trade in your old gadgets for exciting new ones at unbeatable prices.</li>
            <li><strong>No-Cost EMI:</strong> Buy now and pay later with zero-interest installment plans.</li>
            <li><strong>Exclusive Online Coupons:</strong> Save more with our limited-time promotional offers.</li>
        </ul>
        <button onclick="alert('Explore our amazing services!')">View All Services</button>
    </section>

    <section id="about" class="section">
        <h2>About Our Company</h2>
        <p>We deliver innovative IT solutions tailored to your business needs.Empowering businesses with secure, scalable, and cutting-edge technology solutions.Your trusted IT partner—delivering expertise, innovation, and reliability."</p>
        <p>We simplify IT, so you can focus on what matters—growing your business.</p>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>We'd love to hear from you! Reach out to us for any queries, feedback, or assistance.</p>
        <form class="contact-form">
            <label>Name:</label>
            <input type="text" placeholder="Enter your name" required>
            <label>Email:</label>
            <input type="email" placeholder="Enter your email" required>
            <label>Message:</label>
            <textarea placeholder="Your message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <section id="account" class="section">
        <h2>User Account Management</h2>
        <p>Login to manage your account, track your orders, and personalize your preferences.</p>
        <button onclick="login()">Login</button>
    </section>

    <footer>
        <p>&copy; 2025 My Business. All Rights Reserved.</p>
    </footer>

    <script>
        function login() {
            let username = prompt("Enter your username:");
            if (username) {
                alert("Welcome, " + username + "!");
            } else {
                alert("Login canceled.");
            }
        }
    </script>

</body>
</html>


## OUTPUT
## C:/Users/admin/Pictures/Saved%20Pictures/OneDrive/Desktop/web%20aplicaton/.vscode/web%20APPLICATION%201.html#account
## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
