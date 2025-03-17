<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StepCom Corp - E-Commerce</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>StepCom Corp</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="electronics.html">Electronics</a>
            <a href="fashion.html">Fashion</a>
            <a href="books.html">Books</a>
            <a href="cart.html">Cart (<span id="cart-count">0</span>)</a>
        </nav>
    </header>

    <section class="categories">
        <h2>Shop by Category</h2>
        <div class="category-list">
            <a href="electronics.html" class="category">Electronics</a>
            <a href="fashion.html" class="category">Fashion</a>
            <a href="books.html" class="category">Books</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 StepCom Corp. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Electronics - StepCom Corp</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Electronics</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="fashion.html">Fashion</a>
            <a href="books.html">Books</a>
            <a href="cart.html">Cart (<span id="cart-count">0</span>)</a>
        </nav>
    </header>

    <section class="products">
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Smartphone">
            <h2>Smartphone</h2>
            <p>$499</p>
            <button onclick="addToCart('Smartphone', 499)">Add to Cart</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Laptop">
            <h2>Laptop</h2>
            <p>$999</p>
            <button onclick="addToCart('Laptop', 999)">Add to Cart</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 StepCom Corp. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion - StepCom Corp</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Fashion</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="electronics.html">Electronics</a>
            <a href="books.html">Books</a>
            <a href="cart.html">Cart (<span id="cart-count">0</span>)</a>
        </nav>
    </header>

    <section class="products">
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="T-Shirt">
            <h2>T-Shirt</h2>
            <p>$25</p>
            <button onclick="addToCart('T-Shirt', 25)">Add to Cart</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Sneakers">
            <h2>Sneakers</h2>
            <p>$80</p>
            <button onclick="addToCart('Sneakers', 80)">Add to Cart</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 StepCom Corp. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Books - StepCom Corp</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Books</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="electronics.html">Electronics</a>
            <a href="fashion.html">Fashion</a>
            <a href="cart.html">Cart (<span id="cart-count">0</span>)</a>
        </nav>
    </header>

    <section class="products">
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Book 1">
            <h2>Book Title 1</h2>
            <p>$15</p>
            <button onclick="addToCart('Book Title 1', 15)">Add to Cart</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Book 2">
            <h2>Book Title 2</h2>
            <p>$20</p>
            <button onclick="addToCart('Book Title 2', 20)">Add to Cart</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 StepCom Corp. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shopping Cart - StepCom Corp</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Shopping Cart</h1>
        <nav>
            <a href="index.html">Home</a>
        </nav>
    </header>

    <section class="cart-items">
        <h2>Your Cart</h2>
        <ul id="cart-list"></ul>
        <p>Total: $<span id="cart-total">0</span></p>
        <button onclick="checkout()">Checkout</button>
    </section>

    <footer>
        <p>&copy; 2025 StepCom Corp. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
