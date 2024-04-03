
install mysql di docker sebagai 1 container sendiri 

docker pull mysql
docker run --name mysql -d -p 3307:3306 -e MYSQL_ROOT_PASSWORD=112  -v mysql:/var/lib/mysql mysql:8


penjelasan
--name mysql (bisa disesuaikan nama container )
mysql:/var/lib/mysql storage dari docker bisa disesuaikan directory maupun penamaan di dalam lib