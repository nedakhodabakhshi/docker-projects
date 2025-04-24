# vProfile Project (Dockerized)

This project is a Docker-based deployment of the **vProfile** application, a multi-tier web application designed for DevOps training and practice.

## ������ Technologies Used
- Docker & Docker Compose
- Nginx
- Tomcat (Java App)
- MySQL
- Memcached
- RabbitMQ / ActiveMQ

## ������ Folder Structure
Docker-files/ ├── app/ # Java-based application (Tomcat) ├── db/ # MySQL database setup ├── web/ # Nginx reverse proxy config docker-compose.yml

## ������ How to Run

Clone the repository and run:
```bash
docker-compose up --build

http://localhost/login
