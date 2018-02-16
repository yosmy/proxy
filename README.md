# Deploy

git clone https://github.com/yosmy/proxy proxy

cd proxy

docker network create proxy

docker-compose -f docker/all.yml -p proxy stop && docker-compose -f docker/all.yml -p proxy up -d

cd ..