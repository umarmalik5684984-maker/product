<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shoes Product Page</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 90%;
            max-width: 900px;
            margin: 30px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .product-box {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .product-box img {
            width: 320px;
            border-radius: 10px;
        }

        .product-info {
            flex: 1;
        }

        .product-info h2 {
            margin-top: 0;
        }

        .price {
            color: green;
            font-size: 24px;
            font-weight: bold;
        }

        .btn {
            display: inline-block;
            padding: 12px 20px;
            background: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 15px;
            font-size: 16px;
        }

        .btn:hover {
            background: #0056b3;
        }

    </style>
</head>
<body>

    <div class="container">
        <div class="product-box">
            
            <!-- Product Image -->
            <img src="https://www.ndure.com/cdn/shop/files/M-PR-LEN-0014BLACK.jpg?v=1759385226" alt="Shoes">

            <!-- Product Info -->
            <div class="product-info">
                <h2>Sport Running Shoes</h2>
                <p>Comfortable and lightweight running shoes designed for daily training and casual wear.</p>

                <p class="price">$79.99</p>

                <h3>Features:</h3>
                <ul>
                    <li>Breathable mesh material</li>
                    <li>Lightweight sole</li>
                    <li>Shock-absorbing design</li>
                    <li>Available in multiple sizes</li>
                </ul>

                <a class="btn" href="#">Add to Cart</a>
            </div>
        </div>
    </div>

</body>
</html>
