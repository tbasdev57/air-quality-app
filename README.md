

# Air Quality App

## Description

**Air Quality App** est une application web permettant de consulter la qualité de l'air dans différentes villes à travers le monde en utilisant l'**API IQAir**. Elle affiche l'indice de qualité de l'air (AQI) en temps réel, ainsi que des informations détaillées sur les polluants présents dans l'air.

## Fonctionnalités

- **Sélection de ville** : Choisir une ville pour afficher son indice de qualité de l'air.
- **Affichage de l'Indice AQI** : Afficher l'indice AQI et sa description (bon, modéré, mauvais, etc.).
- **Détails des polluants** : Afficher les niveaux de PM2.5, PM10, CO, etc.
- **Changement de VPN** : Changer automatiquement de VPN selon la ville ou le pays sélectionné.

## Installation

### Prérequis

Avant de commencer, assurez-vous d'avoir installé :

- **Node.js** : [Télécharge Node.js ici](https://nodejs.org/)
- **npm (Node Package Manager)** : npm est installé avec Node.js. Vérifiez son installation avec `npm -v`.

### Étapes d'installation

1. **Clone le dépôt** :

   ```bash
   git clone https://github.com/tbasdev57/air-quality-app.git
   ```

2. **Accède au dossier du projet** :

   ```bash
   cd air-quality-app
   ```

3. **Installe les dépendances** :

   ```bash
   npm install
   ```

4. **Lance l'application** :

   ```bash
   npm start
   ```

   L'application sera ouverte dans votre navigateur par défaut.

### Obtenir une clé API IQAir

1. Va sur le site IQAir : [IQAir API](https://www.iqair.com/world-air-quality).
2. Crée un compte ou connecte-toi à ton compte IQAir.
3. Accède à la section API et génère une clé API.
4. Copie la clé API et colle-la dans ton fichier `app.js` (ou un fichier similaire) en remplaçant la variable `apiKey` :

   ```javascript
   const apiKey = 'TA_CLE_API_IQAIR'; // Remplace par ta propre clé API IQAir
   ```

---
