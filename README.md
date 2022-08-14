# pihole_docker
In this repository I am running a docker-compose file  without ports confict

1 update and upgrade:
sudo apt-get update
sudo apt-get upgrade

2 install docker and docker-compose
sudo apt-get istall docker
sudo apt-get install docker-compose

3 exceute the docker container
sudo docker-compose up -d

4 check the container/image
sudo docker ps

5 chnage the pi-hole password
sudo pihole -a -p

6 accessing to pi-hole admin:
IP adress (your raspberry ip)/admin
(ex:192.168.1.108/admin)
