# SIAKAD APPLICATION - LARAVEL 10

## Run Locally

Clone the project

```bash
  git clone https://github.com/abdulaziz-m5u/siakad-laravel.git nama_project
```

```bash
  cd nama_project
```

-   Copy .env.example file to .env and edit database credentials there

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan artisan migrate:fresh --seed
```

```bash
    php artisan storage:link
```

