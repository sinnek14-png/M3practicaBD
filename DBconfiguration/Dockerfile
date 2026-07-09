# Imagen oficial de PostgreSQL
FROM postgres:latest

# copia el script SQL al directorio de inicializacion de PostgreSQL
COPY Init.sql /docker-entrypoint-initdb.d/
COPY save_data.sql /docker-entrypoint-initdb.d/


