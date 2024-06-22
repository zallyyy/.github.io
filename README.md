# .github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Music Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .product-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product {
            background: #fff;
            border: 1px solid #ddd;
            margin: 10px;
            padding: 20px;
            width: 30%;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            color: #555;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Welcome to the Simple Music Store</h1>
        </div>
    </header>

    <div class="container">
        <section class="product-list">
            <div class="product">
                <img src="guitar.jpg" alt="Guitar">
                <h3>Acoustic Guitar</h3>
                <p>$150</p>
                <p>High quality acoustic guitar.</p>
            </div>
            <div class="product">
                <img src="piano.jpg" alt="Piano">
                <h3>Electric Piano</h3>
                <p>$300</p>
                <p>Top-notch electric piano with multiple features.</p>
            </div>
            <div class="product">
                <img src="drum.jpg" alt="Drum Set">
                <h3>Drum Set</h3>
                <p>$200</p>
                <p>Complete drum set for all your drumming needs.</p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Simple Music Store. All rights reserved.</p>
    </footer>
</body>
</html>
