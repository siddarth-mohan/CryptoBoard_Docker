# Crypto Dashboard


 This repo contains the different microservices making up the backend for the crypto dashboard and the frontend application

### Prerequisites
Make sure you hvae these 3 installed in your machine.
- maven
  - https://maven.apache.org/download.cgi
  - https://www.baeldung.com/install-maven-on-windows-linux-mac
- npm
  - https://docs.npmjs.com/downloading-and-installing-node-js-and-npm
- docker
  - https://www.docker.com/products/docker-desktop/

### Instructions to run

```
cd crypto-dashboard
```

From the crypto-dashboard directory, run the below commands
```
docker compose up --build --detach
```

### To stop and clean up environment
After all execution this command can be run to remove all containers.
```
docker compose down --rmi all
```

### Endpoints

Crypto Dashboard: http://localhost:8080
