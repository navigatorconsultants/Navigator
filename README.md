# Navigator Consultants
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navigator Consultants – Redefining Success</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: url('hero.jpg') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        section {
            padding: 40px 20px;
            text-align: center;
        }
        .services img {
            width: 300px;
            border-radius: 10px;
            margin: 20px;
        }
        .contact-form input, .contact-form textarea {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            color: white;
            background: #007BFF;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>

<body>

    <!-- Hero Section -->
    <header>
        <h1>Navigator Consultants</h1>
        <p>Redefining Business Success with Innovation and Strategy</p>
    </header>

    <!-- About Us Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>We specialize in delivering strategic business solutions to empower your growth and success.</p>
    </section>

    <!-- Our Services Section -->
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div>
            <img src="service1.jpg" alt="Service 1">
            <p>Business Strategy & Consulting</p>
        </div>
        <div>
            <img src="service2.jpg" alt="Service 2">
            <p>Market Analysis & Insights</p>
        </div>
        <div>
            <img src="service3.jpg" alt="Service 3">
            <p>Digital Transformation</p>
        </div>
    </section>

    <!-- Contact Us Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form action="mailto:info@navigatorconsultants.com" method="POST" enctype="text/plain" class="contact-form">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit" class="btn">Send Message</button>
        </form>
        <p>Email us at: <a href="mailto:info@navigatorconsultants.com">info@navigatorconsultants.com</a></p>
    </section>

</body>

</html>
