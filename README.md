# Comics-Blog (LaravelCRUD Server-Side CA2 Project)

A fully functioning blog using the Laravel framework. The blog focuses on comic books.

# Requirements
• PHP 7.3 or higher
• Node 12.13.0 or higher

# Setting up project
- Please follow the steps below
```sh
git clone git@github.com:codewithdary/laravel-8-complete-blog.git
cd laravel-8-complete-blog
cp .env.example .env
composer install
php artisan key:generate
php artisan cache:clear && php artisan config:clear
php artisan serve
```

# Before starting
1. **Create the Database:**
```sh
mysql -u root
create database laravelblog;
exit;
```

2. **Set up database credentials in your .env file**
```ini
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravelblog
DB_USERNAME={USERNAME}
DB_PASSWORD={PASSWORD}
```

3. **Migrate the tables**

```sh
php artisan migrate
```
