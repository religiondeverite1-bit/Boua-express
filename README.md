# Boua-express
Site commerciale
index.html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Boua Express - Bafster</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f8f8f8; }
    header { background: #222; color: white; padding: 20px; text-align: center; }
    h1 { margin: 0; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; padding: 20px; }
    .product { background: white; border-radius: 8px; padding: 16px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); }
    .product img { width: 100%; height: 200px; object-fit: cover; border-radius: 4px; }
    .product h2 { font-size: 18px; margin: 10px 0 5px; }
    .product p { margin: 5px 0; font-size: 14px; }
    .btn { display: inline-block; margin-top: 10px; padding: 8px 12px; background: #25D366; color: white; border-radius: 5px; text-decoration: none; font-weight: bold; }
    footer { background: #222; color: white; text-align: center; padding: 10px; }
  </style>
</head>
<body>
  <header>
    <h1>Bafster - Boua Express</h1>
    <p>Vente de produits électriques, électroniques, tissus et plus...</p>
  </header>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/250x200.png?text=Fer+%C3%A0+repasser" alt="Fer à repasser">
      <h2>Fer à repasser électrique</h2>
      <p>Prix : 12 000 FCFA</p>
      <a class="btn" href="https://wa.me/22399009057?text=Je%20veux%20acheter%20le%20fer%20%C3%A0%20repasser">Commander</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200.png?text=Multim%C3%A8tre" alt="Multimètre">
      <h2>Multimètre numérique</h2>
      <p>Prix : 8 500 FCFA</p>
      <a class="btn" href="https://wa.me/22399009057?text=Je%20veux%20acheter%20le%20multim%C3%A8tre">Commander</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200.png?text=Tissu+Bazin" alt="Tissu Bazin">
      <h2>Tissu Bazin Riche</h2>
      <p>Prix : 6 000 FCFA / mètre</p>
      <a class="btn" href="https://wa.me/22399009057?text=Je%20veux%20acheter%20le%20tissu%20bazin">Commander</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x200.png?text=Lampe+LED" alt="Lampe LED">
      <h2>Lampe LED Rechargeable</h2>
      <p>Prix : 3 000 FCFA</p>
      <a class="btn" href="https://wa.me/22399009057?text=Je%20veux%20acheter%20la%20lampe%20LED">Commander</a>
    </div>
  </section>

  <footer>
    <p>Contact : 99 00 90 57 | Boua Express &copy; 2025</p>
  </footer>
</body>
</html>
