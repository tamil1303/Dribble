# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Pacifico', cursive;
            margin: 0;
            padding: 0;
            background-image: url('your-image-url.jpg'); 
            background-size: cover;
            background-position: center; 
            background-repeat: no-repeat; 
            color: #2c3e50; 
        }
        .gallery-item {
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease;
        }
        .gallery-item:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .gallery-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
    </style>

    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
</head>
<body>
    
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Dribbble</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Community</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
                <li class="nav-item"><a class="btn btn-primary" href="#">Sign Up</a></li>
            </ul>
        </div>
    </nav>

    
    <div class="container mt-4">
        <div class="text-center mb-4 header-section">
            <h3>What are you working on?</h3>
            <p class="lead">Dribbble is show and tell for designers.</p>
        </div>

        
        <div class="row gallery-section">
            
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="1224FEA_Cookies_199_RedVelvet-Sandwich-Cookies_preview-d99b2c8f011b44bca382da3a5862f18e.jpg" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">cream cookies</p>
                        
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="christmas-cookies-6859116_640.jpg" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">Leaf Cookies</p>
                
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="pinwheel-cookies-homemade.jpg" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">Choco cookies</p>
                        
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="Thumbprint-cookies-baf69cf.jpg" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">Jam Cookies</p>
                        
                    </div>
                </div>
            </div>
        
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="83804240.webp" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title"></p>
                        <small class="text-muted">Round cookies</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="white.jpg" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">Cheese cookies</p>
                        
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="images (1).jpg" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">Moon cookies</p>
                        
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="images.jpg" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">Blue cookies</p>
                        
                    </div>
                </div>
            </div>
        </div>
    </div>


    <footer class="bg-dark text-white text-center py-3">
        <p>© Dribbble. All rights reserved.</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/1a3b4e2b-e93f-4fce-ae06-9d4cf6b2f6bb)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
