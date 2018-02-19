# sipac_balancing
Configuracion para docker compose con Nginx como proxy-reverse y como balanceador de carga para Apache server.

--
git clone https://github.com/rmolinet/sipac_balancing.git
cd sipac_balancing
docker-compose up --scale apache_sipac=4
