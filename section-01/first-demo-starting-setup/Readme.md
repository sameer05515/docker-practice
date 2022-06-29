#

docker build .
 docker run -p 3000:3000 <container-id>  
 docker run -p <local-port>:<internal-docker-container-port> <container-id>
 -p == publish
 
 5e252e8feb247ead85f1971ab77a9fa612ac0fefad191c052811535cf7009da4

 docker ps
 docker stop

 docker run -p 8000:3000 -d --name pythonapp --rm python-demo:latest

 docker build -t node-demo:latest .

docker image prune -a

docker container prune
