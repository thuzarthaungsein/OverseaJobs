
## JWT-Laravel7-VueJS
Testing Project Frame for Oversea Jobs

### INSTALLATION
```bash
git clone https://github.com/Thuzar-TS/OverseaJobs.git
```
Go to project folder.
```bash
git checkout your-branch-name (optional)
composer install
npm install
php artisan key:generate
php artisan jwt:secret
```

### For Admin
- user table role default => 1 

### For User
- change role => 2 

### Database Setup
- In Browser, go to localhost/phpmyadmin
- Create database ```oversea_jobs``` with collation ```utf8mb4_unicode_ci```
- Clone ```.env.example``` file as ```.env```
- Change your database connection in .env file.
- run ```php artisan migrate```

### Run Project
- run ```php artisan serve```
- run ```npm run watch```