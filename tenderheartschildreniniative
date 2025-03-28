<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tender Hearts Children Initiative | Helping Orphans in Uganda</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Global Styles */
        :root {
            --primary: #e74c3c;
            --secondary: #3498db;
            --dark: #2c3e50;
            --light: #ecf0f1;
            --accent: #f39c12;
            --success: #27ae60;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }

        a {
            text-decoration: none;
            color: var(--secondary);
            transition: all 0.3s ease;
        }

        a:hover {
            color: var(--primary);
        }

        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .btn {
            display: inline-block;
            padding: 12px 25px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s ease;
            text-align: center;
        }

        .btn:hover {
            background: #c0392b;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .btn-secondary {
            background: var(--secondary);
        }

        .btn-secondary:hover {
            background: #2980b9;
        }

        .btn-accent {
            background: var(--accent);
        }

        .btn-accent:hover {
            background: #e67e22;
        }

        .section-title {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
            color: var(--dark);
            text-align: center;
            position: relative;
            padding-bottom: 15px;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: var(--primary);
        }

        .section-padding {
            padding: 80px 0;
        }

        .text-center {
            text-align: center;
        }

        /* Header */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }

        .logo {
            display: flex;
            align-items: center;
        }

        .logo img {
            height: 50px;
            margin-right: 10px;
        }

        .logo-text h1 {
            font-size: 1.5rem;
            color: var(--primary);
        }

        .logo-text span {
            font-size: 0.9rem;
            color: var(--dark);
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 30px;
        }

        nav ul li a {
            color: var(--dark);
            font-weight: 600;
            position: relative;
        }

        nav ul li a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--primary);
            transition: width 0.3s ease;
        }

        nav ul li a:hover::after {
            width: 100%;
        }

        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 1.5rem;
            color: var(--dark);
            cursor: pointer;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1526666923127-b2970f64b422?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            text-align: center;
            color: white;
            margin-top: 80px;
        }

        .hero-content {
            max-width: 800px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            line-height: 1.2;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }

        .hero-btns {
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        /* About Section */
        .about {
            background-color: white;
        }

        .about-content {
            display: flex;
            align-items: center;
            gap: 50px;
            margin-top: 50px;
        }

        .about-img {
            flex: 1;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .about-img img {
            width: 100%;
            height: auto;
            display: block;
        }

        .about-text {
            flex: 1;
        }

        .about-text h3 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--dark);
        }

        .about-text p {
            margin-bottom: 20px;
        }

        .stats {
            display: flex;
            justify-content: space-between;
            margin-top: 30px;
        }

        .stat-item {
            text-align: center;
        }

        .stat-number {
            font-size: 2.5rem;
            font-weight: bold;
            color: var(--primary);
            margin-bottom: 5px;
        }

        .stat-label {
            font-size: 1rem;
            color: var(--dark);
        }

        /* Programs Section */
        .programs {
            background-color: var(--light);
        }

        .programs-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }

        .program-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .program-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
        }

        .program-img {
            height: 200px;
            overflow: hidden;
        }

        .program-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }

        .program-card:hover .program-img img {
            transform: scale(1.1);
        }

        .program-content {
            padding: 25px;
        }

        .program-content h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--dark);
        }

        /* Donate Section */
        .donate {
            background: linear-gradient(rgba(44, 62, 80, 0.9), rgba(44, 62, 80, 0.9)), url('https://images.unsplash.com/photo-1532629345422-7515f3d16bb6?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
            color: white;
            text-align: center;
        }

        .donate .section-title {
            color: white;
        }

        .donate .section-title::after {
            background: var(--accent);
        }

        .donate p {
            max-width: 700px;
            margin: 0 auto 40px;
            font-size: 1.1rem;
        }

        .donate-options {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
            margin-top: 40px;
        }

        .donate-option {
            background: white;
            padding: 30px;
            border-radius: 10px;
            width: 280px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .donate-option:hover {
            transform: translateY(-10px);
        }

        .donate-option i {
            font-size: 3rem;
            color: var(--primary);
            margin-bottom: 20px;
        }

        .donate-option h3 {
            color: var(--dark);
            margin-bottom: 15px;
        }

        .donate-option p {
            color: #666;
            margin-bottom: 20px;
            font-size: 0.9rem;
        }

        /* Gallery Section */
        .gallery {
            background-color: white;
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 50px;
        }

        .gallery-item {
            position: relative;
            border-radius: 10px;
            overflow: hidden;
            height: 250px;
        }

        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }

        .gallery-item:hover img {
            transform: scale(1.1);
        }

        .gallery-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(231, 76, 60, 0.8);
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .gallery-item:hover .gallery-overlay {
            opacity: 1;
        }

        .gallery-overlay i {
            color: white;
            font-size: 2rem;
        }

        /* Testimonials Section */
        .testimonials {
            background-color: var(--light);
        }

        .testimonials-slider {
            max-width: 800px;
            margin: 50px auto 0;
            position: relative;
        }

        .testimonial {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
            display: none;
        }

        .testimonial.active {
            display: block;
        }

        .testimonial-text {
            font-size: 1.1rem;
            font-style: italic;
            margin-bottom: 20px;
            color: #555;
        }

        .testimonial-author {
            font-weight: bold;
            color: var(--dark);
        }

        .testimonial-role {
            color: #777;
            font-size: 0.9rem;
        }

        .testimonial-nav {
            display: flex;
            justify-content: center;
            margin-top: 30px;
        }

        .testimonial-dot {
            width: 12px;
            height: 12px;
            background: #ccc;
            border-radius: 50%;
            margin: 0 5px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .testimonial-dot.active {
            background: var(--primary);
        }

        /* Contact Section */
        .contact {
            background-color: white;
        }

        .contact-container {
            display: flex;
            gap: 50px;
            margin-top: 50px;
        }

        .contact-info {
            flex: 1;
        }

        .contact-info h3 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--dark);
        }

        .contact-details {
            margin-bottom: 30px;
        }

        .contact-item {
            display: flex;
            align-items: flex-start;
            margin-bottom: 20px;
        }

        .contact-item i {
            font-size: 1.2rem;
            color: var(--primary);
            margin-right: 15px;
            margin-top: 5px;
        }

        .contact-form {
            flex: 1;
            background: var(--light);
            padding: 30px;
            border-radius: 10px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: var(--dark);
        }

        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-family: inherit;
            font-size: 1rem;
        }

        .form-group textarea {
            height: 150px;
            resize: vertical;
        }

        /* Footer */
        footer {
            background-color: var(--dark);
            color: white;
            padding: 60px 0 20px;
        }

        .footer-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }

        .footer-col h3 {
            font-size: 1.3rem;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }

        .footer-col h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 2px;
            background: var(--primary);
        }

        .footer-col p {
            margin-bottom: 15px;
            opacity: 0.8;
        }

        .footer-links {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 10px;
        }

        .footer-links a {
            color: white;
            opacity: 0.8;
            transition: opacity 0.3s ease;
        }

        .footer-links a:hover {
            opacity: 1;
            color: var(--primary);
        }

        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }

        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            color: white;
            font-size: 1.2rem;
            transition: all 0.3s ease;
        }

        .social-links a:hover {
            background: var(--primary);
            transform: translateY(-3px);
        }

        .footer-bottom {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-size: 0.9rem;
            opacity: 0.7;
        }

        /* Back to Top Button */
        .back-to-top {
            position: fixed;
            bottom: 30px;
            right: 30px;
            width: 50px;
            height: 50px;
            background: var(--primary);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
            cursor: pointer;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s ease;
            z-index: 999;
        }

        .back-to-top.active {
            opacity: 1;
            visibility: visible;
        }

        .back-to-top:hover {
            background: #c0392b;
            transform: translateY(-5px);
        }

        /* Responsive Styles */
        @media (max-width: 992px) {
            .about-content {
                flex-direction: column;
            }
            
            .about-img, .about-text {
                flex: none;
                width: 100%;
            }
            
            .contact-container {
                flex-direction: column;
            }
        }
        
        @media (max-width: 768px) {
            .header-container {
                padding: 15px;
            }
            
            nav {
                position: fixed;
                top: 80px;
                left: -100%;
                width: 100%;
                height: calc(100vh - 80px);
                background: white;
                transition: left 0.3s ease;
                z-index: 999;
            }
            
            nav.active {
                left: 0;
            }
            
            nav ul {
                flex-direction: column;
                padding: 20px;
            }
            
            nav ul li {
                margin: 15px 0;
            }
            
            .mobile-menu-btn {
                display: block;
            }
            
            .hero h1 {
                font-size: 2.2rem;
            }
            
            .hero-btns {
                flex-direction: column;
                gap: 15px;
            }
            
            .btn {
                width: 100%;
            }
            
            .section-title {
                font-size: 2rem;
            }
            
            .stats {
                flex-wrap: wrap;
                gap: 20px;
            }
            
            .stat-item {
                width: calc(50% - 10px);
            }
        }
        
        @media (max-width: 576px) {
            .hero {
                height: auto;
                padding: 100px 0;
            }
            
            .section-padding {
                padding: 60px 0;
            }
            
            .donate-options {
                flex-direction: column;
                align-items: center;
            }
            
            .stat-item {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-container">
            <div class="logo">
                <img src="https://via.placeholder.com/50x50" alt="Tender Hearts Logo">
                <div class="logo-text">
                    <h1>Tender Hearts</h1>
                    <span>Children Initiative</span>
                </div>
            </div>
            <button class="mobile-menu-btn" id="mobileMenuBtn">
                <i class="fas fa-bars"></i>
            </button>
            <nav id="mainNav">
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#programs">Programs</a></li>
                    <li><a href="#gallery">Gallery</a></li>
                    <li><a href="#donate">Donate</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Providing Hope and Shelter for Vulnerable Children in Uganda</h1>
            <p>Join us in our mission to transform the lives of orphans and vulnerable children through love, care, and education.</p>
            <div class="hero-btns">
                <a href="#donate" class="btn">Donate Now</a>
                <a href="#about" class="btn btn-secondary">Learn More</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about section-padding" id="about">
        <div class="container">
            <h2 class="section-title">About Our Initiative</h2>
            <div class="about-content">
                <div class="about-img">
                    <img src="https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Children at Tender Hearts">
                </div>
                <div class="about-text">
                    <h3>Our Story</h3>
                    <p>Tender Hearts Children Initiative was founded in 2010 with the mission to provide shelter, education, and holistic care to orphans and vulnerable children in Uganda. What began as a small home for 5 children has grown into a thriving community supporting over 100 children annually.</p>
                    <p>We believe every child deserves love, safety, and the opportunity to reach their full potential. Our approach focuses on creating a family-like environment where children can heal, grow, and prepare for a bright future.</p>
                    <div class="stats">
                        <div class="stat-item">
                            <div class="stat-number">100+</div>
                            <div class="stat-label">Children Helped</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">12</div>
                            <div class="stat-label">Years of Service</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">25</div>
                            <div class="stat-label">Dedicated Staff</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Programs Section -->
    <section class="programs section-padding" id="programs">
        <div class="container">
            <h2 class="section-title">Our Programs</h2>
            <p class="text-center">We provide comprehensive support to meet the physical, emotional, and educational needs of the children in our care.</p>
            <div class="programs-grid">
                <div class="program-card">
                    <div class="program-img">
                        <img src="https://images.unsplash.com/photo-1523050854058-8df90110c9f1?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Education Program">
                    </div>
                    <div class="program-content">
                        <h3>Education Support</h3>
                        <p>We ensure every child in our care has access to quality education through school fees payment, uniforms, books, and after-school tutoring.</p>
                        <a href="#" class="btn btn-secondary">Learn More</a>
                    </div>
                </div>
                <div class="program-card">
                    <div class="program-img">
                        <img src="https://images.unsplash.com/photo-1579684385127-1ef15d508118?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Nutrition Program">
                    </div>
                    <div class="program-content">
                        <h3>Nutrition & Health</h3>
                        <p>We provide balanced meals, clean water, and access to medical care to ensure our children grow up healthy and strong.</p>
                        <a href="#" class="btn btn-secondary">Learn More</a>
                    </div>
                </div>
                <div class="program-card">
                    <div class="program-img">
                        <img src="https://images.unsplash.com/photo-1549060279-7e168fcee0c2?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Counseling Program">
                    </div>
                    <div class="program-content">
                        <h3>Counseling & Therapy</h3>
                        <p>Our trained counselors help children heal from trauma and develop resilience through individual and group therapy sessions.</p>
                        <a href="#" class="btn btn-secondary">Learn More</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Donate Section -->
    <section class="donate section-padding" id="donate">
        <div class="container">
            <h2 class="section-title">Make a Difference Today</h2>
            <p>Your generous donation helps us provide food, shelter, education, and medical care to vulnerable children in Uganda. Every contribution, no matter the size, makes a real impact in a child's life.</p>
            <div class="donate-options">
                <div class="donate-option">
                    <i class="fas fa-hand-holding-heart"></i>
                    <h3>One-Time Gift</h3>
                    <p>Make a single donation to support our immediate needs and ongoing programs.</p>
                    <a href="http://gofund.me/d47c7728" class="btn" target="_blank">Donate via GoFundMe</a>
                </div>
                <div class="donate-option">
                    <i class="fas fa-calendar-check"></i>
                    <h3>Monthly Support</h3>
                    <p>Become a monthly donor and provide consistent support for a child's needs.</p>
                    <a href="https://www.paypal.me/KMHFINACIAL" class="btn btn-accent" target="_blank">Donate via PayPal</a>
                </div>
                <div class="donate-option">
                    <i class="fas fa-gift"></i>
                    <h3>Sponsor a Child</h3>
                    <p>Sponsor a specific child and follow their progress through regular updates.</p>
                    <a href="#contact" class="btn">Contact Us</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="gallery section-padding" id="gallery">
        <div class="container">
            <h2 class="section-title">Our Children's Smiles</h2>
            <p class="text-center">These moments of joy are made possible by your support.</p>
            <div class="gallery-grid">
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1503454537195-1dcabb73ffb9?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="Happy children">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1532635241-17e820acc59f?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="Children learning">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1548213238-0da7521bd6e0?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="Children playing">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1541746972996-4e0b0f43e02a?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="Children eating">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1516589178581-6cd7833ae3b2?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="Children in class">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1527631746610-bca00a040d60?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80" alt="Children singing">
                    <div class="gallery-overlay">
                        <i class="fas fa-search-plus"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials section-padding">
        <div class="container">
            <h2 class="section-title">Stories of Hope</h2>
            <div class="testimonials-slider">
                <div class="testimonial active">
                    <p class="testimonial-text">"Tender Hearts gave me a home when I had nowhere else to go. Thanks to their support, I'm now in university studying to become a doctor so I can help others like they helped me."</p>
                    <p class="testimonial-author">Sarah K.</p>
                    <p class="testimonial-role">Former Resident, Now Medical Student</p>
                </div>
                <div class="testimonial">
                    <p class="testimonial-text">"As a monthly donor, I receive regular updates about the child I sponsor. Seeing her progress in school and her smiling face makes my contribution feel so meaningful."</p>
                    <p class="testimonial-author">Michael T.</p>
                    <p class="testimonial-role">Sponsor from Canada</p>
                </div>
                <div class="testimonial">
                    <p class="testimonial-text">"After volunteering at Tender Hearts for 3 months, I can honestly say this is one of the most well-run organizations I've encountered. Every dollar goes directly to helping the children."</p>
                    <p class="testimonial-author">Emily R.</p>
                    <p class="testimonial-role">Volunteer from the UK</p>
                </div>
                <div class="testimonial-nav">
                    <div class="testimonial-dot active" data-slide="0"></div>
                    <div class="testimonial-dot" data-slide="1"></div>
                    <div class="testimonial-dot" data-slide="2"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact section-padding" id="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-container">
                <div class="contact-info">
                    <h3>We'd Love to Hear From You</h3>
                    <div class="contact-details">
                        <div class="contact-item">
                            <i class="fas fa-map-marker-alt"></i>
                            <div>
                                <p>P.O. BOX 710167</p>
                                <p>Kampala, Uganda</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <i class="fas fa-phone-alt"></i>
                            <div>
                                <p>+256 771 268 285 (Call/WhatsApp)</p>
                                <p>Mon-Fri, 8am-5pm EAT</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <i class="fas fa-envelope"></i>
                            <div>
                                <p>africankids.org@gmail.com</p>
                                <p>For all inquiries</p>
                            </div>
                        </div>
                    </div>
                    <h3>Follow Our Journey</h3>
                    <div class="social-links">
                        <a href="https://www.facebook.com/joshuambogoli" aria-label="Facebook" target="_blank"><i class="fab fa-facebook-f"></i></a>
                        <a href="https://www.instagram.com/joshuambogoli" aria-label="Instagram" target="_blank"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <div class="contact-form">
                    <form id="contactForm">
                        <div class="form-group">
                            <label for="name">Your Name</label>
                            <input type="text" id="name" name="name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email Address</label>
                            <input type="email" id="email" name="email" required>
                        </div>
                        <div class="form-group">
                            <label for="subject">Subject</label>
                            <input type="text" id="subject" name="subject" required>
                        </div>
                        <div class="form-group">
                            <label for="message">Your Message</label>
                            <textarea id="message" name="message" required></textarea>
                        </div>
                        <button type="submit" class="btn">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-container">
                <div class="footer-col">
                    <h3>About Us</h3>
                    <p>Tender Hearts Children Initiative is a registered non-profit organization dedicated to providing care, education, and hope to vulnerable children in Uganda since 2010.</p>
                    <p>Registration No.: 80034784000652</p>
                </div>
                <div class="footer-col">
                    <h3>Quick Links</h3>
                    <ul class="footer-links">
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#programs">Our Programs</a></li>
                        <li><a href="#donate">Donate</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Our Programs</h3>
                    <ul class="footer-links">
                        <li><a href="#">Child Sponsorship</a></li>
                        <li><a href="#">Education Support</a></li>
                        <li><a href="#">Health & Nutrition</a></li>
                        <li><a href="#">Counseling Services</a></li>
                        <li><a href="#">Community Outreach</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Newsletter</h3>
                    <p>Subscribe to our newsletter to receive updates on our work and stories from the children.</p>
                    <form
