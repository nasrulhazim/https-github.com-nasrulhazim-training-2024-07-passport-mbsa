# OAuth2.0 with Laravel Passport

Create new Laravel project:

```bash
laravel new jetpass-app --stack=livewire --jet --dark --api --pest
```

Install Passport and OAuth2.0 Support for Laravel Jetstream:

```bash
composer require "headerx/laravel-jetstream-passport:^1.0"
```

Then install the package:

```bash
php artisan jetstream-passport:install
```

Create Clients:


```bash
php artisan passport:client

 Which user ID should the client be assigned to? (Optional):
 >

 What should we name the client?:
 > Chirper App

 Where should we redirect the request after authorization? [http://localhost/auth/callback]:
 > http://127.0.0.1:80001/oauth/callback
 ```
