<!DOCTYPE html>

<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Valley+Sans:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <title>Tamer store </title>
    <style>
        body {
            margin: 0;

            .valley-sans-<uniquifier> {
                font-family: "Valley Sans", sans-serif;
                font-optical-sizing: auto;
                font-weight: <weight>;
                font-style: normal;
            }

            .header {
                background-color: black;
                display: flex;
                justify-content: space-between;
                align-items: center;
                padding: 10px 50px;
            }

            .logo {
                width: 100px;
            }

            .header-links a {
                color: white;
                padding: 0px 25px;
                text-decoration: none;
                border-radius: 15px;
            }

            .header-links a:hover {
                color: blue;
            }

            .header-links button {
                background-color: cornflowerblue;
                border: none;
                padding: 5px 15px;
                border-radius: 15px;
            }

            .Landing-page {
                background-color: black;
                display: flex;
                justify-content: space-between;
                padding: 10px 50px;
                align-items: center;
                color: white;
                border-radius: 0px 0px 50px 50px;
            }

            .Landing-page-search input {
                border-radius: 50px;
                border: none;
                outline: none;
                height: 30px;
                padding: 0px 10px;
            }

            .Landing-page-search button {
                position: absolute;
                left: 200px;
                height: 30px;
                background-color: cornflowerblue;
                border: none;
                padding: 5px 15px;
                border-radius: 15px;
            }

            .Landing-page-image-container img {
                border-radius: 20px;
                width: 300px;
            }

            .Landing-page-left-section {
                width: 500px;
            }

            .trending-container {
                padding: 25px 50px;
            }

            .Trending {
                display: flex;
                align-items: center;
            }

            .Trending button {
                background-color: cornflowerblue;
                border: none;
                padding: 5px 10px;
                border-radius: 15px;

            }

            .card {
                width: 200px;
                background-color: #EEEEEE;
                height: 300px;
            }

            .card-info {
                display: flex;
                justify-content: space-between;
                align-items:flex-start
            }

            .card-info img {
                border-radius: 50px
            }
    </style>
</head>

<body>
    <!--HEADER-->
    <div class="header">
        <img class="logo" src="Gemini_Generated_Image_n2pwc6n2pwc6n2pw.jpg">
        <div class="header-links" style="color: aliceblue;">
            <a href="£">Home</a>
            <a href="£">Our shop</a>
            <a href="£">Contact Us</a>
            <button>Sign In</button>
        </div>
    </div>

    <!--Landing page-->
    <div class="Landing-page">
        <div>
            <span>WELCOME TO TAMER STORE</span>
            <h1>BEST GAMING SITE EVER!</h1>
            <P>
                Tamer Store is a free gaming store. It has a many games.You can download any game you want.
                please,tell your freinds to come site
            </P>
            <div class="Landing-page-search">
                <input placeholder="start typing..." />
                <button>Search</button>
            </div>
        </div>
        <div class="Landing-page-image-container">
            <img src="2713.jpg">
        </div>
    </div>
    <!--Trending Games-->
    <div class="Trending container">
        <div class="Trending">
            <h1>Trending Games</h1>
            <button>View All</button>
            <div class="trending cards">
                <div class="card">
                    <img src="images.jpg">
                    <div class="card-info">
                        <div class="card-name">
                            <p>Action</p>
                            <h3>Efootball2026</h3>

                        </div>
                    </div>


                </div>
            </div>
        </div>



</body>
