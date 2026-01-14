<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exterior Cleaning Services</title>
  <style>
    /* Reset & basics */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
    body { line-height: 1.6; color: #333; }

    /* Header / Hero */
    header {
      background: #4CAF50;
      color: white;
      text-align: center;
      padding: 80px 20px;
    }
    header h1 { font-size: 2.5em; margin-bottom: 10px; }
    header p { font-size: 1.2em; margin-bottom: 20px; }
    header a {
      background: #fff;
      color: #4CAF50;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    /* Sections */
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 40px;
      font-size: 2em;
      color: #4CAF50;
    }
    p { text-align: center; max-width: 700px; margin: auto 0 20px; }

    /* Services */
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .service {
      flex: 1 1 200px;
      background: #f4f4f4;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }

    /* Gallery */
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
    }
    .gallery img {
      width: 200px;
      border-radius: 10px;
    }

    /* Testimonials */
    .testimonial {
      background: #f9f9f9;
      padding: 20px;
      margin: 20px auto;
      max-width: 600px;
      border-radius: 10px;
      font-style: italic;
      text-align: center;
    }

    /* Contact */
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 400px;
      margin: auto;
    }
    input, textarea {
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
      width: 100%;
    }
    button {
      padding: 10px;
      border: none;
      background: #4CAF50;
      color: white;
      font-weight: bold;
      cursor: pointer;
      border-radius: 5px;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background: #333;
      color: white;
    }

    /* Responsive */
    @media(max-width: 768px) {
      .services { flex-direction: column; align-items: center; }
      .gallery img { width: 100%; max-width: 300px; }
    }
  </style>
</head>
<body>

  <!-- Header / Hero -->
  <header>
    <h1>Exterior Cleaning Services</h1>
    <p>Professional cleaning in Coventry & Hinckley & Bosworth</p>
    <a href="#contact">Get a Free Quote</a>
  </header>

  <!-- About Us -->
  <section id="about">
    <h2>About Us</h2>
    <p>We provide reliable and high-quality exterior cleaning services. With years of experience, we ensure your property looks its best.</p>
  </section>

  <!-- Services -->
  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service">Exterior Building Cleaning</div>
      <div class="service">Driveway & Patio Cleaning</div>
      <div class="service">Roof & Gutter Cleaning</div>
      <div class="service">Window Cleaning</div>
    </div>
  </section>

  <!-- Gallery -->
  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/200" alt="Gallery Image 1">
      <img src="https://via.placeholder.com/200" alt="Gallery Image 2">
      <img src="https://via.placeholder.com/200" alt="Gallery Image 3">
      <img src="https://via.placeholder.com/200" alt="Gallery Image 4">
    </div>
  </section>

  <!-- Testimonials -->
  <section id="testimonials">
    <h2>Testimonials</h2>
    <div class="testimonial">"Lee and Marcus did an amazing job! Highly recommend."</div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Phone: 07423 630 477 | Marcus: 07405 401 481</p>
    <p>Email: <a href="mailto:penneylee244@gmail.com">penneylee244@gmail.com</a></p>
    <p>Areas Covered: Coventry & Hinckley & Bosworth</p>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2026 Exterior Cleaning Services. All rights reserved.
  </footer>

</body>
</html>
