# Prometheus & Grafana docker-compose monitoring stack

After starting your monitoring stach with docker-compose, You can now access the Grafana dashboard at `http://<Host IP Address>:3000` *Username: `admin`, Password: `changeme`*.

Here's a list of all the services that are created:

| Service | Port | Description | Notes |
| --- |:---:| --- | --- |
| Prometheus | :9090 | Data Aggregator | Username: `admin`, Password: `admin` |
| Alert Manager | :9093 | Adds Alerting for Prometheus Checks | Username: `admin`, Password: `admin` |
| Grafana | :3000 | UI To Show Prometheus Data | Username: `admin`, Password: `changeme`|