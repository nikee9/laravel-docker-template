Installing Laravel using composer

CD to the directory
docker-compose run --rm --user 1000:1000 composer composer create-project laravel/laravel .

Run laravel and composer commands via 
docker-compose exec php php artisan command
docker-compose exec php composer