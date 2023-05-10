# space

### Build
`docker-compose build --no-cache`

### Start all container  
`docker-compose start`
  
### Stop and remove all container  
`docker stop $(docker ps -a -q) && docker rm $(docker ps -a -q)`
or
`docker system prune -af`
  
### Delete all PM2
`pm2 delete all`
