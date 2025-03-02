### Docker setup for local development

Create containers for all the services
```bash
docker compose -p "development" up -d
```

Once all the containers are created, stop/start the containers manually from the docker desktop client.

### Ubuntu service (SSH)
This continer is for testing ubuntu and ssh connectivity. The username and password is `ubuntu`.
