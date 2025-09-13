# Insduslone
this is my first uplod 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css" rel="stylesheet">  
     <link rel="stylesheet" href="C:\Users\abhis\Desktop\INDUS\style.css">
     <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <style>
    

        .formm {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(to right, #e0f7fa, #e8f5e9);
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .contact-container {
            background: white;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            max-width: 1000px;
            width: 90%;
            display: flex;
            flex-wrap: wrap;
        }

        .contact-form, .contact-info {
            flex: 1 1 50%;
            padding: 40px;
        }

        .contact-header h2 {
            font-size: 32px;
            color: #2c3e50;
            margin-bottom: 10px;
        }

        .contact-header p {
            color: #555;
            margin-bottom: 30px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group input, .form-group textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 6px;
            font-size: 16px;
        }

        .form-group textarea {
            resize: vertical;
            height: 100px;
        }

        .submit-button {
            background-color: #00b894;
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 6px;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .submit-button:hover {
            background-color: #009170;
        }

        .info-item {
            margin-bottom: 30px;
        }

        .info-item h3 {
            color: #00b894;
            margin-bottom: 8px;
            font-size: 20px;
        }

        .info-item p {
            color: #666;
        }

        @media (max-width: 768px) {
            .contact-form, .contact-info {
                flex: 1 1 100%;
                padding: 30px 20px;
            }
        }
    </style>
</head>
<body>
    <div id="loader">
        <img src="loder.gif" alt="Loading..." id="loader-img">
      </div>
      
   
      <script>
        window.addEventListener("load", function() {
          setTimeout(function() {
            document.getElementById("loader").style.display = "none";
            document.getElementById("content").style.display = "block";
          }, 1300); // 2000 milliseconds = 2 seconds ka delay
        });
</script>
    <!-- Navbar Start -->  
      <nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top">  
        <div class="container-fluid">  
            <div class="row w-100 align-items-center">  
                <!-- First Column: Logo -->  
                <div class="col-lg-2 col-6">  
                    <a class="navbar-brand" href="index.html">  
                <img src="indus.logo.png" alt="Logo" class="img-fluid" style="height: 60px; width: auto;">  
                </a>  
                </div>  

                <!-- Button Columns -->  
                <div class="col-lg-10 col-6">  
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">  
                        <span class="navbar-toggler-icon"></span>  
                    </button>  

                    <div class="collapse navbar-collapse" id="navbarNav">  
                        <div class="nav-center" > <!-- Centered Links aligned to the right -->  
                            <ul class="navbar-nav" >  
                                <li class="nav-item">  
                                    <a class="nav-link" href="indusindex.html" >Home</a>  
                                </li>  
                                <li class="nav-item">  
                                    <a class="nav-link" href="#dded">Services</a>  
                                </li>  
                                <li class="nav-item">  
                                    <a class="nav-link" href="blog.html">Blog</a>  
                                </li>  
                                <li class="nav-item">  
                                    <a class="nav-link" href="contact.html">Connect</a>  
                                </li>  
                            </ul>  
                        </div>  
                    </div>  
                </div>  
            </div>  
        </div>  
    </nav>  
    <!-- Navbar End --> 
    <div class="form"> 
    <div class="contact-container">
        <div class="contact-form">
            <div class="contact-header">
                
                <h2>Contact Us</h2>
                <p>We'd love to hear from you! Fill out the form below to get in touch.</p>
            </div>
            <form action="https://api.web3forms.com/submit" method="POST">
                <input type="hidden" name="access_key" value="a2103e03-97c1-4006-8416-9be4c4ed744f">
                <div class="form-group">
                    <input type="text" name="Full_Name" placeholder="Your Name" required>
                </div>
                <div class="form-group">
                    <input type="email" name="Email" placeholder="Your Email" required>
                </div>
                <div class="form-group">
                    <textarea placeholder="Your Message" name="Message" required></textarea>
                </div>
                <button type="submit" class="submit-button">Send Message</button>
            </form>
        </div>
        <div class="contact-info">
            <div class="info-item">
                <h3>About Club</h3>
                <p>Running Guide, Workouts</p>
            </div>
            <div class="info-item">
                <h3>Phone (anytime)</h3>
                <p>+91 97183 51280<br>+91 85953 70145</p>
            </div>
            <div class="info-item">
                <h3>Office Location</h3>
                <p>Flat no.420, near metro station, aya nagar<br>Arjan garh, New Delhi, India</p>
            </div>
        </div>
    </div>
    </div>




    <!--footer start -->
<footer style="background-color: #1d1d1d; color: #ffffff; padding: 40px 20px; font-family: 'Arial', sans-serif;">  
    <div style="display: flex; justify-content: space-between; flex-wrap: wrap; max-width: 1200px; margin: auto;">  
        <div style="flex: 1; min-width: 250px; margin: 20px;">  
            <h2 style="font-size: 28px; margin-bottom: 10px; color: #ffcc00;">Loan.</h2>  
            <p style="font-size: 15px; line-height: 1.6; margin: 10px 0; opacity: 0.8;">  
                Heaven fruitful doesn't over lesser days appear creeping seasons so behold bearing.  
            </p>  
        </div>  
        <div style="flex: 1; min-width: 200px; margin: 20px;">  
            <h3 style="font-size: 20px; margin-bottom: 10px; color: #ffcc00;">Quick Links</h3>  
            <ul style="list-style-type: none; padding: 0;">  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">About</a>  
                </li>  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">Offers & Discounts</a>  
                </li>  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">Get Coupon</a>  
                </li>  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">Contact Us</a>  
                </li>  
            </ul>  
        </div>  
        <div style="flex: 1; min-width: 200px; margin: 20px;">  
            <h3 style="font-size: 20px; margin-bottom: 10px; color: #ffcc00;">New Products</h3>  
            <ul style="list-style-type: none; padding: 0;">  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">Woman Cloth</a>  
                </li>  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">Fashion Accessories</a>  
                </li>  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">Man Accessories</a>  
                </li>  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">Rubber made Toys</a>  
                </li>  
            </ul>  
        </div>  
        <div style="flex: 1; min-width: 200px; margin: 20px;">  
            <h3 style="font-size: 20px; margin-bottom: 10px; color: #ffcc00;">Support</h3>  
            <ul style="list-style-type: none; padding: 0;">  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">Frequently Asked Questions</a>  
                </li>  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">Terms & Conditions</a>  
                </li>  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">Privacy Policy</a>  
                </li>  
                <li style="margin: 5px 0;">  
                    <a href="#" style="color: #ffffff; text-decoration: none; transition: color 0.3s;">Report a Payment Issue</a>  
                </li>  
            </ul>  
        </div>  
    </div>  
    
<div style="text-align: center; margin-top: 30px;">  
      <h5 style="margin-bottom: 10px; color: #ffcc00;">Follow Us</h5>  
      <div style="margin-top: 10px;">
          <a href="#" style="color: #ffffff; margin: 0 15px; text-decoration: none; transition: color 0.3s;">
              <i class="fab fa-twitter fa-1x"></i>
          </a>  
          <a href="#" style="color: #ffffff; margin: 0 15px; text-decoration: none; transition: color 0.3s;">
              <i class="fab fa-facebook-f fa-1x"></i>
          </a>  
          <a href="#" style="color: #ffffff; margin: 0 15px; text-decoration: none; transition: color 0.3s;">
              <i class="fab fa-instagram fa-1x"></i>
          </a>  
            </div>
        </div> 
    
    
</footer> 
</body>
</html>
