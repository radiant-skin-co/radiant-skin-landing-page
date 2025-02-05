# radiant-skin-landing-page
/* Global Styles */
body {
  font-family: 'Roboto', sans-serif;
  color: #333;
  background-color: #f8f8f8;
  margin: 0;
  padding: 0;
}

header {
  background-color: #fff;
  padding: 1rem;
  text-align: center;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

header h1 {
  font-size: 2.5rem;
  color: #e91e63; /* Soft Pink */
  margin: 0;
}

header p {
  font-size: 1.2rem;
  color: #666;
  margin: 0.5rem 0;
}

header nav {
  margin-top: 1rem;
}

header nav a {
  color: #333;
  text-decoration: none;
  margin: 0 0.5rem;
  font-size: 1rem;
}

header nav a:hover {
  color: #e91e63; /* Soft Pink */
}

/* Product Sections */
section {
  background-color: #fff;
  padding: 2rem;
  margin: 1rem auto;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.product-header h1 {
  font-size: 2.5rem;
  color: #333;
}

.subheadline {
  font-size: 1.2rem;
  color: #666;
}

.price {
  font-size: 1.5rem;
  color: #e91e63; /* Soft Pink */
}

.cta-button {
  background-color: #e91e63; /* Soft Pink */
  color: #fff;
  padding: 0.8rem 1.5rem;
  border-radius: 5px;
  text-decoration: none;
  display: inline-block;
  margin-top: 1rem;
}

.learn-more {
  display: inline-block;
  margin-top: 0.5rem;
  color: #e91e63; /* Soft Pink */
  text-decoration: underline;
}

.learn-more:hover {
  color: #c2185b;
}

.key-benefits ul {
  list-style: none;
  padding: 0;
}

.key-benefits li {
  background-color: #f8f8f8;
  margin: 0.5rem 0;
  padding: 0.8rem;
  border-radius: 5px;
}

.clinical-results {
  margin-top: 2rem;
}

.before-after {
  display: flex;
  gap: 1rem;
  margin-top: 1rem;
}

.before-after img {
  width: 45%;
  border-radius: 10px;
}

.ingredients-highlight ul {
  list-style: none;
  padding: 0;
}

.ingredients-highlight li {
  background-color: #f8f8f8;
  margin: 0.5rem 0;
  padding: 0.8rem;
  border-radius: 5px;
}

.how-to-use ol {
  list-style: none;
  padding: 0;
}

.how-to-use li {
  background-color: #f8f8f8;
  margin: 0.5rem 0;
  padding: 0.8rem;
  border-radius: 5px;
}

/* Footer */
footer {
  background-color: #333;
  color: #fff;
  padding: 1rem;
  text-align: center;
  margin-top: 2rem;
}

footer a {
  color: #e91e63; /* Soft Pink */
  text-decoration: none;
}

footer a:hover {
  color: #c2185b;
}

/* Mobile Optimization */
@media (max-width: 768px) {
  header h1 {
    font-size: 2rem;
  }

  header p {
    font-size: 1rem;
  }

  header nav a {
    font-size: 0.9rem;
    margin: 0 0.3rem;
  }

  .product-header h1 {
    font-size: 2rem;
  }

  .subheadline {
    font-size: 1rem;
  }

  .price {
    font-size: 1.2rem;
  }

  .cta-button {
    padding: 0.6rem 1.2rem;
    font-size: 0.9rem;
  }

  .learn-more {
    font-size: 0.9rem;
  }

  .key-benefits li, .how-to-use li, .ingredients-highlight li {
    font-size: 0.9rem;
    padding: 0.6rem;
  }
}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Radiant Skin & Co.</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Radiant Skin & Co.</h1>
    <p>Your Path to Radiant Skin</p>
    <nav>
      <a href="#relief-cream">345 Relief Cream</a>
      <a href="#cleansing-oil">Cleansing Oil</a>
      <a href="#anua-serum">Anua Serum</a>
      <a href="#rice-toner">Rice Toner</a>
      <a href="#bundles">Bundles</a>
    </nav>
  </header>

  <section id="relief-cream">
    <div class="product-header">
      <h1>345 Relief Cream</h1>
      <p class="subheadline">Your Daily Dose of Soothing Care</p>
      <p class="price">$27.00</p>
      <a href="https://amzn.to/4hnx7JO" class="cta-button" target="_blank">Buy Now on Amazon</a>
      <a href="https://amzn.to/4hnx7JO" class="learn-more" target="_blank">Learn More</a>
    </div>
    <div class="key-benefits">
      <h2>Key Benefits</h2>
      <ul>
        <li>Reduces dark spots and blemishes with Niacinamide.</li>
        <li>Soothes sensitive skin with Panthenol and Beta-glucan.</li>
        <li>Locks in moisture with Ceramide NP and Hyaluronic Acid.</li>
        <li>Vegan, paraben-free, and fragrance-free.</li>
      </ul>
    </div>
    <div class="clinical-results">
      <h2>Clinical Results</h2>
      <p>Improves skin clarity and radiance after just <strong>2 weeks</strong> of use.</p>
      <div class="before-after">
        <img src="images/before-serum.jpg" alt="Before Use">
        <img src="images/after-serum.jpg" alt="After 2 Weeks">
      </div>
    </div>
    <div class="how-to-use">
      <h2>How to Use</h2>
      <ol>
        <li>Apply a small amount to clean skin.</li>
        <li>Gently pat into the skin until fully absorbed.</li>
        <li>Use morning and night for best results.</li>
      </ol>
    </div>
  </section>

  <!-- Add more product sections here -->

  <footer>
    <p>As an Amazon Associate, I earn from qualifying purchases.</p>
    <p><a href="/privacy-policy">Privacy Policy</a> | <a href="/terms-of-service">Terms of Service</a></p>
  </footer>
</body>
</html>
