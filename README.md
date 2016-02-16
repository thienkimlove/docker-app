# docker-app

Docker include with laravel + mysql

Git Clone 

composer install && cp .env.example  .env && cp docker-compose.yml.example docker-compose.yml

chmod -R 777 storage && chmod -R 777 bootstrap && docker-compose up -d 

docker exec -it containerID  

php artisan migrate


