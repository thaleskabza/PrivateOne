
# Build and Compile 
```bash
docker compose -f docker-compose.yml up -d --build
```

# Run Tests 
```bash
 docker compose run --rm test-runner mvn test
```

# Pull down
```bash
 docker compose down -v
```
