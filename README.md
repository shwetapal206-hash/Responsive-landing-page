HTML Code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Landing Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav class="navbar" id="navbar">
        <h2 class="logo">Dream<span>Space</span></h2>

        <button class="menu-btn" id="menuBtn" aria-label="Open menu">☰</button>

        <ul class="nav-links" id="navLinks">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section class="hero" id="home">
        <div class="hero-content">
            <p class="tag">WELCOME TO DREAMSPACE ✨</p>
            <h1>Big Ideas Start With <span>You.</span></h1>
            <p class="description">
                Explore your creativity, discover new possibilities,
                and turn your ideas into something amazing.
            </p>
            <a href="#about" class="btn">Get Started →</a>
        </div>

        <div class="hero-image">💡</div>
    </section>

    <section class="about" id="about">
        <h2>A Place to <span>Create</span></h2>
        <p>
            DreamSpace is a simple space for creativity, learning,
            and discovering new ideas.
        </p>
    </section>

    <section class="services" id="services">
        <h2>What We Offer</h2>

        <div class="cards">
            <div class="card">
                <div class="icon">🎨</div>
                <h3>Creativity</h3>
                <p>Bring your imagination to life.</p>
            </div>

            <div class="card">
                <div class="icon">💻</div>
                <h3>Technology</h3>
                <p>Explore the digital world.</p>
            </div>

            <div class="card">
                <div class="icon">🚀</div>
                <h3>Growth</h3>
                <p>Learn something new every day.</p>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Ready to Begin?</h2>
        <p>Your next great idea starts today.</p>
        <a href="mailto:shwetapal206@gmail.com" class="btn">
            Contact Us →
        </a>
    </section>

    <footer>
        <p>Made with ❤️ | DreamSpace © <span id="year"></span></p>
    </footer>

     <script src="script.js"></script>
</body>
</html>

    <script src="script.js"></script>
</body>
</html>
