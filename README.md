# About Jetstream App

This Project is designed with Laravel using Jetstream Package that provides the implementation of Login System, Registration, Email verification, two step verificatiton and team management.


## Create App

```
composer create-project laravel/laravel jetstreamApp

cd jetstreamApp

composer require laravel/jetstream

```

## Install with Livewire

> Livewire is a full-stack framework for Laravel that enables you to create rich, dynamic user interfaces using server-side rendering. It allows us to build UI components in PHP and Laravel Blade templates, providing a familiar development experience. This integration allows you to create dynamic forms, handle form submissions, perform AJAX requests, and update the UI without writing JavaScript code manually.
> Using Livewire, we can create interactive UI components that respond to user actions, validate form inputs, perform server-side validation, and display dynamic data. It also provides real-time validation and error handling capabilities

```
php artisan jetstream:install livewire

php artisan jetstream:install livewire --teams

> for dark mode

php artisan jetstream:install livewire --dark

```

## After installation we should install npm dependencies and migrate our database.

```
npm install && npm run build

php artisan migrate

```

