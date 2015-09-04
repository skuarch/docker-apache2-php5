Dockerfile for apache2 and php5

this is the best way to run this container

docker run --name apache2-php5 -i -t -p 80:80 -c 4 --net=host -m 4096M -v /var/www/html:/var/www/html skuarch/apache2-php5

"-c 4" is optional and "-m 4096M" if you prefer change the volumen to a better place
