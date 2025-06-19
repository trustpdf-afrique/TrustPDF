# TrustPDF
TrustPDF est une application de vente de PDF professionnel 
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TrustPDF| Boutique</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }
    header {
      background-color: #222;
      color: #fff;
      padding: 20px;
      text-align: center;
      position: relative;
    }
    header::after {
      content: "";
      display: block;
      height: 4px;
      background: linear-gradient(to right, #4caf50, #81c784);
      margin-top: 10px;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #fff;
      padding: 10px;
      gap: 20px;
      flex-wrap: wrap;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    .search {
      text-align: center;
      margin: 20px;
    }
    .search input {
      width: 80%;
      padding: 10px;
      font-size: 16px;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background-color: #fff;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 10px;
    }
    .price {
      font-size: 18px;
      font-weight: bold;
      color: #4caf50;
      margin: 10px 0 5px;
    }
    .note {
      font-size: 14px;
      color: #888;
      margin-bottom: 10px;
    }
    .author {
      font-size: 14px;
      color: #555;
      margin-bottom: 15px;
    }
    .card button {
      background-color: #4caf50;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
      margin-top: auto;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenue sur TrustPDF</h1>
  </header>
  <nav>
    <a href="#">Formations</a>
    <a href="#">eBooks</a>
  </nav>
  <div class="search">
    <input type="text" id="searchInput" placeholder="Rechercher un produit...">
  </div>
  <div class="container" id="productContainer">
    <div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 1">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
 Comment générer 100.000 FCFA par semaine avec ton téléphone 
</p>
      <div class="price">1500 FCFA</div>
      <div class="note">⭐4.0</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/comment-generer-100-000-fcfa-par-semaine-avec-ton-telephone-en-2025_1750034626690/" target="_blank">
  <button>Acheter maintenant</button>
</a>
    </div>
    <div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Résumé ultra simple gagner de l'argent en ligne 2025
</p>
      <div class="price">1000 FCFA</div>
      <div class="note">⭐4.7</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/resume-ultra-simple-gagner-de-largent-en-ligne-2025_1750034951105/"target="_blank">
<button>Acheter maintenant</button>
</a>
    </div>
    <div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 3">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Créer et vendre des ebooks en automatique avec ton téléphone 
</p>
      <div class="price">1500 FCFA</div>
      <div class="note">⭐4.1</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/creer-et-vendre-des-ebooks-en-automatique-avec-ton-telephone_1750035102057/"target="_blank">
<button>Acheter maintenant</button>
</a>
    </div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  10 meilleures façons de gagner de l'argent avec son téléphone 
</p>
      <div class="price">1000 FCFA</div>
      <div class="note">⭐4.8</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/les-10-meilleures-facons-de-gagner-de-largent-avec-son-telephone_1750035203591/"target="_blank">
<button>Acheter maintenant</button>
</a>
 </div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Transformer tes idées en PDF à vendre 
</p>
      <div class="price">1500 FCFA</div>
      <div class="note">⭐4.9</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/transformer-tes-idees-en-pdf-a-vendre_1750064242624/"target="_blank">
<button>Acheter maintenant</button>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Réjoignez le réseau 3h18 et accédez à des missions 
</p>
      <div class="price">2000 FCFA</div>
      <div class="note">⭐4.0</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/rejoignez-le-reseau-3h18-et-accedez-a-des-missions_1750064315079/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Publicités ultra rentable sur tiktok, Facebook en 2025
</p>
      <div class="price">2000 FCFA</div>
      <div class="note">⭐4.8</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/publicites-ultra-rentables-sur-tiktok-facebook-en-2025_1750064381700/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Pack e-commerce boutique en ligne 2025
</p>
      <div class="price">5000 FCFA</div>
      <div class="note">⭐4.8</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/pack-ecommerce-2025-boutique_1750064465034/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
 Meilleures idées de vidéos tiktok pour percer en 2025
</p>
      <div class="price">1500 FCFA</div>
      <div class="note">⭐4.0</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/les-meilleures-idees-de-videos-tiktok-pour-percer-en-2025_1750065066356/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Le plan marketing en une seule page 
</p>
      <div class="price">1000 FCFA</div>
      <div class="note">⭐3.8</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/le-plan-marketing-en-une-seule-page-_1750064983812/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Lancer une formation en ligne avec ton téléphone en 2025
</p>
      <div class="price">1500 FCFA</div>
      <div class="note">⭐4.5</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/lancer-une-formation-en-ligne-avec-ton-telephone-en-2025_1750065998671/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
 Formation complet le guide ultime de l'intelligence artificielle en 2025
</p>
      <div class="price">4000 FCFA</div>
      <div class="note">⭐4.9</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/formation-complete-le-guide-ultime-de-lintelligence-artificielle-en-2025_1750066066166/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Créer et vendre des formations 2025
</p>
      <div class="price">1000 FCFA</div>
      <div class="note">⭐4.5</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/creer-et-vendre-des-formations-2025_1750066142817/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Créer un business avec les fiches tiktok 
</p>
      <div class="price">1000 FCFA</div>
      <div class="note">⭐4.0</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/creer-un-business-avec-les-fiches-tiktok_1750066271921/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Créer et vendre des ebooks en automatique avec ton téléphone 
</p>
      <div class="price">2000 FCFA</div>
      <div class="note">⭐4.7</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/creer-et-vendre-des-ebooks-en-automatique-avec-ton-telephone_1750067669471/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Comment vivre d'un compte tiktok en Afrique 
</p>
      <div class="price">2500 FCFA</div>
      <div class="note">⭐4.6</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/comment-vivre-dun-compte-tiktok-en-afrique_1750067894502/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Comment gagner 10.000 FCFA en 7 jours
</p>
      <div class="price">1500 FCFA</div>
      <div class="note">⭐4.5</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/comment-gagner-10-000-fcfa-en-7-jours_1750067986152/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Comment fonctionne l'algorithme tiktok pour maximiser tes vues en 2025
</p>
      <div class="price">5000 FCFA</div>
      <div class="note">⭐4.8</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/comment-fonctionne-lalgorithme-tiktok-pour-maximiser-tes-vues-en-2025_1750068084264/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Activer la monétisation tiktok en Afrique 2025
</p>
      <div class="price">2000 FCFA</div>
      <div class="note">⭐4.5</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/activer-la-monetisation-tiktok-en-afrique-2025_1750068243913/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  7 idées de vidéos tiktok qui vont te rendre populaire 
</p>
      <div class="price">2000 FCFA</div>
      <div class="note">⭐4.9</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/7-idees-de-videos-tiktok-qui-vont-te-rendre-populaire_1750076744958/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  10 erreurs graves que font les tiktokeurs débutants en 2025
</p>
      <div class="price">2000 FCFA</div>
      <div class="note">⭐4.5</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/10-erreurs-graves-que-font-les-tiktokeurs-debutants-en-2025_1750076494756/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  10 conseils puissants pour bien gérer tes réseaux sociaux en 2025
</p>
     <div class="price">2000 FCFA</div>
      <div class="note">⭐4.6</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/10-conseils-puissants-pour-bien-gerer-tes-reseaux-en-2025_1750076562964/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  10 bonnes pratiques pour utiliser les réseaux sociaux en 2025
</p>
      <div class="price">2000 FCFA</div>
      <div class="note">⭐4.6</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/10-bonnes-pratiques-pour-utiliser-les-reseaux-sociaux-en-2025_1750076626495/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Pack comment créer une application
</p>
      <div class="price">5000 FCFA</div>
      <div class="note">⭐4.8</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/pack-comment-creer-une-application-mobile_1750077509334/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Formation devenir influenceur rentable sans des millions d'abonnés
</p>
      <div class="price">2500 FCFA</div>
      <div class="note">⭐4.5</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/formation---devenir-influenceur-rentable-sans-des-millions-dabonnes-_1750077617174/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  Comment avoir beaucoup de vues sur tiktok en 2025
</p>
      <div class="price">2500 FCFA</div>
      <div class="note">⭐4.7</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/comment-avoir-beaucoup-de-vues-sur-tiktok-en-2025_1750081733423/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; color: black; text-align: center;">
  10 meilleures conseils aux femmes pour prendre soin d'elle-même 
</p>
    <div class="price">2000 FCFA</div>
      <div class="note">⭐4.7</div>
      <div class="author">trustPDF</div>
      <a href="https://www.pay.moneyfusion.net/les-10-meilleurs-conseils-aux-femmes-pour-prendre-soin-delles-memes_1750081846296/"target="_blank">
<button>Acheter maintenant</button>
</a>
</div>
<div class="card">
      <img src="https://i.postimg.cc/5tTmJBgK/Publication-Instagram-1er-mai-F-te-du-Travail-Moderne-Orange-et-Jaune-20250615-225820-0000.png="Produit 2">
<p style="font-size: 18px; font-weight: bold; font-family: 'Georgia', serif; col
