# DataEngineeringBootCampp
docker run -it \
  -e POSTGRES_USER="root" \
  -e POSTGRES_PASSWORD="root" \
  -e POSTGRES_DB="ny_taxi" \
  -v dtc_postgres_volume_local/var/lib/postgresql/data \
  -p 5432:5432 \
  postgres:13








  docker run -it \
  -e PGADMIN_DEFAULT_EMAIL="admin@admin.com" \
  -e POSTGRES_DEFAULT_PASSWORD="root" \
  -p 8088:80 \
  --network=pg-network \
  --name pgadmin \
  dpage/pgadmin4
  