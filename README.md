
#Docker container with Laravel + Vue

 - Docker
 - Laravel
 - Vue
 - composer
 - npm
 - PhpMyAdmin
 - nginx
 - php-fpm 7.4
 - mysql
 
 
Conspect

docker-compose up

docker-compose build


git init

git add . && git commit -m "initial commit"

git remote add origin git@github.com:niko898/docker_laravel_vue.git

git push -u original master


composer install

php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"

php -r "if (hash_file('sha384', 'composer-setup.php') === '55ce33d7678c5a611085589f1f3ddf8b3c52d662cd01d4ba75c0ee0459970c2200a51f492d557530c71c15d8dba01eae') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"

php composer-setup.

php -r "unlink('composer-setup.php');"


npm install

curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.3/install.sh | bash

bash

nvm ls-remote

nvm install v18.7.0