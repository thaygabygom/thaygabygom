<html>
<head>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            width: 200px;
            height: 100px;
            margin: 20px;
        }

        .menu {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #ffffff;
            padding: 10px;
        }

        .menu ul {
            list-style: none;
            display: flex;
        }

        .menu ul li {
            margin: 10px;
        }

        .menu ul li a {
            text-decoration: none;
            color: #000000;
            font-weight: bold;
        }

        .menu ul li a:hover {
            color: #ff0000;
        }

        .banner {
            width: 100%;
            height: 500px;
            background-image: url("orixas.jpg");
            background-size: cover;
            background-position: center;
        }

        .banner h1 {
            color: #ffffff;
            font-size: 50px;
            text-align: center;
            padding-top: 200px;
        }

        .banner h2 {
            color: #ffffff;
            font-size: 30px;
            text-align: center;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-gap: 20px;
            margin: 20px;
        }

        .product {
            background-color: #ffffff;
            padding: 10px;
            border: 1px solid #cccccc;
        }

        .product img {
            width: 100%;
            height: 200px;
            object-fit: contain;
        }

        .product h3 {
            color: #000000;
            font-size: 20px;
            margin: 10px 0;
        }

        .product p {
            color: #000000;
            font-size: 15px;
            margin: 10px 0;
        }

        .product button {
            width: 100%;
            height: 40px;
            background-color: #ff0000;
            color: #ffffff;
            font-weight: bold;
            border: none;
            cursor: pointer;
        }

        .product button:hover {
            background-color: #cc0000;
        }

        .footer {
            background-color: #000000;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }

        .footer p {
            margin: 10px 0;
        }

        .footer a {
            color: #ffffff;
            text-decoration: none;
        }

        .footer a:hover {
            color: #ff0000;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="menu">
            <img src="logo.png" alt="Amor & Axé" class="logo">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Produtos</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </div>
        <div class="banner">
            <h1>Amor & Axé</h1>
            <h2>A loja que celebra a fé e a arte dos povos africanos</h2>
        </div>
        <div class="products">
            <div class="product">
                <img src="guia.jpg" alt="Guia de contas">
                <h3>Guia de contas</h3>
                <p>R$ 29,90</p>
                <button>Comprar</button>
            </div>
            <div class="product">
                <img src="tridente.jpg" alt="Tridente de Exú">
                <h3>Tridente de Exú</h3>
                <p>R$ 49,90</p>
                <button>Comprar</button>
            </div>
            <div class="product">
                <img src="cajado.jpg" alt="Cajado de Oxalá">
                <h3>Cajado de Oxalá</h3>
                <p>R$ 59,90</p>
                <button>Comprar</button>
            </div>
            <div class="product">
                <img src="espada.jpg" alt="Espada de Ogum">
                <h3>Espada de Ogum</h3>
                <p>R$ 69,90</p>
                <button>Comprar</button>
            </div>
        </div>
    </div>
    <div class="footer">
        <p>Todos os direitos reservados © 2024 Amor & Axé</p>
        <p>Desenvolvido por Bing</p>
        <a href="#">Política de privacidade</a> | <a href="#">Termos de uso</a>
    </div>
</body>
</html>
