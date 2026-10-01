<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Q1 Drill 2</title>
    <style>
        section{
    	background-color: #eff4ff;
    	padding: 20px;
    	border-radius: 12px;
    	width: 600px;
    	margin: auto;
    	box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    h1,p{
    	text-align: center;
    }
    body{
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
    input[type="text"], select, textarea, button {
    	width: 94%;
    	padding: 15px;
    	border: 1px solid #ccc;
    	border-radius: 5px;
    	text-align: center;
    }
    </style>
</head>
<body>
<header>
    <h1>RATE A MOVIE</h1>
    <p>Say something about the movie</p>
</header>

    <br>
    <section>
    <form>
        <img style="display: block; height: 100px; width: 100px; margin: 0 auto;" src="https://cdn-icons-png.flaticon.com/512/4515/4515077.png" alt="movie logo">
        <label for="movie-title">Movie title</label>  
        <br>
        <input type="text" id="movie-title" name="movie-title" placeholder="type here...">

        <label for="genre">Genre/s (select all that apply):</label>
        <br>
        <input type="checkbox" id="genre1" name="genre1">
        <label for="genre1">Action</label>
        <input type="checkbox" id="genre2" name="genre2">
        <label for="genre2">Romance</label>
        <input type="checkbox" id="genre3" name="genre3">
        <label for="genre3">Comedy</label>
        <input type="checkbox" id="genre4" name="genre4">
        <label for="genre4">Tragedy</label>
        <input type="checkbox" id="genre5" name="genre5">
        <label for="genre5">Horror</label>
        <input type="checkbox" id="genre6" name="genre6">
        <label for="genre6">Fantasy</label>

    <br>

    <label for="rate">Rating/s</label>
        <br>
        <input type="radio" id="1star" name="1star">
        <label for="1star">✦⟡⟡⟡⟡</label>
        <br>
        <input type="radio" id="2stars" name="2stars">
        <label for="2stars">✦✦⟡⟡⟡</label>
        <br>
        <input type="radio" id="3stars" name="3stars">
        <label for="3stars">✦✦✦⟡⟡</label>
        <br>
        <input type="radio" id="4stars" name="4stars">
        <label for="4stars">✦✦✦✦⟡</label>
        <br>
        <input type="radio" id="5stars" name="5stars">
        <label for="5stars">✦✦✦✦✦</label>
    
        <br>
        <textarea id="review" placeholder="Write a review..." rows="4" cols="42"></textarea>

        <br>
        <input type="submit" id="submit" style="color: white; background-color: #33298f;" value="Submit my review">

        <br>
        Click <a href="https://www.boxofficemojo.com/chart/top_lifetime_gross/?area=XWW" target="_blank">here</a> for movie details.

    </form>
    </section>
</body>
</html>
