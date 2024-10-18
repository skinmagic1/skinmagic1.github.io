<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SKIN MAGIK</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 4px;
            background-color: #ffffff;
        }

        .header .logo {
            width: 70px;
        }

        .header .company-name {
            font-size: 24px;
            color: black;
            font-weight: bold;
        }

        .cover-image {
            width: 100%;
            height: 300px;
            background-image: url('cover-image.png');
            background-size: cover;
            background-position: center;
            margin-bottom: 20px;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .product {
            background-color: white;
            border-radius: 8px;
            padding: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .product img {
            max-width: 100%;
            border-radius: 8px;
        }

        .product .name {
            font-size: 18px;
            margin: 10px 0;
            font-weight: bold;
        }

        .product .price {
            font-size: 16px;
            color: #999;
            text-decoration: line-through;
        }

        .product .discount {
            font-size: 20px;
            color: #ff6000;
        }

        .product .discount-box {
            background-color: #ff6000;
            color: white;
            display: inline-block;
            padding: 5px 10px;
            border-radius: 4px;
            margin-top: 10px;
            font-weight: bold;
        }

        .description {
            padding: 20px;
            background-color: white;
            text-align: center;
            font-size: 16px;
            color: #555;
        }

        .footer {
            padding: 10px;
            background-color: #333;
            color: white;
            text-align: center;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <div class="header">
        <div class="company-name">SKIN MAGIK</div>
        <img src="logo.png" alt="Logo" class="logo">
    </div>

    <!-- Cover Image -->
    <div class="cover-image"></div>

    <!-- Product Grid Section -->
    <div class="product-grid">
        <!-- Product 1 -->
        <div class="product">
            <a href="https://amzn.to/4f0D11H">
                <img src="product1.png" alt="Product 1">
            </a>
            <div class="name">مرطب للجسم خاص بالبشرة الجافة</div>
 <div class="discount">70sar</div>
            <div class="price">100sar</div>
         
            <div class="discount-box">خصم %30</div>
        </div>

        <!-- Product 2 -->
        <div class="product">
            <a href="https://amzn.to/3Y2uYKN">
                <img src="product2.png" alt="Product 2">
            </a>
            <div class="name">اسم المنتج 2</div>
         
            <div class="discount">120sar</div>
<div class="price">150sar</div>
            <div class="discount-box">خصم %20</div>
        </div>

        <!-- Product 3 -->
        <div class="product">
            <a href="product-link-3.html">
                <img src="product3.png" alt="Product 3">
            </a>
            <div class="name">اسم المنتج 3</div>
 <div class="discount">50sar</div>
            <div class="price">80sar</div>
    
            <div class="discount-box"> 40% خصم </div>
        </div>

        <!-- Product 4 -->
        <div class="product">
            <a href="product-link-4.html">
                <img src="product4.png" alt="Product 4">
            </a>
            <div class="name">اسم المنتج 4</div>
            <div class="discount">150sar</div>
 <div class="price">200sar</div>
            <div class="discount-box">خصم %25</div>
        </div>
    </div>

    <!-- Description Section -->
    <div class="description">
        <p>!استمتع بأحدث العروض على منتجاتنا ذات الجودة العالية مع تخفيضات مذهلة تصل إلى 50%. 
تابعنا للحصول على المزيد من العروض</p>
    </div>

    <!-- Footer Section -->
    <div class="footer">
        <p>SKIN MAGIC 2024 © حقوق النشر محفوظة  </p>
    </div>

</body>
</html>
