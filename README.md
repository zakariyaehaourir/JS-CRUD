<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - CRUD avec LocalStorage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2 {
            color: #2c3e50;
        }
        ul {
            margin-left: 20px;
        }
        li {
            margin-bottom: 10px;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <h1>CRUD avec LocalStorage</h1>
    <p>
        Cette application JavaScript simple permet de gérer une liste de produits avec les opérations CRUD (Créer, Lire, Mettre à jour, Supprimer) en utilisant le <strong>LocalStorage</strong> pour la persistance des données.
    </p>
    
    <h2>Fonctionnalités</h2>
    <ul>
        <li>Ajouter un nouveau produit avec un libellé et un prix unitaire.</li>
        <li>Afficher une liste des produits enregistrés.</li>
        <li>Mettre à jour les informations d’un produit existant.</li>
        <li>Supprimer un produit spécifique ou tous les produits.</li>
        <li>Rechercher des produits par leur libellé grâce à une barre de recherche.</li>
        <li>Notifications visuelles pour confirmer les actions (ajout, modification, suppression).</li>
    </ul>

    <h2>Technologies Utilisées</h2>
    <ul>
        <li><strong>HTML</strong> : Structure de la page et formulaire d'ajout.</li>
        <li><strong>CSS</strong> : Design minimaliste et responsive.</li>
        <li><strong>JavaScript</strong> : Gestion des opérations CRUD et interactions utilisateur.</li>
        <li><strong>LocalStorage</strong> : Persistance des données côté client.</li>
    </ul>

    <h2>Comment l'utiliser ?</h2>
    <ol>
        <li>Cloner ou télécharger le projet depuis le dépôt GitHub.</li>
        <li>Ouvrir le fichier <strong>index.html</strong> dans votre navigateur.</li>
        <li>Utiliser le formulaire pour ajouter, modifier ou supprimer des produits.</li>
    </ol>

    <h2>Structure du Projet</h2>
    <pre>
    ├── index.html
    ├── styles.css (optionnel pour le design)
    ├── script.js
    </pre>

    <h2>Aperçu</h2>
    <p>Voici un aperçu visuel de l'interface utilisateur :</p>
    <ul>
        <li><strong>Formulaire d'ajout :</strong> Saisie du libellé et du prix du produit.</li>
        <li><strong>Tableau des produits :</strong> Affiche les produits avec des boutons d'action (modifier/supprimer).</li>
        <li><strong>Barre de recherche :</strong> Filtre les produits en fonction du libellé saisi.</li>
    </ul>

    <h2>Contact</h2>
    <p>Pour toute question ou suggestion, n'hésitez pas à me contacter via mon dépôt GitHub :</p>
    <p>
        <a href="https://github.com/zakariyaehaourir/JS-CRUD" target="_blank">https://github.com/zakariyaehaourir/JS-CRUD</a>
    </p>
</body>
</html>
