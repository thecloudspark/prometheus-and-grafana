# Prometheus and Grafana

[![GitHub](https://img.shields.io/badge/GitHub-romarcablao-lightgrey)](https://github.com/romarcablao)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-romarcablao-blue)](https://linkedin.com/in/romarcablao)

Setup Prometheus and Grafana using Docker and Compose.

```bash
docker-compose up -d
```

Once all containers are running, visit http://localhost  
To login, use initial creds: 
```bash
username: admin
password: admin
```

To add prometheus as datasource, use the following:
```bash
# HTTP
url: http://prometheus:9090

# Auth
# Enable Basic Auth and use the following Details
username: admin
password: admin
```