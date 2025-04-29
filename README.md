<!-- DEVELOPER: Olumuyiwa Akinde, IS117-004, Fall 2024 -->
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Photography Hobby</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="index.html">Photography Hobby</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" href="index.html">Home</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown">Content</a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="gallery.html">Gallery</a></li>
            <li><a class="dropdown-item" href="tips.html">Tips & Tricks</a></li>
            <li><a class="dropdown-item" href="gear.html">Gear</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<header class="bg-primary text-white text-center p-5">
  <h1>Welcome to My Photography World!</h1>
  <p>Capturing moments one click at a time.</p>
</header>

<!-- Main Content -->
<div class="container my-5">
  <div class="row">
    <div class="col-md-4">
      <div class="card">
        <img src="images/photo1.jpg" class="card-img-top" alt="Nature">
        <div class="card-body">
          <h5 class="card-title">Nature Photography</h5>
          <p class="card-text">Discover the beauty of the outdoors through a camera lens.</p>
          <a href="gallery.html" class="btn btn-primary">Explore Gallery</a>
        </div>
      </div>
    </div>

    <div class="col-md-4">
      <div class="card">
        <img src="images/photo2.jpg" class="card-img-top" alt="Portrait">
        <div class="card-body">
          <h5 class="card-title">Portrait Photography</h5>
          <p class="card-text">Learn how to capture the perfect expression and mood.</p>
          <a href="tips.html" class="btn btn-primary">Learn Tips</a>
        </div>
      </div>
    </div>

    <div class="col-md-4">
      <div class="card">
        <img src="images/photo3.jpg" class="card-img-top" alt="Gear">
        <div class="card-body">
          <h5 class="card-title">Photography Gear</h5>
          <p class="card-text">Find out what gear you need to take your shots to the next level.</p>
          <a href="gear.html" class="btn btn-primary">Check Gear</a>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="bg-dark text-white text-center p-3">
  <p>&copy; 2025 Olumuyiwa Akinde, oa356. All rights reserved.</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
