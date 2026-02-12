<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Men's Clothes</title>
<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f4f4f4;
}

header {
    background: white;
    padding: 20px 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid #ddd;
}

header h1 {
    margin: 0;
    font-size: 28px;
}

nav a {
    margin: 0 15px;
    text-decoration: none;
    color: black;
    font-weight: bold;
}

.hero {
    background: url('https://images.unsplash.com/photo-1520975922324-7b1fbdcc3f52') center/cover;
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    text-align: center;
}

.hero h2 {
    font-size: 40px;
    background: rgba(0,0,0,0.5);
    padding: 20px;
}

.section {
    padding: 50px;
    text-align: center;
}

.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}

.card {
    background: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.card img {
    width: 100%;
    height: 250px;
    object-fit: cover;
}

.card h4 {
    margin: 10px 0;
}

.card button {
    background: black;
    color: white;
    padding: 10px 15px;
    border: none;
    cursor: pointer;
}

.categories {
    display: flex;
    gap: 20px;
    margin-top: 40px;
}

.category {
    flex: 1;
    background: #222;
    color: white;
    padding: 40px;
    font-size: 22px;
}

footer {
    background: #111;
    color: white;
    padding: 30px;
    text-align: center;
    margin-top: 50px;
}
</style>
</head>

<body>

<header>
    <h1>Men's Clothes</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">New Arrivals</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Create Your Individuality</h2>
</section>

<section class="section">
    <h2>New Products</h2>
    <div class="products">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1593030761757-71fae45fa0e7">
            <h4>Stylish Jacket</h4>
            <p>$120.00</p>
            <button>Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1520974735194-6c77e0f20f7c">
            <h4>Modern Suit</h4>
            <p>$250.00</p>
            <button>Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1602810318383-e386cc2a3ccf">
            <h4>Casual Shirt</h4>
            <p>$60.00</p>
            <button>Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1593032457863-03d3b6bdf6f7">
            <h4>Winter Hoodie</h4>
            <p>$90.00</p>
            <button>Add to Cart</button>
        </div>
    </div>

    <div class="categories">
        <div class="category">Coats & Jackets</div>
        <div class="category">Sports Jackets</div>
        <div class="category">Suits & Blazers</div>
    </div>
</section>

<footer>
    <p>© 2026 Men's Clothes | All Rights Reserved</p>
</footer>

</body>
</html>
