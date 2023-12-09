<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #111;
            color: #fff;
        }

        header {
            padding: 1rem;
            background-color: #000;
            text-align: center;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .main-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .movie-card {
            width: 300px;
            margin: 20px;
            overflow: hidden;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s;
            cursor: pointer;
        }

        .movie-card:hover {
            transform: scale(1.05);
        }

        .movie-card img {
            width: 100%;
            height: auto;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background-color: #000;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Netflix Clone</h1>
    </header>

    <div class="container">
        <div class="main-content">
            <!-- Movie Cards -->
            <div class="movie-card">
                <img src="movie1.jpg" alt="Movie 1">
                <h3>Movie Title 1</h3>
            </div>

            <div class="movie-card">
                <img src="movie2.jpg" alt="Movie 2">
                <h3>Movie Title 2</h3>
            </div>

            <!-- Add more movie cards as needed -->
        </div>
    </div>

    <footer>
        <p>&copy; 2023 Netflix Clone</p>
    </footer>
</body>
</html>
