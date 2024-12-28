# Project Responsive Web Design using Bootstrap
# Date:7/12/2024
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Gliters</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
        <a class="navbar-brand" href="#"> </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#features">Features</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#gallery">Gallery</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#footer">Contact</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<header class="bg-primary text-white text-center py-5"style="background-image:url('background\ image.jpg');background-size: cover;">
    <div class="container" >
        <h1 style="color: black;">Welcome to  Gliters</h1>
    </div>
</header>

 

<!-- Gallery Section -->
<section id="gallery" class="py-5 bg-light">
    <div class="container">
        <div class="text-center mb-5">
            <h2> GLITERS</h2>
            <p class="lead"> Explore featured designs</p>
        </div>
        <div class="row g-4">
            <div class="col-md-4">
                <div class="card">
                    <img src=" c:\Users\admin\Downloads\NARS Sheer Glow foundation & Radiant Creamy concealer - Beautyill.jpg"width="300px"height="400px" class="card-img-top" alt="Design 1">
                    <div class="card-body">
                        <h5 class="card-title"> Foundation</h5>
                        <p class="card-text">Foundation is the solid base or groundwork upon which something is built or established.</p>
                        <p>Rs=1200</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src=" c:\Users\admin\Downloads\$76.jpg"width="300px"height="400px" class="card-img-top" alt="Design 2">
                    <div class="card-body">
                        <h5 class="card-title"> lash glue</h5>
                        <p class="card-text"> Lash glue is a specially formulated adhesive used to securely attach false eyelashes to your natural lash line.</p>
                        <p>Rs=2100</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src=" c:\Users\admin\Downloads\rubor.jpg"width="300px"height="400px" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title"> Rubor</h5>
                        <p class="card-text"> Rubor is the medical term for redness of the skin, often caused by increased blood flow due to inflammation or irritation..</p>
                        <p>Rs=2500</p>                   
                    </div>et an
                </div>
            </div>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card">
                        <img src=" c:\Users\admin\Downloads\lipglosses.jpg" width="300px"height="400px"class="card-img-top" alt="Design 1">
                        <div class="card-body">
                            <h5 class="card-title"> lipglosses</h5>
                            <p class="card-text"> Lip glosses are shiny, moisturizing cosmetics that add color and a glossy finish to enhance your lips.</p>
                            <p>Rs=2500</p>
                        </div>
                    </div>
                </div>
        
                    <div class="col-md-4">
                        <div class="card">
                            <img src=" c:\Users\admin\Downloads\Korean Skincare Aesthetic - LANEIGE LIP SLEEPING MASK .jpg"width="300px"height="400px" class="card-img-top" alt="Design 1">
                            <div class="card-body">
                                <h5 class="card-title">lip ballm </h5>
                                <p class="card-text"> Lip balm is a moisturizing product designed to hydrate and protect your lips from dryness and chapping.</p>
                                <p>Rs=4000</p>                            
                            </div>
                        </div>
                    </div>
        
                        <div class="col-md-4">
                            <div class="card">
                                <img src=" c:\Users\admin\Downloads\The Secret To Flawless Makeup.jpg"width="300px"height="400px" class="card-img-top" alt="Design 1">
                                <div class="card-body">
                                    <h5 class="card-title">compact powder </h5>
                                    <p class="card-text">Compact powder is a lightweight, pressed powder used to set makeup, reduce shine, and provide a smooth, matte finish to the skin .</p>
                                    <p>Rs=5000</p>
                                </div>
                            </div>
                        </div>          
                        </section>

<!-- Footer -->
<footer id="footer" class="bg-dark text-white py-4">
    <div class="container text-center">
        <p>&copy; 2024  GLITERS. All rights reserved.</p>
        <p>Follow us on <a href="#" class="text-white">Social Media</a></p>
        <P>Contact=9566795488</P>
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
~~~

# OUTPUT:
![Screenshot 2024-12-28 124239](https://github.com/user-attachments/assets/8d6868a7-ad04-40bf-a00c-58535a6f0968)
![Screenshot 2024-12-28 124308](https://github.com/user-attachments/assets/87af0d6d-9c0f-4800-b705-920dfd3b68f7)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
