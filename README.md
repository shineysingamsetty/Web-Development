1.<!DOCTYPE html>
<html>
<head>
    <title>Sweet Bliss Bakery</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            color: #5c2c2c;

            /* Full webpage cake background */
            background:
                linear-gradient(rgba(255,248,240,0.82),
                                rgba(255,248,240,0.82)),
                url("https://images.unsplash.com/photo-1495147466023-ac5c588e2e94?auto=format&fit=crop&w=1600&q=80");

            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        header {
            background: #8b3a3a;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 35px;
            margin-bottom: 10px;
        }

        nav {
            background: #f4c2c2;
            padding: 15px;
            text-align: center;
        }

        nav a {
            text-decoration: none;
            color: #5c2c2c;
            margin: 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: white;
            background: #8b3a3a;
            padding: 10px;
            border-radius: 5px;
        }

        .hero {
            background:
                linear-gradient(rgba(0,0,0,0.4),
                                rgba(0,0,0,0.4)),
                url("https://images.unsplash.com/photo-1578985545062-69928b1d9587?auto=format&fit=crop&w=1600&q=80")
                center/cover;

            height: 350px;
            text-align: center;
            color: white;
            padding: 100px 20px;
        }

        .hero h2 {
            font-size: 40px;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 20px;
        }

        section {
            padding: 40px 20px;
            text-align: center;
        }

        section h2 {
            color: #8b3a3a;
            margin-bottom: 25px;
            font-size: 30px;
        }

        .gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 25px;
        }

        .card {
            background: rgba(255,255,255,0.95);
            width: 250px;
            border-radius: 12px;
            box-shadow: 0 4px 10px #d8b4b4;
            overflow: hidden;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
        }

        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .card h3 {
            margin: 15px;
        }

        .card p {
            margin: 10px;
        }

        .price {
            color: #d6336c;
            font-size: 20px;
            font-weight: bold;
            padding-bottom: 15px;
        }

        .custom {
            background: rgba(255,228,225,0.90);
        }

        .offer {
            background: #8b3a3a;
            color: white;
            padding: 35px;
            margin: 20px;
            border-radius: 15px;
        }

        .offer h2 {
            color: white;
        }

        .offer p {
            font-size: 20px;
        }

        .contact {
            background: rgba(255,240,245,0.90);
        }

        footer {
            background: #8b3a3a;
            color: white;
            text-align: center;
            padding: 20px;
        }

        @media (max-width: 600px) {
            nav a {
                display: inline-block;
                margin: 8px;
            }

            .hero h2 {
                font-size: 28px;
            }

            .card {
                width: 90%;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>🍰 Sweet Bliss Bakery</h1>
    <p>Freshly Baked Happiness Every Day!</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#cakes">Cakes</a>
    <a href="#pastries">Pastries</a>
    <a href="#custom">Custom Cakes</a>
    <a href="#offers">Offers</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
    <h2>Welcome to Sweet Bliss Bakery</h2>
    <p>Delicious Cakes, Sweet Memories!</p>
</div>

<section id="cakes">
    <h2>Our Delicious Cakes 🎂</h2>

    <div class="gallery">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?auto=format&fit=crop&w=600&q=80" alt="Chocolate Cake">
            <h3>Chocolate Cake</h3>
            <p>Rich and creamy chocolate cake</p>
            <p class="price">₹500</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1563729784474-d77dbb933a9e?auto=format&fit=crop&w=600&q=80" alt="Strawberry Cake">
            <h3>Strawberry Cake</h3>
            <p>Fresh strawberry cream cake</p>
            <p class="price">₹600</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1535141192574-5d4897c12636?auto=format&fit=crop&w=600&q=80" alt="Birthday Cake">
            <h3>Birthday Cake</h3>
            <p>Beautiful birthday celebration cake</p>
            <p class="price">₹800</p>
        </div>

    </div>
</section>

<section id="pastries">
    <h2>Pastries & Cookies 🍪</h2>

    <div class="gallery">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1555507036-ab1f4038808a?auto=format&fit=crop&w=600&q=80" alt="Chocolate Pastry">
            <h3>Chocolate Pastry</h3>
            <p>Soft and delicious pastry</p>
            <p class="price">₹80</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1499636136210-6f4ee915583e?auto=format&fit=crop&w=600&q=80" alt="Cookies">
            <h3>Cookies</h3>
            <p>Crispy chocolate chip cookies</p>
            <p class="price">₹150</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1486427944299-d1955d23e34d?auto=format&fit=crop&w=600&q=80" alt="Cupcakes">
            <h3>Cupcakes</h3>
            <p>Colorful and tasty cupcakes</p>
            <p class="price">₹60</p>
        </div>

    </div>
</section>

<section class="custom" id="custom">
    <h2>Custom Cake Designs 🎨</h2>

    <div class="gallery">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1464349095431-e9a21285b5f3?auto=format&fit=crop&w=600&q=80" alt="Wedding Cake">
            <h3>Wedding Cakes</h3>
            <p>Elegant cakes for special occasions</p>
            <p class="price">Starting ₹2000</p>
        </div>

        <div class="card">
            <img src="https://static.vecteezy.com/system/resources/thumbnails/024/388/335/small_2x/celebration-party-birthday-cake-with-lots-of-icing-and-decorations-generative-ai-free-photo.jpg" alt="Desginer Cake">
            <h3>Designer Cakes</h3>
            <p>Customized cakes made with love</p>
            <p class="price">Starting ₹1000</p>
        </div>

    </div>

    <p style="margin-top:25px;">
        Contact us to customize your dream cake!
    </p>
</section>

<section id="offers">
    <div class="offer">
        <h2>🎉 Seasonal Special Offers 🎉</h2>
        <p>20% OFF on Birthday Cakes!</p>
        <p>Buy 2 Pastries and Get 1 Cookie FREE!</p>
        <p>Special Christmas and New Year Cake Collections!</p>
    </div>
</section>

<section class="contact" id="contact">
    <h2>Contact Us 📞</h2>

    <p><b>Address:</b> Main Road, Vijayawada</p>
    <p><b>Phone:</b> 98765 43210</p>
    <p><b>Email:</b> sweetbliss@example.com</p>
    <p><b>Opening Hours:</b> 9:00 AM - 9:00 PM</p>
</section>

<footer>
    <p>© 2026 Sweet Bliss Bakery | Made with ❤️</p>
</footer>

</body>
</html>

2.<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>FoodieHub - Online Food Ordering</title>

<style>

/* GENERAL */
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:Arial,sans-serif;
    background:#fff7f2;
    color:#3d1c15;
}

/* HEADER */
header{
    background:#35120b;
    color:white;
    padding:18px 7%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
}

.logo{
    font-size:28px;
    color:#ffcc00;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin:12px;
    font-weight:bold;
}

nav a:hover{
    color:#ffcc00;
}

.cart{
    background:#ff3b30;
    color:white;
    border:none;
    padding:12px 18px;
    border-radius:25px;
    cursor:pointer;
    font-weight:bold;
}

/* HERO */
.hero{
    min-height:450px;
    background:
    linear-gradient(90deg,rgba(0,0,0,.85),rgba(0,0,0,.2)),
    url("https://images.unsplash.com/photo-1550547660-d9450f859349?auto=format&fit=crop&w=1600&q=85")
    center/cover;
    display:flex;
    align-items:center;
    padding:60px 8%;
    color:white;
}

.hero-content{
    max-width:600px;
}

.hero h1{
    font-size:55px;
    margin-bottom:20px;
}

.hero h1 span{
    color:#ffcc00;
}

.hero p{
    font-size:20px;
    line-height:1.6;
}

.hero button{
    margin-top:25px;
    padding:15px 30px;
    background:#ff3b30;
    color:white;
    border:none;
    border-radius:30px;
    font-size:17px;
    cursor:pointer;
}

.hero button:hover{
    background:#d92318;
}

/* DELIVERY FEATURES */
.features{
    display:flex;
    justify-content:space-around;
    flex-wrap:wrap;
    gap:20px;
    background:white;
    padding:25px;
    box-shadow:0 4px 15px #ddd;
}

.feature{
    text-align:center;
    font-weight:bold;
}

.feature span{
    display:block;
    color:#ff3b30;
    font-size:25px;
    margin-bottom:8px;
}

/* SECTION */
section{
    padding:55px 7%;
}

.section-title{
    text-align:center;
    font-size:32px;
    margin-bottom:35px;
    color:#6b2013;
}

/* CATEGORIES */
.categories{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
    gap:20px;
}

.category{
    background:white;
    border-radius:15px;
    overflow:hidden;
    text-align:center;
    box-shadow:0 5px 15px #e5cfc7;
    transition:.3s;
}

.category:hover{
    transform:translateY(-8px);
}

.category img{
    width:100%;
    height:140px;
    object-fit:cover;
}

.category h3{
    padding:15px;
}

/* OFFER */
.offer{
    margin:20px 7%;
    padding:40px;
    background:linear-gradient(120deg,#6b1207,#e73518);
    color:white;
    border-radius:20px;
    text-align:center;
}

.offer h2{
    font-size:35px;
    color:#ffcc00;
    margin-bottom:15px;
}

.offer p{
    font-size:20px;
    margin-bottom:15px;
}

.offer button{
    background:#ffcc00;
    color:#35120b;
    border:none;
    padding:14px 28px;
    border-radius:30px;
    font-weight:bold;
    cursor:pointer;
}

/* FOOD MENU */
.menu{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:25px;
}

.food-card{
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 5px 15px #e2c9c0;
    transition:.3s;
}

.food-card:hover{
    transform:translateY(-8px);
}

.food-card img{
    width:100%;
    height:200px;
    object-fit:cover;
}

.food-info{
    padding:20px;
}

.food-info h3{
    margin-bottom:10px;
}

.food-info p{
    color:#777;
    margin-bottom:12px;
}

.rating{
    color:#ff9900;
    margin-bottom:12px;
}

.price{
    color:#e73518;
    font-size:22px;
    font-weight:bold;
}

.add-btn{
    width:100%;
    margin-top:15px;
    padding:12px;
    background:#ff3b30;
    color:white;
    border:none;
    border-radius:25px;
    cursor:pointer;
    font-weight:bold;
}

.add-btn:hover{
    background:#c82016;
}

/* REVIEWS */
.reviews{
    background:#ffe5df;
}

.review-container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.review{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 4px 10px #e5c6bd;
}

.review h3{
    color:#a42c19;
    margin-bottom:12px;
}

.review p{
    line-height:1.6;
}

/* RESTAURANT */
.restaurant{
    text-align:center;
    line-height:2;
}

.restaurant h2{
    color:#e73518;
    margin-bottom:15px;
}

/* CONTACT */
.contact{
    background:#fff0e8;
    text-align:center;
    line-height:2;
}

.contact h2{
    color:#e73518;
}

/* FOOTER */
footer{
    background:#35120b;
    color:white;
    text-align:center;
    padding:30px;
    line-height:2;
}

/* CART MODAL */
.modal{
    display:none;
    position:fixed;
    inset:0;
    background:rgba(0,0,0,.6);
    z-index:1000;
    justify-content:center;
    align-items:center;
    padding:20px;
}

.modal-box{
    background:white;
    padding:30px;
    border-radius:15px;
    width:100%;
    max-width:450px;
    max-height:80vh;
    overflow:auto;
}

.modal-box h2{
    margin-bottom:20px;
}

.cart-item{
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:10px;
    padding:12px 0;
    border-bottom:1px solid #ddd;
}

.cart-item button{
    padding:5px 10px;
    cursor:pointer;
}

.total{
    margin-top:20px;
    font-size:22px;
    font-weight:bold;
    color:#e73518;
}

.close-btn{
    background:#555;
    color:white;
    padding:10px 20px;
    border:none;
    border-radius:20px;
    cursor:pointer;
    margin-top:15px;
}

.checkout-btn{
    background:#ff3b30;
    color:white;
    padding:12px 20px;
    border:none;
    border-radius:20px;
    cursor:pointer;
    margin-top:15px;
}

/* RESPONSIVE */
@media(max-width:768px){

    header{
        justify-content:center;
        gap:20px;
    }

    nav{
        text-align:center;
    }

    nav a{
        display:inline-block;
        margin:8px;
    }

    .hero h1{
        font-size:38px;
    }

    .hero{
        min-height:400px;
    }

    .offer h2{
        font-size:27px;
    }
}

</style>
</head>

<body>

<!-- HEADER -->
<header>

<div class="logo">🍔 FoodieHub</div>

<nav>
<a href="#home">Home</a>
<a href="#categories">Categories</a>
<a href="#menu">Menu</a>
<a href="#offers">Offers</a>
<a href="#reviews">Reviews</a>
<a href="#contact">Contact</a>
</nav>

<button class="cart" onclick="openCart()">
🛒 Cart (<span id="cart-count">0</span>)
</button>

</header>

<!-- HERO -->
<div class="hero" id="home">

<div class="hero-content">

<h1>Delicious Food<br>
Delivered to <span>Your Door!</span></h1>

<p>
Order your favourite food from the best restaurant
in town. Fast, Fresh and Tasty.
</p>

<button onclick="document.getElementById('menu').scrollIntoView()">
Order Now 🍕
</button>

</div>
</div>

<!-- FEATURES -->
<div class="features">

<div class="feature">
<span>🛵</span>
Free Delivery<br>Above ₹199
</div>

<div class="feature">
<span>⏰</span>
30 Min Delivery<br>Guaranteed
</div>

<div class="feature">
<span>🔒</span>
Secure Payments<br>100% Safe
</div>

<div class="feature">
<span>☎️</span>
Customer Support<br>24/7
</div>

</div>

<!-- CATEGORIES -->
<section id="categories">

<h2 class="section-title">🍽️ Our Food Categories</h2>

<div class="categories">

<div class="category">
<img src="https://images.unsplash.com/photo-1513104890138-7c749659a591?auto=format&fit=crop&w=600&q=80" alt="Pizza">
<h3>🍕 Pizzas</h3>
</div>

<div class="category">
<img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?auto=format&fit=crop&w=600&q=80" alt="Burger">
<h3>🍔 Burgers</h3>
</div>

<div class="category">
<img src="https://tse2.mm.bing.net/th/id/OIP.JnC8QqiVvOA5zijmbRqbOQHaE7?r=0&w=1480&h=986&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Biryani">
<h3>🍛 Biryani</h3>
</div>

<div class="category">
<img src="https://images.unsplash.com/photo-1473093295043-cdd812d0e601?auto=format&fit=crop&w=600&q=80" alt="Pasta">
<h3>🍝 Pasta</h3>
</div>

<div class="category">
<img src="https://images.unsplash.com/photo-1546173159-315724a31696?auto=format&fit=crop&w=600&q=80" alt="Dessert">
<h3>🍰 Desserts</h3>
</div>

<div class="category">
<img src="https://images.unsplash.com/photo-1544145945-f90425340c7e?auto=format&fit=crop&w=600&q=80" alt="Drinks">
<h3>🥤 Drinks</h3>
</div>

</div>
</section>

<!-- OFFER -->
<div class="offer" id="offers">

<h2>🎉 Special Offer!</h2>

<p>Get 30% OFF on your first food order!</p>

<p>Use Coupon Code: <b>FOOD30</b></p>

<button onclick="document.getElementById('menu').scrollIntoView()">
Order Now →
</button>

</div>

<!-- MENU -->
<section id="menu">

<h2 class="section-title">🔥 Popular Dishes</h2>

<div class="menu">

<div class="food-card">
<img src="https://images.unsplash.com/photo-1513104890138-7c749659a591?auto=format&fit=crop&w=600&q=80" alt="Pizza">
<div class="food-info">
<h3>Margherita Pizza</h3>
<p>Fresh cheese, tomato and herbs</p>
<div class="rating">⭐ 4.8 (120 reviews)</div>
<span class="price">₹299</span>
<button class="add-btn" onclick="addToCart('Margherita Pizza',299)">🛒 Add to Cart</button>
</div>
</div>

<div class="food-card">
<img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?auto=format&fit=crop&w=600&q=80" alt="Burger">
<div class="food-info">
<h3>Classic Burger</h3>
<p>Juicy burger with cheese and vegetables</p>
<div class="rating">⭐ 4.7 (85 reviews)</div>
<span class="price">₹199</span>
<button class="add-btn" onclick="addToCart('Classic Burger',199)">🛒 Add to Cart</button>
</div>
</div>

<div class="food-card">
<img src="https://thumbs.dreamstime.com/b/top-view-biryani-platter-raita-chilled-lemonade-delicious-realistic-spread-featuring-flavorful-chicken-creamy-360641277.jpg" alt="Biryani">
<div class="food-info">
<h3>Chicken Biryani</h3>
<p>Spicy aromatic rice with chicken</p>
<div class="rating">⭐ 4.9 (150 reviews)</div>
<span class="price">₹249</span>
<button class="add-btn" onclick="addToCart('Chicken Biryani',249)">🛒 Add to Cart</button>
</div>
</div>

<div class="food-card">
<img src="https://images.unsplash.com/photo-1473093295043-cdd812d0e601?auto=format&fit=crop&w=600&q=80" alt="Pasta">
<div class="food-info">
<h3>Creamy Pasta</h3>
<p>Italian pasta with creamy sauce</p>
<div class="rating">⭐ 4.6 (75 reviews)</div>
<span class="price">₹249</span>
<button class="add-btn" onclick="addToCart('Creamy Pasta',249)">🛒 Add to Cart</button>
</div>
</div>

<div class="food-card">
<img src="https://images.unsplash.com/photo-1565958011703-44f9829ba187?auto=format&fit=crop&w=600&q=80" alt="Cake">
<div class="food-info">
<h3>Chocolate Cake</h3>
<p>Rich chocolate dessert</p>
<div class="rating">⭐ 4.8 (90 reviews)</div>
<span class="price">₹149</span>
<button class="add-btn" onclick="addToCart('Chocolate Cake',149)">🛒 Add to Cart</button>
</div>
</div>

<div class="food-card">
<img src="https://images.unsplash.com/photo-1544145945-f90425340c7e?auto=format&fit=crop&w=600&q=80" alt="Juice">
<div class="food-info">
<h3>Fresh Fruit Juice</h3>
<p>Refreshing seasonal fruit juice</p>
<div class="rating">⭐ 4.5 (60 reviews)</div>
<span class="price">₹99</span>
<button class="add-btn" onclick="addToCart('Fresh Fruit Juice',99)">🛒 Add to Cart</button>
</div>
</div>

</div>
</section>

<!-- REVIEWS -->
<section class="reviews" id="reviews">

<h2 class="section-title">💬 Customer Reviews</h2>

<div class="review-container">

<div class="review">
<h3>⭐⭐⭐⭐⭐</h3>
<p>"Amazing food and super fast delivery! The pizza was delicious."</p>
<br>
<b>- Priya Sharma</b>
</div>

<div class="review">
<h3>⭐⭐⭐⭐⭐</h3>
<p>"Best biryani in town. Great taste and excellent service."</p>
<br>
<b>- Rahul Kumar</b>
</div>

<div class="review">
<h3>⭐⭐⭐⭐⭐</h3>
<p>"Easy ordering process and beautiful food packaging."</p>
<br>
<b>- Ananya Reddy</b>
</div>

</div>
</section>

<!-- RESTAURANT -->
<section class="restaurant">

<h2>🏪 About Our Restaurant</h2>

<p><b>FoodieHub Restaurant</b></p>
<p>📍 123 Food Street, Vijayawada, Andhra Pradesh</p>
<p>⏰ Open: 10:00 AM - 11:00 PM</p>
<p>⭐ Restaurant Rating: 4.8/5</p>
<p>🚚 Delivery Available Across Vijayawada</p>

</section>

<!-- CONTACT -->
<section class="contact" id="contact">

<h2>📞 Contact Us</h2>

<p>📍 Address: 123 Food Street, Vijayawada</p>
<p>☎️ Phone: +91 98765 43210</p>
<p>📧 Email: support@foodiehub.com</p>
<p>🕒 Working Hours: 10 AM - 11 PM</p>

</section>

<!-- FOOTER -->
<footer>

<h2>🍔 FoodieHub</h2>
<p>Good Food. Good Mood.</p>
<p>Your Favourite Food, Delivered With Love ❤️</p>

<p>© 2026 FoodieHub | All Rights Reserved</p>

</footer>

<!-- CART MODAL -->
<div class="modal" id="cart-modal">

<div class="modal-box">

<h2>🛒 Your Shopping Cart</h2>

<div id="cart-items"></div>

<div class="total">
Total: ₹<span id="total">0</span>
</div>

<button class="checkout-btn" onclick="checkout()">Place Order</button>

<button class="close-btn" onclick="closeCart()">Close</button>

</div>
</div>

<script>

/* SHOPPING CART */
let cart = [];

function addToCart(name,price){

    let item = cart.find(food => food.name === name);

    if(item){
        item.quantity++;
    }
    else{
        cart.push({
            name:name,
            price:price,
            quantity:1
        });
    }

    updateCart();

    alert(name + " added to cart!");
}

function updateCart(){

    let count = 0;
    let total = 0;

    cart.forEach(item=>{
        count += item.quantity;
        total += item.price * item.quantity;
    });

    document.getElementById("cart-count").innerText = count;
    document.getElementById("total").innerText = total;

    let cartItems = document.getElementById("cart-items");

    cartItems.innerHTML = "";

    cart.forEach((item,index)=>{

        cartItems.innerHTML += `
        <div class="cart-item">

            <div>
                <b>${item.name}</b><br>
                ₹${item.price} × ${item.quantity}
            </div>

            <div>
                <button onclick="changeQty(${index},-1)">−</button>
                ${item.quantity}
                <button onclick="changeQty(${index},1)">+</button>
                <button onclick="removeItem(${index})">❌</button>
            </div>

        </div>
        `;

    });

}

function changeQty(index,change){

    cart[index].quantity += change;

    if(cart[index].quantity <= 0){
        cart.splice(index,1);
    }

    updateCart();
}

function removeItem(index){

    cart.splice(index,1);
    updateCart();

}

function openCart(){

    document.getElementById("cart-modal").style.display="flex";

}

function closeCart(){

    document.getElementById("cart-modal").style.display="none";

}

function checkout(){

    if(cart.length===0){
        alert("Your cart is empty!");
        return;
    }

    let total = cart.reduce((sum,item)=>
        sum + item.price * item.quantity,0);

    alert("Thank you for your order!\nTotal Amount: ₹"+total);

    cart=[];
    updateCart();
    closeCart();

}

</script>

</body>
</html>

3.<!DOCTYPE html>
<html>
<head>
    <title>FitZone Gym</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: url("https://images.unsplash.com/photo-1534438327276-14e5300c3a48")
                        center/cover fixed;
            color: white;
        }

        header {
            background: #111;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            color: #ff4500;
            font-size: 35px;
        }

        nav {
            background: #222;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
        }

        nav a:hover {
            color: #ff4500;
        }

        section {
            background: rgba(0, 0, 0, 0.85);
            margin: 15px;
            padding: 30px;
            border-radius: 10px;
            text-align: center;
        }

        .cards {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .card {
            background: #222;
            padding: 15px;
            width: 250px;
            border-radius: 10px;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 0 15px #ff4500;
        }

        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
        }

        h2 {
            color: #ff4500;
        }

        button {
            background: #ff4500;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: white;
            color: #ff4500;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background: #222;
        }

        th, td {
            border: 1px solid #555;
            padding: 12px;
        }

        th {
            background: #ff4500;
        }

        form {
            max-width: 450px;
            margin: auto;
        }

        input, select {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border-radius: 5px;
            border: none;
        }

        footer {
            background: #111;
            padding: 20px;
            text-align: center;
        }

        @media (max-width: 600px) {
            nav a {
                display: inline-block;
                margin: 8px;
            }

            section {
                padding: 20px 10px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>FITZONE GYM</h1>
        <p>Transform Your Body | Transform Your Life</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#programs">Programs</a>
        <a href="#trainers">Trainers</a>
        <a href="#plans">Membership</a>
        <a href="#schedule">Schedule</a>
        <a href="#register">Register</a>
    </nav>

    <section id="home">
        <h2>Welcome to FitZone</h2>
        <p>Build Strength, Improve Fitness, and Stay Healthy!</p>
        <button onclick="location.href='#register'">
            Join Now
        </button>
    </section>

    <section id="programs">
        <h2>Workout Programs</h2>

        <div class="cards">

            <div class="card">
                <img src="https://images.unsplash.com/photo-1534438327276-14e5300c3a48"
                     alt="Strength Training">
                <h3>Strength Training</h3>
                <p>Build strength and improve fitness.</p>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1517836357463-d25dfeac3438"
                     alt="Cardio Workout">
                <h3>Cardio</h3>
                <p>Improve stamina and endurance.</p>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b"
                     alt="Yoga">
                <h3>Yoga</h3>
                <p>Improve flexibility and relaxation.</p>
            </div>

        </div>
    </section>

    <section id="trainers">
        <h2>Our Trainers</h2>

        <div class="cards">

            <div class="card">
                <img src="https://images.unsplash.com/photo-1567013127542-490d757e51fc"
                     alt="Fitness Trainer">
                <h3>Rahul</h3>
                <p>Strength Trainer</p>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1583454110551-21f2fa2afe61"
                     alt="Fitness Trainer">
                <h3>Jeevan</h3>
                <p>Yoga Trainer</p>
            </div>

        </div>
    </section>

    <section id="facilities">
        <h2>Gym Facilities</h2>
        <p>Modern Equipment | Personal Training | Locker Rooms</p>
        <p>Cardio Machines | Weight Training | Yoga Studio</p>
    </section>

    <section id="plans">
        <h2>Membership Plans</h2>

        <div class="cards">

            <div class="card">
                <h3>Basic Plan</h3>
                <h2>₹999/month</h2>
                <p>Gym Access</p>
                <p>Basic Equipment</p>
                <button onclick="choosePlan('Basic Plan')">Select Plan</button>
            </div>

            <div class="card">
                <h3>Premium Plan</h3>
                <h2>₹1999/month</h2>
                <p>Gym Access</p>
                <p>Personal Training</p>
                <button onclick="choosePlan('Premium Plan')">Select Plan</button>
            </div>

            <div class="card">
                <h3>Elite Plan</h3>
                <h2>₹2999/month</h2>
                <p>All Facilities</p>
                <p>Personal Training + Yoga</p>
                <button onclick="choosePlan('Elite Plan')">Select Plan</button>
            </div>

        </div>
    </section>

    <section id="schedule">
        <h2>Class Schedule</h2>

        <table>
            <tr>
                <th>Class</th>
                <th>Time</th>
                <th>Trainer</th>
            </tr>

            <tr>
                <td>Yoga</td>
                <td>6 AM</td>
                <td>Priya</td>
            </tr>

            <tr>
                <td>Cardio</td>
                <td>8 AM</td>
                <td>Rahul</td>
            </tr>

            <tr>
                <td>Strength</td>
                <td>5 PM</td>
                <td>Rahul</td>
            </tr>
        </table>
    </section>

    <section id="register">
        <h2>Gym Registration</h2>

        <form id="form">

            <input type="text" id="name"
                   placeholder="Enter Your Name" required>

            <input type="email" id="email"
                   placeholder="Enter Your Email" required>

            <input type="tel" id="phone"
                   placeholder="10 Digit Phone Number"
                   pattern="[0-9]{10}" required>

            <select id="plan" required>
                <option value="">Select Membership Plan</option>
                <option>Basic Plan</option>
                <option>Premium Plan</option>
                <option>Elite Plan</option>
            </select>

            <button type="submit">Register Now</button>

        </form>

        <div id="result"></div>
    </section>

    <footer>
        <p>Contact: fitzone@gmail.com | 9876543210</p>
        <p>© 2026 FitZone Gym</p>
    </footer>

    <script>
        function choosePlan(plan) {
            document.getElementById("plan").value = plan;
            location.href = "#register";
        }

        document.getElementById("form").onsubmit = function(e) {
            e.preventDefault();

            document.getElementById("result").innerHTML =
                "<h3>Registration Successful!</h3>" +
                "Welcome " + document.getElementById("name").value +
                "! Your selected plan is " +
                document.getElementById("plan").value;
        };
    </script>

</body>
</html>



