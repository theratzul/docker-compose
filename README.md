Start the docker compose in path: docker-compose up -d  
Take the admin passwords from logs: docker logs -f jenkins  
Open dns https://localhost:8086  (vi /etc/hosts/ and add jenkins in localhost and ip)  
Setup password theratzul/b..n  
Restart the service in path: docker-compose service restart  