# Observability in the CLOUD
### We can imagine this scenario where we need to monitor each customers with one Stack.
![alt text](https://ravindrajob.blob.core.windows.net/assets/customerScénario6.png)

## The four Golden Signals :
Latency
Traffic
Errors
Saturation

## why collecting this signals ?

Alerting: notify when something is wrong
Troubleshooting: help us to isolate and fix the problem
Tuning/Capacity Planning: to assist us in improving our setup over time

## Why monitoring ?
## Wich tools ?
In our case we will use those components on a docker compute:
- Thanos for the retention (and a Azure Storage account)
- Prometheus to orchestrate the supervision
- AlertManager for alerting
- Grafana for display metrics and logs
- Loki for parse our LOGs
- Telegraf for self monitoring
- Nginx to securise and expose our stack

### Our principal monitoring stack is made with this :
![alt text](https://ravindrajob.blob.core.windows.net/assets/Monitoring.png)


