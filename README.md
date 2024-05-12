# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
ABOUT.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>contact us</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body style="background-color: rgb(191, 255, 0);">


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">NICK Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">SKIN CARE</a></li>
              <li><a class="dropdown-item" href="#">HEALTH CARE</a></li>
              <li><a class="dropdown-item" href="#">HOME CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="container py-5">
    <h1 class="text-center mb-4">Contact Us</h1>
    <div class="row">
      <div class="col-md-6">
        <h3>INFO</h3>
        <p>NICK Pharma</p>
        <p>NICK Pharma
           Tondiar Nagar,
           Chennai,
           PINCODE-600004.
        </p>
        <p>Phone Number: <a href="tel:+1234567890">256-356-4567</a></p>
        <p>Email: <a href="mailto:info@yourcompany.com">info@NICK.com</a></p>
      </div>
      <div class="col-md-6">
        <h3>To stay in touch </h3>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Your Name</label>
            <input type="text" class="form-control" id="name" required>
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email Address</label>
            <input type="email" class="form-control" id="email" required>
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" rows="3" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </div>
  </section>

  <footer style="background-color: rgb(69, 110, 199);" class="text-center py-3">
    <p>&copy; 2024 NICK Pharma NIKESHKUMAR C(212223040132)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
APP.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharma</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
<body style="background-color: rgb(191, 255, 0);">

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">NICK Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">SKIN CARE</a></li>
              <li><a class="dropdown-item" href="#">HEALTH CARE</a></li>
              <li><a class="dropdown-item" href="#">HOME CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="hero d-flex align-items-center justify-content-center text-center py-5 mb-5">
    <div class="container">
      <h1>PROFESSIONAL MEDICINE & PHARMACY ONLINE WOOCOMMERCE THEME</h1>
      <p class="lead">Our aim is to provide healthcare and medicines to people in all over world.</p>
      <a href="#" class="btn btn-primary btn-lg">MORE INFO</a>
    </div>
  </section>

  <section class="container">
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="1.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">UPDATION</h5>
            <p class="card-text">We are prone to update our machines to more enhanced way to make sure of your health needs</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="2.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">QUALITY</h5>
            <p class="card-text">Our commitment to quality ensures the safety and cleanliness of rooms to avoid spreading od disease.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="3.jpeg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Patient Care</h5>
            <p class="card-text">We are so kind to our patient.Its our responsibility to take a complete care of them.Every patient is equal to us no matter they are rich or poor.We respect our patients.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer style="background-color: rgb(69, 110, 199);" class="text-center py-3">
    <p>&copy; 2024 NICK Pharma NIKESHKUMAR C(212223040132) </p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
EVENT.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Events</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" crossorigin="anonymous">
</head>
<body style="background-color: rgb(191, 255, 0);">

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">NICK Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">SKIN CARE</a></li>
              <li><a class="dropdown-item" href="#">HEALTH CARE</a></li>
              <li><a class="dropdown-item" href="#">HOME CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <section class="container py-5">
    <h1 class="text-center mb-4">News & Events</h1>
    <div class="row">
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="7.jpg" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Mainz Biomed to unveil breakthrough early cancer detection study results at DDW 2024</h5>
            <p class="card-text" style="font-size: large;">Mainz Biomed N.V., a molecular genetics diagnostic company specializing in the early detection of cancer, will present  an analysis from  its eAArly DETECT study at Digestive Disease Week (DDW) 2024 in Washington D.C. from May 18th to May 21st. DDW is recognized as a premier forum for the latest advancements in gastroenterology, hepatology, endoscopy, and gastrointestinal surgery.</p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="8.jpg" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Autoimmune diseases: Targeting the cGAS-STING pathway</h5>
            <p class="card-text" style="font-size: large;">Cyclic GMP-AMP synthase (cGAS) functions as a foreign DNA sensor, triggering an immune response to pathogens by activating the STING (stimulator of interferon genes) receptor. Shortly after its discovery in 2013, abnormal activation of cGAS by self-DNA was found to cause debilitating and often deadly autoimmune disorders, such as systemic lupus erythematosus (SLE) and Aicardi–Goutieres Syndrome (AGS).</p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="9.webp" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Advances in Aseptic Processing: The Future of Sterile Pharmaceutical Manufacturing</h5>
            <p class="card-text" style="font-size: large;">The manufacturing of both sterile drugs and biological products can be achieved through terminal sterilization or aseptic processing.

                Terminal sterilization involves filling and sealing containers under specific environmental conditions to prevent the contamination of these products from microbial and particulate matter. After this process has been completed, the final product is often subjected to heat, irradiation, or another sterilization process.</p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
    </div>
   
    
    </section>
  <footer style="background-color: rgb(69, 110, 199);" class="text-center py-3">
    <p>&copy; 2024 NICK Pharma NIKESHKUMAR C(212223040132)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
PRODUCTS.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Products</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body style="background-color: rgb(191, 255, 0);">


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">NICK Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">SKIN CARE</a></li>
              <li><a class="dropdown-item" href="#">HEALTH CARE</a></li>
              <li><a class="dropdown-item" href="#">HOME CARE</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-5">
    <h1 class="text-center mb-4">Our Products</h1>
    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
      <div class="col">
        <div class="card">
          <img src="4.jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Neurocalm</h5>
            <p class="card-text">Neurocalm is a medication designed to alleviate symptoms of anxiety and promote relaxation by regulating neurotransmitter activity in the brain. It helps manage anxiety disorders, including generalized anxiety disorder and panic disorder.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="5.jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title"> CardioClear</h5>
            <p class="card-text">CardioClear is a cardiovascular medication that helps regulate blood pressure and improve heart function. It is commonly prescribed to individuals with hypertension and congestive heart failure to reduce the risk of cardiovascular events such as heart attacks and strokes.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="6.jpeg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title"> RenewFlex</h5>
            <p class="card-text"> RenewFlex is a joint health supplement formulated to support flexibility and mobility by promoting joint lubrication and cartilage health. It is commonly used to alleviate symptoms of osteoarthritis and improve joint function in individuals experiencing joint stiffness and discomfort.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      </div>
  
  
  </section>

  <footer style="background-color: rgb(69, 110, 199);" class="text-center py-3">
    <p>&copy; 2024 NICK Pharma NIKESHKUMAR C(212223040132)</p>
  </footer>

</body>
</html>
```



## OUTPUT:
![alt text](<Screenshot 2024-05-12 161851.png>)
![alt text](<Screenshot 2024-05-12 161904.png>)
![alt text](<Screenshot 2024-05-12 161921.png>)
![alt text](<Screenshot 2024-05-12 161934.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
