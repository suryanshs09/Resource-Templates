# Common Docker Compose Setup

This directory contains a ready-to-use `docker-compose.yml` for running containers of microservice with PostgreSQL and Redis.

### Usage
```bash
docker compose up --build
```

### Includes
- A Node.js sample microservice
- Dedicated PostgreSQL container
- Dedicated Redis cache
- Isolated networks for clean separation

### Example `.env`
```
DB_USER=admin_user
DB_PASSWORD=password
DB_NAME=db
DB_PORT=5432

HOST_PORT=3001

CACHE_PORT=6379

JWT_SECRET=supersecret
```
