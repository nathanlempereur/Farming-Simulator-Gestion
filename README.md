# 🚜 Farming Simulator Gestion - Gestionnaire de Cultures & Calculateur

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-En%20D%C3%A9veloppement-orange)

<img width="1919" height="792" alt="image" src="https://github.com/user-attachments/assets/05ca17ee-899f-4f6f-8820-41d7947d9d67" />

## Description

**Farming Simulator Gestion** est une application web statique (Front-end) conçue pour aider les joueurs de *Farming Simulator* à optimiser leur économie agricole le mieu possible. 

L'outil permet de visualiser rapidement les périodes de semis et de récolte, d'identifier les meilleurs mois pour vendre ses stocks, et de calculer instantanément la rentabilité d'une récolte en fonction des prix du marché fluctuants.

## Fonctionnalités Principales

* ** Tableau de Bord des Cultures :** Liste complète des cultures (Blé, Orge, Soja, etc.) avec leurs périodes de semis, de récolte et le mois de revente optimal.
* ** Recherche & Tri Dynamique :** Filtrage instantané des cultures et tri des colonnes (par nom ou par mois chronologique) sans rechargement de page.
* ** Calculateur de Revenus :** Outil intégré pour estimer le gain total selon la quantité (Litres) et le cours actuel du marché (€/1000L).
* ** Visualisation Graphique :** Courbes de fluctuation des prix interactives (via Chart.js) pour analyser les tendances du marché.
* ** Design Responsive :** Interface adaptée aux écrans de bureau, tablettes et mobiles pour une utilisation en "second écran" pendant le jeu.

## Stack Technique

Le projet est construit en technologies Web standards, sans framework lourd, pour garantir légèreté et facilité de modification.

| Technologie | Usage |
| :--- | :--- |
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Structure sémantique de la page |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Design personnalisé, Flexbox, Variables CSS |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Logique de calcul, tri du tableau et interactivité |
| **Chart.js** | Librairie pour le rendu des graphiques |
| **FontAwesome** | Icônes vectorielles (Interface & Navigation) |

## Installation & Démarrage

Ce projet étant un site statique (HTML/CSS/JS pur), il ne nécessite **aucun serveur** (comme Apache ou Nginx) ni environnement complexe (Node.js, PHP) pour fonctionner en local.

### Prérequis
* Un navigateur web (Chrome, Firefox, Edge, Safari).
* Git (optionnel, pour cloner le dépôt).

### Méthode 1 : Via Git (Recommandé)
1.  Ouvrez votre terminal.
2.  Clonez le dépôt :
    ```bash
    git clone [URL du projet github]
    ```
3.  Accédez au dossier :
    ```bash
    cd farming-simulator-gestion
    ```
4.  Lancez le fichier `index.html` (double-clic).

### Méthode 2 : Téléchargement manuel
1.  Cliquez sur le bouton **Code** (en vert) en haut de la page GitHub.
2.  Sélectionnez **Download ZIP**.
3.  Extrayez le fichier ZIP sur votre ordinateur.
4.  Double-cliquez sur le fichier `index.html`.

---

## Guide d'Utilisation

L'interface a été pensée pour être utilisée sur un second écran pendant vos sessions de jeu.

### 1. Tableau de Bord Dynamique
* **Recherche Rapide :** Utilisez la barre de recherche située au-dessus du tableau pour filtrer instantanément les cultures par nom (ex: tapez "Soja" pour ne voir que cette ligne).
* **Tri Intelligent :** Cliquez sur les en-têtes de colonnes (*Type, Semence, Récolte...*) pour trier les données.
    * *Note : Le tri des mois respecte l'ordre chronologique (Janvier avant Février) et non l'ordre alphabétique.*
    * 
<img width="1920" height="739" alt="image" src="https://github.com/user-attachments/assets/fc5c230e-cc83-4374-860a-4b89259fe305" />


### 2. Calculatrice de Rentabilité
Utilisez cet outil pour savoir exactement combien votre remorque va vous rapporter.
1.  **Champ Quantité :** Entrez le volume total de votre récolte en Litres (ex: `15000`).
2.  **Champ Prix :** Entrez le prix actuel du marché pour 1000L tel qu'affiché dans le menu du jeu (ex: `350`).
3.  **Résultat :** Le revenu total estimé s'affiche automatiquement et en temps réel.

<img width="1920" height="790" alt="image" src="https://github.com/user-attachments/assets/0e38178a-861c-4a10-8b2c-b9548813d4a0" />


### 3. Graphiques de Fluctuation
* Passez votre souris sur les points de la courbe pour voir l'indice de prix précis mois par mois (échelle de 0 à 10).

<img width="1920" height="790" alt="image" src="https://github.com/user-attachments/assets/2d608665-7cd4-4316-af82-7b384bc55c87" />


## Contribution & Licence 

**Nathan Lempereur** - Étudiant en BTS SIO SISR
* [GitHub](https://github.com/nathanlempereur)
* [LinkedIn](https://www.linkedin.com/in/nathan-lempereur-989624373)
* [Site Web](https://nlempereur.ovh)

  Ce projet a été conçu dans un but pédagogique et est Open-Source, vous pouvez le modifier, l’améliorer et proposer des mises à jour.

---

© 2026 Nathan Lempereur — Tous droits réservés
