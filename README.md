![image](https://github.com/user-attachments/assets/6071e46f-ba6b-43ce-a8fd-474f9d32d4d6)## À propos du projet: Dashboard-laravel-tailwindcss-breeze

Ce projet est une application web développée avec le framework Laravel. Il intègre diverses dépendances pour améliorer le développement et les fonctionnalités, notamment Tailwind CSS pour le style, Alpine.js pour les interactions, et Vite pour la gestion des modules.

![01](https://github.com/user-attachments/assets/70db6870-c87c-4659-9ac7-11a898a0c62a)
![02](https://github.com/user-attachments/assets/b5909782-a983-48f6-9207-00768891de2a)

## Prérequis

- **PHP** : version 8.2 ou supérieure
- **Composer** : pour la gestion des dépendances PHP
- **Node.js et npm** : pour la gestion des dépendances JavaScript
- **Base de données** : MySQL, PostgreSQL ou autre, selon votre configuration

## Installation

1. **Cloner le dépôt** :

   ```bash
   git clone https://github.com/rosto-infinity/dashboard-laravel-tailwindcss.git
   cd dashboard-laravel-tailwindcss

2. **Installer les dépendances PHP** :
   ```bash
    composer install
    Installer les dépendances JavaScript :

3. **Copier le fichier .env.example en .env** :
 
cp .env.example .env

 - **Modifier les paramètres du fichier .env selon votre configuration (base de données, mail, etc.).**

4. **Générer la clé de l'application :** :

 ```bash
 php artisan key:generate :

5. **Exécuter les migrations de la base de données **


 ```bash
php artisan migrate
Compiler les assets :

En mode développement :

 ```bash
npm run dev
En mode production :


Démarrer le serveur de développement :

 ```bash
php artisan serve
L'application sera accessible à l'adresse http://localhost:8000.

Dépendances principales
Dépendances PHP :

laravel/framework : ^11.31
laravel/tinker : ^2.9
Dépendances PHP pour le développement :

fakerphp/faker : ^1.23
laravel/breeze : ^2.3
laravel/pail : ^1.1
laravel/pint : ^1.13
laravel/sail : ^1.26
mockery/mockery : ^1.6
nunomaduro/collision : ^8.1
phpunit/phpunit : ^11.0.1
Dépendances JavaScript :

@alpinejs/persist : ^3.12.0
apexcharts : ^3.36.3
flatpickr : ^4.6.13
jsvectormap : ^1.5.1
Dépendances JavaScript pour le développement :

@tailwindcss/forms : ^0.5.2
alpinejs : ^3.4.2
autoprefixer : ^10.4.2
axios : ^1.7.4
concurrently : ^9.0.1
laravel-vite-plugin : ^1.0
postcss : ^8.4.31
vite : ^6.0
@babel/core : ^7.16.12
@babel/preset-env : ^7.16.11
babel-plugin-prismjs : ^2.1.0
css-loader : ^6.5.1
file-loader : ^6.2.0
glob : ^7.2.0
html-loader : ^3.1.0
html-webpack-plugin : ^5.5.0
