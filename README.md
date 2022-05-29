//home page

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>University Website Design</title>
    <link rel="stylesheet" href="home.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css" integrity="sha384-jLKHWM3JRmfMU0A5x5AkjWkw/EYfGUAGagvnfryNV3F9VqM98XiIH7VBGVoxVSc7" crossorigin="anonymous">
</head>
<body>
    <section class="header">
        <nav>
            
            <div class="nav-links" id="navLinks">
                
                <i class="fa fa-times" onclick="hideMenu()"></i>
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="https://maps.google.com/">Location</a></li>
                    <li><a href="nikita.html">Crimes and Data</a></li>
                    <li><a href="Aboutus.html">CONTACT US</a></li>
                </ul>
            </div>
            <i class="fa fa-bars" onclick="showMenu()"></i>
        </nav>
        <div class="text-box">
            <h1>NOT DONE YET</h1>
            <p>Data Base Management<br>Yoooo</p>
            <a href="" class="hero-btn">Visit Us To Know More</a>
        </div>
    </section>


    
    
    

        


    

    
    <script>

        var navLinks = document.getElementById("navLinks"); 

        function showMenu(){
            navLinks.style.right = "0";
        }
        function hideMenu(){
            navLinks.style.right = "-200px";
        }

    </script>
</body>
</html>
