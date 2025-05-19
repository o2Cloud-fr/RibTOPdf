# 🏦 RIB Generator - Générateur de Relevés d'Identité Bancaire

**RIB Generator** est une application web PHP qui permet de créer et personnaliser des Relevés d'Identité Bancaire (RIB) au format PDF. Simple d'utilisation et élégante, elle offre une solution pratique pour générer des RIB professionnels avec une personnalisation visuelle.

![Banner](https://o2cloud.fr/logo/o2Cloud.png)

## ✨ Fonctionnalités

- 📝 **Création de RIB personnalisés** - Générez des RIB avec vos informations bancaires
- 🎨 **Personnalisation visuelle** - Choisissez la couleur du RIB pour s'adapter à votre identité visuelle
- 🖼️ **Support de logo** - Ajoutez le logo de votre banque ou votre propre logo
- 🔍 **Aperçu en temps réel** - Visualisez le RIB avant de le télécharger
- 📊 **Mise en page professionnelle** - Format structuré et conforme aux standards
- 🖨️ **Export en PDF** - Générez des documents PDF de haute qualité
- 💼 **Format portable** - Partagez facilement vos coordonnées bancaires

## 📋 Pré-requis

- Serveur web avec PHP 7.4 ou supérieur
- Composer (gestionnaire de dépendances PHP)
- Extension PHP FileInfo activée
- Extension PHP GD pour le traitement des images
- Permissions d'écriture pour le dossier "uploads"

## 🚀 Installation

1. Clonez le dépôt sur votre serveur web
```bash
git clone https://github.com/RibTOPdf/RibTOPdf.git
```

2. Accédez au répertoire du projet
```bash
cd RibTOPdf
```

3. Installez les dépendances via Composer
```bash
composer require dompdf/dompdf
composer install
```

4. Créez le dossier uploads et donnez-lui les permissions nécessaires
```bash
mkdir uploads
chmod 777 uploads
```

5. Accédez à l'application via votre navigateur
```
https://RibTOPdf.o2Cloud.fr/
```

## 📚 Fonctionnement

RIB Generator utilise le package Dompdf pour générer des PDF à partir de modèles HTML/CSS. L'application est structurée autour de :

- Un **formulaire interactif** pour la saisie des informations bancaires
- Un **sélecteur de couleur** pour personnaliser l'apparence du RIB
- Un système de **prévisualisation** en temps réel
- Un moteur de **génération PDF** pour exporter le RIB au format PDF

## 👨‍💻 Auteurs

- [@votre-utilisateur-github](https://www.github.com/RibTOPdf)

## 🔖 Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)](https://github.com/votre-utilisateur/rib-generator)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://github.com/votre-utilisateur/rib-generator)
[![Dompdf](https://img.shields.io/badge/Dompdf-PDF_Generation-red)](https://github.com/votre-utilisateur/rib-generator)

## 💬 Feedback

Si vous avez des commentaires ou des suggestions, n'hésitez pas à ouvrir une issue sur notre dépôt GitHub.

## 🔗 Liens

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/votre-profil/)
[![github](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/votre-utilisateur)

## 🛠️ Compétences

- PHP
- HTML/CSS
- Tailwind CSS
- JavaScript
- Génération de PDF (Dompdf)

## 📝 Licence

[MIT License](https://opensource.org/licenses/MIT)

## 🗺️ Feuille de route

- Ajout de modèles prédéfinis de RIB
- Support multilingue (anglais, espagnol, allemand)
- Stockage temporaire des RIB générés
- Génération par lot à partir d'un fichier CSV
- Interface d'administration pour les utilisateurs professionnels
- Intégration API pour générer des RIB programmatiquement

## 🆘 Support

Pour obtenir de l'aide, ouvrez une issue sur notre dépôt GitHub ou contactez-nous par email : github@o2cloud.fr

## 💼 Utilisé par

Cette application est idéale pour :

- Les travailleurs indépendants et freelances devant fournir leurs coordonnées bancaires
- Les petites entreprises souhaitant générer des RIB personnalisés
- Les associations et organismes nécessitant des RIB pour leurs adhérents
- Les comptables et gestionnaires devant préparer des documents bancaires
