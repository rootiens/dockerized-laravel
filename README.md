```
docker-compose build && docker-compose up -d
docker-compose run --rm composer create-project --prefer-dist laravel/laravel .
```

* nginx - `:80`
* mysql - `:3306`
* phpmyadmin - `:8024`
* php - `:9000`
* redis - `:6379`
* mailhog - `:8025`

Three additional containers are included that handle Composer, NPM, and Artisan. Use the following command examples root.

* `docker-compose run --rm composer update`
* `docker-compose run --rm npm run dev`
* `docker-compose run --rm artisan migrate` or `docker-compose run --rm artisan migrate:fresh --seed`

PhpMyAdmin

`http://localhost:8024/`
