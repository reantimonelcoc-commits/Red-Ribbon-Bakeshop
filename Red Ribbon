<!DOCTYPE html>
<html>
<head>
    <title>Red Ribbon Bakeshop</title>

    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&family=Pacifico&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        body {
            margin: 0;
            margin-top: 80px;
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
        }

        header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background-color: #cc0000;
            padding: 10px 20px;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 80px;
            box-sizing: border-box;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        .logo {
            height: 50px;
        }

        nav a {
            color: white;
            margin: 25px;
            text-decoration: none;
            font-size: 18px;
            padding: 6px 10px;
            border-radius: 20px;
            transition: 0.3s;
        }

        nav a:hover {
            background-color: white;
            color: #c40000;
        }

        section {
            padding: 80px 20px;
        }

        html {
            scroll-behavior: smooth;
        }

        #home {
            background-image: url("https://dynl.mktgcdn.com/p/4twNGJuO2UypM7Ciz99mpOIO1pJsJr4hZlej-4amInU/1280x960.jpg");
            background-size: cover;
            background-position: center;
            text-align: center;
            color: white;
            min-height: 100vh;
        }

        #home h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 70px;
            margin-top: 120px;
            text-shadow: 2px 2px 5px red;
        }

        #home p {
            font-size: 22px;
            background: rgba(0,0,0,0.5);
            display: inline-block;
            padding: 10px 20px;
            border-radius: 10px;
        }

       
        #about {
            background-color: white;
            text-align: center;
        }

        .about-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 25px;
            max-width: 1100px;
            margin: auto;
            margin-top: 30px;
        }

        .about-card {
            background: #ffffff;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .about-card:hover {
            transform: translateY(-5px);
        }

        .about-card h2 {
            color: #cc0000;
        }

       
        .product-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
            max-width: 1100px;
            margin: auto;
            margin-top: 30px;
        }

        .product-card {
            background: white;
            padding: 15px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .product-card:hover {
            transform: scale(1.05);
        }

        .product-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            
            cursor: pointer;
        }

        .product-card p {
            margin-top: 10px;
            font-weight: bold;
            color: #cc0000;
        }

        #contact {
            background-color: #cc0000;
            color: white;
            text-align: center;
        }

        .contact-info p {
            font-size: 18px;
            margin: 10px 0;
        }
        .social-links {
    margin-top: 20px;
    text-align: center;
}
    .social-links a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    margin: 10px;
    padding: 12px 22px;
    background: #ffffff;
    color: #cc0000;
    text-decoration: none;
    border-radius: 30px;
    font-weight: bold;
    font-size: 16px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
}
    .social-links a:hover {
    background: #cc0000;
    color: white;
    transform: translateY(-3px);
    }
    .social-links i {
    font-size: 18px;
}

        .modal {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.85);
    display: none;
    justify-content: center;
    align-items: center;
}

.modal img {
    max-width: 80%;
    max-height: 80%;
    border-radius: 10px;
}

.modal:target {
    display: flex;
}

.close {
    position: absolute;
    top: 20px;
    right: 40px;
    font-size: 40px;
    color: white;
    text-decoration: none;
}

       
            @media (max-width: 768px) {
            .about-container {
                grid-template-columns: 1fr;
            }

            .product-grid {
                grid-template-columns: 1fr;
            }

            nav a {
                display: block;
                margin: 10px 0;
            }

            header {
                flex-direction: column;
                height: auto;
            }
        }

    </style>
</head>

<body>

<header>
    <img src="https://upload.wikimedia.org/wikipedia/en/5/58/Red_Ribbon_Bakeshop_Logo.webp" class="logo">

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#product">Product</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="home">
    <h1>Red Ribbon Bakeshop</h1>
    <p><b>Welcome to my Red Ribbon Bakeshop</b></p>
</section>

<section id="about">
    <h1>About</h1>

    <div class="about-container">
        <div class="about-card">
            <h2>What is Red Ribbon?</h2>
            <p>Red Ribbon is a well-known bakery chain from the Philippines, famous for its cakes, pastries, and comfort food.</p>
        </div>

        <div class="about-card">
            <h2>Background</h2>
            <p>Founded in 1979 in Quezon City. Now owned by Jollibee Foods Corporation.</p>
        </div>

        <div class="about-card">
            <h2>Popular Products</h2>
            <p>Black Forest Cake, Mango Supreme, Chocolate Mousse, Ensaymada, Ube Cake.</p>
        </div>

        <div class="about-card">
            <h2>Locations</h2>
            <p>Philippines, U.S., Canada, Middle East.</p>
        </div>
    </div>
</section>

<section id="product">
    <h1>Products</h1>

    <div class="product-grid">
        <div class="product-card">
            <a href="#img1">
            <img src="https://raw.githubusercontent.com/reantimonelcoc-commits/Image./main/Red-Ribbon-Philippines-Menu-Prices%20%281%29.webp">
            </a>
                <p>Menu Selection</p>
        </div>

        <div class="product-card">
            <a href="#img1">
            <img src="https://raw.githubusercontent.com/reantimonelcoc-commits/Image./main/Red-Ribbon-Philippines-Menu-Prices.webp">
            </a>    
            <p>Cake Varieties</p>
        </div>

        <div class="product-card">
            <a href="#img1">
            <img src="https://raw.githubusercontent.com/reantimonelcoc-commits/Image./main/images%20%2835%29.jpeg">
            </a>
            <p>Cake Varieties</p>
        </div>
    </div>
</section>

<section id="contact">
    <h1>Contact</h1>
    <p>We’d love to hear from you!</p>

    <div class="contact-info">
        <p>Email: rean.timonel.coc@phinmaed.com</p>
        <p>Email: axam.blaya.coc@phinmaed.com</p>
        <p>Email: reva.villamor.coc@phinmaed.com</p>
        <p>Email: ambe.balansi.coc@phinmaed.com</p>
    </div>
<div class="social-links">
    <div class="social-item">
        <i class="fab fa-facebook"></i> Facebook
    </div>

    <div class="social-item">
        <i class="fab fa-twitter"></i> Twitter (X)
    </div>

    <div class="social-item">
        <i class="fab fa-instagram"></i> Instagram
    </div>
</div>
</section>

<div id="img1" class="modal">
    <a href="#" class="close">&times;</a>
    <img src="https://raw.githubusercontent.com/reantimonelcoc-commits/Image./main/Red-Ribbon-Philippines-Menu-Prices%20%281%29.webp">
</div>

<div id="img2" class="modal">
    <a href="#" class="close">&times;</a>
    <img src="https://raw.githubusercontent.com/reantimonelcoc-commits/Image./main/Red-Ribbon-Philippines-Menu-Prices.webp">
</div>

<div id="img3" class="modal">
    <a href="#" class="close">&times;</a>
    <img src="https://raw.githubusercontent.com/reantimonelcoc-commits/Image./main/images%20%2835%29.jpeg">
</div>


</body>
</html>

