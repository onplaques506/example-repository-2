<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>58 Flavous - Siaya Gem</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #fdfdfd;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #ff416c, #ff4b2b);
      color: white;
      padding: 30px;
      text-align: center;
    }
    nav {
      background: #fff;
      display: flex;
      justify-content: center;
      gap: 40px;
      padding: 15px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    nav a {
      color: #ff4b2b;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px;
      text-align: center;
    }
    .flavors {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      margin-top: 30px;
    }
    .flavor {
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.05);
      padding: 20px;
      transition: transform 0.3s;
    }
    .flavor:hover {
      transform: scale(1.05);
    }
    .flavor img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 8px;
    }
    footer {
      background: #ff4b2b;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>58 Flavous 🍦</h1>
    <p>Mautamu Spot - Flavours You’ll Never Forget</p>
    <p>Fresh & Flavourful - Siaya Gem, Odera Okango Campus</p>
  </header>

  <nav>
    <a href="#strawberry">Strawberry</a>
    <a href="#vanilla">Vanilla</a>
    <a href="#chocolate">Chocolate</a>
  </nav>

  <section id="strawberry">
    <h2>Strawberry Flavour</h2>
    <div class="flavors">
      <div class="flavor">
        <img src="images/strawberry-tumbler.jpg" alt="Strawberry Ice Cream">
        <h3>Sweet Strawberry</h3>
        <p>Made with real strawberries picked fresh from local gardens, served in chilled tumblers.</p>
      </div>
    </div>
  </section>

  <section id="vanilla">
    <h2>Vanilla Flavour</h2>
    <div class="flavors">
      <div class="flavor">
        <img src="images/vanilla-tumbler.jpg" alt="Vanilla Ice Cream">
        <h3>Classic Vanilla</h3>
        <p>Rich, creamy and timeless – our vanilla is a local favourite served in stylish tumblers.</p>
      </div>
    </div>
  </section>

  <section id="chocolate">
    <h2>Chocolate Flavour</h2>
    <div class="flavors">
      <div class="flavor">
        <img src="images/chocolate-tumbler.jpg" alt="Chocolate Ice Cream">
        <h3>Dark Chocolate</h3>
        <p>Deep and smooth – every bite melts with cocoa goodness, served in premium ice cream cups.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 58 Flavous | Mautamu Spot - Siaya Gem, Odera Okango Campus</p>
    <p>Follow us on IG @58flavous & WhatsApp Orders: +254792910360</p>
  </footer>
</body>
</html>
