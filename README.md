# **Paul Standley**

![profile](profile.png)

## fuzzy-octo-engine

### BASH

```BASH

composer create-project --prefer-dist laravel/laravel fuzzy-octo-engine

composer require laravel/ui --dev

php artisan ui react

// Generate login / registration scaffolding...
php artisan ui react --auth

npm install && npm run dev

php artisan serve

php artisan make:controller PhotoController --resource

php artisan make:migration PhotoController

```

migration problem AppServiceProvider

php

```PHP

<?php

namespace App\Providers;

use Illuminate\Support\ServiceProvider;
use Illuminate\Support\Facades\Schema;

class AppServiceProvider extends ServiceProvider
{
    /**
     * Register any application services.
     *
     * @return void
     */
    public function register()
    {
        //
    }

    /**
     * Bootstrap any application services.
     *
     * @return void
     */
    public function boot()
    {
        Schema::defaultStringLength(191);
    }
}

```

Bash

```BASH

php artisan migrate:rollback
php artisan make:model Photo -m

```
