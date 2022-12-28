# About this application
CRUD app with laravel and vuejs

In this Laravel Vue.js Crud app, we will implement Laravel Vue.js crud (create, read, update, and delete) spa (Single Page Application) with Vue.js, Vue Router, and Laravel Framework.

In today's, the most popular JS frameworks are Angular JS and Vue JS. Angular JS and Vue JS are very user-friendly JS frameworks and most popular. It provides to manage the whole project or application without refresh page and powerful jquery validation.

Vue comes pre-packaged with Laravel (along with Laravel Mix, an excellent build tool based on webpack) and allows developers to start building complex single-page applications without worrying about transpilers, code packaging, source maps, or any other 'dirty' aspects of modern frontend development.


- [Laravel Vue JS CRUD Application](https://techvblogs.com/blog/build-crud-app-with-laravel-and-vuejs).

# Laravel Vue JS CRUD Application (SPA) :

  1. Install Laravel Project
  2. Configure Database Details
  3. Install NPM Dependencies
  4. Create Migration, Model, and Controller
  5. Define Routes In web.php
  6. Create a Vue App
  7. Create Component For Vue App
  8. Define Route For Crud App in Vue Router
  9. Include Vue.js Dependencies to app.js
  10. Update webpack.mix.js
  11. Run Development Server

# Server Requirements

PHP 7.4

Laravel 8.x

MySQL

# 1. Install Laravel Project

First, open Terminal and run the following command to create a fresh laravel project:

    composer create-project --prefer-dist laravel/laravel crud-spa

or, if you have installed the Laravel Installer as a global composer dependency:

    laravel new crud-spa

# 2. Configure Database Details:

After, Installation Go to the project root directory, open .env file, and set database detail as follow:

    DB_CONNECTION=mysql 
    DB_HOST=127.0.0.1 
    DB_PORT=3306 
    DB_DATABASE=<DATABASE NAME>
    DB_USERNAME=<DATABASE USERNAME>
    DB_PASSWORD=<DATABASE PASSWORD>

# 3. Install NPM Dependencies

Run the following command to install frontend dependencies:

    npm install

Next, install vue, vue-router and vue-axios. Vue-axios will be used for calling Laravel backend API. Run the following command on the terminal:

    npm install vue vue-router vue-axios --save


See https://codeplaners.com/how-to-create-laravel-8-vue-js-crud-example/


# Run Laravel Vue CRUD App
	
    npm run watch

    
    php artisan serve

## Open the URL in the browser:
	
    http://127.0.0.1:8000



# Repository on the command line

    echo "# Laravel-8-VueJs-crud" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/tounsils/Laravel-8-VueJs-crud.git
    git push -u origin main   