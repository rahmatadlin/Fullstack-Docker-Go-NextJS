# Fullstack-Docker-Go-NextJS

touch .gitignore
\*node_modules
touch compose.yaml
docker compose up -d db
docker ps -a
docker exec -it db psql -U postgres
\l
\dt

backend
go mod init api
get github.com/gorilla/mux (parsing the JSON file)
go getgithub.com/lib/pq

RUN
docker compose build
docker compose up -d goapp
