# Project Responsive Web Design using Bootstrap
## Date: 20/05/2025
## Name: VASANTHAN N
## Reg_No: 212224240180

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


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


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">

  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f8f9fa;
    }
    .navbar-dark .navbar-brand {
      font-weight: bold;
      font-size: 1.4rem;
    }
    .card-img-top {
      height: 200px;
      object-fit: cover;
    }
    .card:hover {
      box-shadow: 0 6px 18px rgba(0, 0, 0, 0.1);
      transform: translateY(-4px);
      transition: all 0.3s ease;
    }
    .btn-pink {
      background-color: #ea4c89;
      color: #fff;
    }
    .btn-pink:hover {
      background-color: #d44179;
    }
    .footer {
      background-color: #343a40;
      color: #ccc;
      padding: 20px 0;
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark px-4">
  <a class="navbar-brand" href="#">dribbble</a>
  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse justify-content-between" id="navbarNav">
    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
      <li class="nav-item"><a class="nav-link active" href="#">Shots</a></li>
      <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
      <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
      <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
    </ul>
    <form class="d-flex me-3">
      <input class="form-control form-control-sm" type="search" placeholder="Search">
    </form>
    <a href="#" class="btn btn-outline-light btn-sm me-2">Sign In</a>
    <a href="#" class="btn btn-pink btn-sm">Sign Up</a>
  </div>
</nav>

<!-- Header Call-to-Action -->
<div class="bg-light text-center py-4 border-bottom">
  <h5 class="mb-2">What are you working on?</h5>
  <p class="text-muted">Dribbble is show and tell for designers.</p>
  <a href="#" class="btn btn-pink btn-sm">Learn more</a>
</div>

<!-- Gallery Grid -->
<div class="container py-5">
  <div class="row g-4">
    <!-- Example card (duplicate for more) -->
    <div class="col-12 col-sm-6 col-md-4 col-lg-3">
      <div class="card h-100">
        <img src="images/U1.jpg" class="card-img-top" alt="Design 1">
        <div class="card-body">
          <h6 class="card-title mb-1">Design Title</h6>
          <small class="text-muted">by Designer Name</small>
        </div>
        <div class="card-footer bg-white border-0 d-flex justify-content-between">
          <span><i class="bi bi-eye"></i> 4,044</span>
          <span><i class="bi bi-heart"></i> 290</span>
        </div>
      </div>
    </div>

    <!-- Add more cards below -->
    <div class="col-12 col-sm-6 col-md-4 col-lg-3">
      <div class="card h-100">
        <img src="images/u2.jpg" class="card-img-top" alt="Design 2">
        <div class="card-body">
          <h6 class="card-title mb-1">Creative UI</h6>
          <small class="text-muted">by Studio JQ</small>
        </div>
        <div class="card-footer bg-white border-0 d-flex justify-content-between">
          <span><i class="bi bi-eye"></i> 2,179</span>
          <span><i class="bi bi-heart"></i> 158</span>
        </div>
      </div>
    </div>

    <!-- More cards... -->
    <div class="col-12 col-sm-6 col-md-4 col-lg-3">
      <div class="card h-100">
        <img src="images/u3.jpg" class="card-img-top" alt="Design 3">
        <div class="card-body">
          <h6 class="card-title mb-1">Portfolio Concept</h6>
          <small class="text-muted">by Romain T.</small>
        </div>
        <div class="card-footer bg-white border-0 d-flex justify-content-between">
          <span><i class="bi bi-eye"></i> 1,872</span>
          <span><i class="bi bi-heart"></i> 148</span>
        </div>
      </div>
    </div>

    <div class="col-12 col-sm-6 col-md-4 col-lg-3">
      <div class="card h-100">
        <img src="images/u4.jpg" class="card-img-top" alt="Design 3">
        <div class="card-body">
          <h6 class="card-title mb-1">Portfolio Concept</h6>
          <small class="text-muted">by Romain T.</small>
        </div>
        <div class="card-footer bg-white border-0 d-flex justify-content-between">
          <span><i class="bi bi-eye"></i> 1,872</span>
          <span><i class="bi bi-heart"></i> 148</span>
        </div>
      </div>
    </div>

    <div class="col-12 col-sm-6 col-md-4 col-lg-3">
      <div class="card h-100">
        <img src="images/u5.jpg" class="card-img-top" alt="Design 3">
        <div class="card-body">
          <h6 class="card-title mb-1">Portfolio Concept</h6>
          <small class="text-muted">by Romain T.</small>
        </div>
        <div class="card-footer bg-white border-0 d-flex justify-content-between">
          <span><i class="bi bi-eye"></i> 1,872</span>
          <span><i class="bi bi-heart"></i> 148</span>
        </div>
      </div>
    </div>

    <div class="col-12 col-sm-6 col-md-4 col-lg-3">
      <div class="card h-100">
        <img src="images/U1.jpg" class="card-img-top" alt="Design 3">
        <div class="card-body">
          <h6 class="card-title mb-1">Portfolio Concept</h6>
          <small class="text-muted">by Romain T.</small>
        </div>
        <div class="card-footer bg-white border-0 d-flex justify-content-between">
          <span><i class="bi bi-eye"></i> 1,872</span>
          <span><i class="bi bi-heart"></i> 148</span>
        </div>
      </div>
    </div>

    <!-- Add or duplicate more cards here -->
  </div>
</div>

<!-- Footer -->
<footer class="footer text-center">
  <div class="container">
    <p>&copy; 2025 Dribbble Clone. Built for educational purposes using Bootstrap.</p>
  </div>
</footer>

<!-- Scripts -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>



## OUTPUT:

![image](https://github.com/user-attachments/assets/7418ec15-0454-413a-8b86-af78f5521f0f)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
