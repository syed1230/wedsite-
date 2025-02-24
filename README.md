# wedsite-
This repositiry contains one wedsite and 2 wed pages 
<!--wed site about the spider man -->
<!--index page ocde-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spider-Man Index Page</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <div class="logo">🕷️ Spider-Man</div>
        <nav>
            <ul>
                <li><a href="/web_site3/ep_1.html">Homecoming</a></li>
                <li><a href="/web_site3/ep_3.html">Far from home </a></li>
                <li><a href="/web_site3/ep_2.html">no way Home</a></li>
                <li><a href="#">gallary</a></li>
                <li><a href="/web_site3/contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h1>Welcome to the Spider-Man Index Page</h1>
            <p>Explore the amazing world of Spider-Man! From movies to comics, characters to galleries, we've got it all!</p>
        </section>
        <section class="featured-content">
            <div class="content">
                <h2>Featured Movies</h2>
                <div class="image-placeholder"><img src="https://m.media-amazon.com/images/I/81mYx9A9FdL._AC_UF1000,1000_QL80_.jpg" alt ="image" width="500/300"></div>
                <br><br>
                <ul>
                    <li>Spider-Man: Homecoming</li>
                    <li>Spider-Man: Far From Home</li>
                    <li>Spider-Man: No Way Home</li>
                </ul>
            </div>
            <div class="content">
                <h2>Popular Characters</h2>
                <div class="image-placeholder"><img src="https://static1.colliderimages.com/wordpress/wp-content/uploads/2023/07/spider-man-homecoming-tom-holland.jpg"alt="imagae"width="500/300"></div>
                <br><br>
                <ul>
                    <li>Peter Parker</li>
                    <li>Mary Jane Watson</li>
                    <li>Green Goblin</li>
                </ul>
            </div>
        </section>
    </main>
    <br><br><Br>
        <div class="pic">
        <img src="https://www.scribblinggeek.com/wp-content/uploads/2021/12/spider-man-no-way-home-movie-review.jpg"alt="image"width=500/500">
        <img src="https://miro.medium.com/v2/resize:fit:1020/1*cBEw3vCOdWv8dQMoG_EtUA.png"alt="image"width="500/500">
        <img src="https://i.ytimg.com/vi/k-dQlHA-VB8/maxresdefault.jpg"alt="3"width="500/500">
        <img src="https://m.media-amazon.com/images/I/A1QMSfJ4bEL._AC_UF894,1000_QL80_.jpg"alt="4"width="200/300">
    </div>
    <br><br><br><br><br><
    <div class="about">
        <h1>🕷️🕸️🕷️🕸️🕷️🕸️🕷️🕸️ <B>SPIDER MAN</B>🕷️🕸️🕷️🕸️🕷️🕸️🕷️🕸️🕷️</h1>
        <p>
           <font size="5">   Spider-Man 🕷️ is a superhero like no other 🦸‍♂️! After being bitten by a radioactive spider 🕷️, Peter Parker gains amazing powers 🦸‍♂️. He can swing through the streets of New York 🏙️ with his webs 🕸️, crawl up buildings 🧗‍♂️, and his "spider-sense" 🧠 warns him of danger before it happens ⚠️. As Peter 🧑‍🎤, he tries to balance his life as a student 📚, friend 👯‍♂️, and superhero 🦸‍♂️, but it's not always easy 😅. His famous motto, "With great power comes great responsibility" 💪💥, guides him through every challenge 🌟. He faces villains like the Green Goblin 👹, Venom 🐍, and the Vulture 🦅, always ready to protect his beloved city 🏙️. No matter what, Spider-Man always saves the day ⚡! Even if it means making personal sacrifices 💔, he never gives up! 🌟
          
        </font>
        </p>
    </div>
    
<br><br><br><br>
    <footer>
        <p>&copy; 2025 Spider-Man Fan Page. All rights reserved.</p>
    </footer>
</body>
</html>
<!--css for this file-->

body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0; 
     color: #333;
/* background-image:url(https://wallpapersmug.com/download/3840x2160/0e57ac/spider-man-neon.jpg);
background-repeat: no-repeat;
background-size: cover; */
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #ff0000;
    color: white;
    padding: 15px 20px;
}

header .logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ffd700;
}

.hero {
    background: url('https://w0.peakpx.com/wallpaper/661/923/HD-wallpaper-chibi-spidey-spiderman-superheroes-digital-art-artwork.jpg') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.hero h1 {
    margin: 0;
    font-size: 48px;
}

.hero p {
    font-size: 24px;
}

.featured-content {
    display: flex;
    justify-content: space-around;
    padding: 40px 20px;
    background-color: white;
    text-align: center;
}

.featured-content .content {
    width: 45%;
}

.featured-content h2 {
    font-size: 32px;
    margin-bottom: 20px;
}

.featured-content ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

.featured-content ul li {
    font-size: 20px;
    margin: 10px 0;
}

.featured-content .image-placeholder {
    width: 100%;
    height: 200px;
    background-color: #b80909;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 18px;
    color: #aaa;
}
.pic{
    width: 100%;
    height: 300px;
    align-content:normal;
    background-color: #b80909;
}
.about {
    background-image: url('https://t4.ftcdn.net/jpg/06/20/96/05/360_F_620960531_UDsMM2MyGwxes4gEFc4Awsb1iYFQksVr.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    /* background:linear-gradient(to right,rgb(124, 3, 3),#943b3b,#3f3d87,rgb(4, 4, 119) ); */
    border: 1px solid #ede7e7;
    border-radius: 50px;
    margin: 15px auto;
    padding: 40px;
    width: 80%;
    box-shadow: 0 0 10px rgb(255, 4, 4);
    color: #f0f0f0;
  }
  .about h2 {
    font-size: 1.8em;
    margin-bottom: 15px;
    justify-content: center;
    text-align: center;
    
  }

footer {
    background-color: #ff0000;
    color: white;
    text-align: center;
    padding: 15px 20px;
    bottom: 0;
    width: 100%;
}
