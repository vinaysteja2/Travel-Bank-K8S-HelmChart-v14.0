
# 🚀 Travel-Bank_K8S-HelmChart_v14.0

> 🌐 Advanced Kubernetes Helm Chart Deployment for the Travel Bank Microservices Suite with enhanced monitoring, centralized logging, and reusable chart structure.

---

## 📁 Project Structure

```
sectionNew16/
├── helm/
│   ├── environments/
│   ├── grafana/
│   ├── grafana-loki/
│   ├── grafana-tempo/
│   ├── kafka/
│   ├── keycloak/
│   ├── kube-prometheus/
│   ├── travelbank-common/
│   ├── travelbank-services/
```

---

## ⚙️ Helm Chart Commands

| Command | Description |
|--------|-------------|
| `helm ls` | List all deployed Helm charts |
| `helm search hub wordpress` | Search charts on Helm Hub |
| `helm repo add bitnami https://charts.bitnami.com/bitnami` | Add Bitnami Helm repo |
| `helm install happy-panda bitnami/wordpress` | Install WordPress chart |
| `helm uninstall happy-panda` | Uninstall WordPress chart |
| `helm create travelbank-common` | Create reusable chart |
| `helm dependencies build` | Compile chart dependencies |
| `helm template .` | Render chart to Kubernetes YAML |
| `helm install travelbank prod-env` | Deploy the Helm chart |
| `helm upgrade travelbank prod-env` | Upgrade deployment with changes |
| `helm history travelbank` | View revision history |
| `helm rollback travelbank 1` | Roll back to revision 1 |
| `helm uninstall travelbank` | Uninstall deployment |

---

## 📊 Monitoring Stack (Grafana + Loki + Tempo)

- **Grafana**: Real-time metrics dashboards
- **Loki**: Log aggregation
- **Tempo**: Distributed tracing

---

## 🔐 Security Stack

- **Keycloak** for centralized identity & access control
- Helm-based deployment for simplified upgrades

---

## 🌐 Observability Stack

- **Kube Prometheus**: Cluster monitoring and alerting
- Integrated with **Grafana Dashboards**

---

## 📦 Microservices Deployment Structure

- travelbank-common → shared templates
- travelbank-services → all business services (accounts, loans, cards)
- environments → different values files (dev, prod, staging)

---

## 🔁 Previous Versions

### 📦 Travel-Bank_K8S-Deployment_v_13.0

> Full Kubernetes-based microservice orchestration with dashboards and RBAC

### 📦 Travel-Bank_Apache-Kafka_v_12.0

> Apache Kafka-based Event-Driven Architecture

---

## 🧾 Version History

| Version | Features |
|--------|----------|
| v1.0 | Core Microservices |
| v2.0 | Docker Integration |
| v3.0 | Config Client |
| v4.0 | Config Server |
| v5.0 | MySQL Integration |
| v6.0 | Eureka Service Discovery |
| v7.0 | API Gateway |
| v8.0 | Resilience4j Circuit Breaker |
| v9.0 | Grafana + Prometheus Observability |
| v10.0 | OAuth2 + Keycloak |
| v11.0 | RabbitMQ Asynchronous |
| v12.0 | Kafka Asynchronous |
| v13.0 | K8S Deployment & Dashboard |
| v14.0 | Helm-based K8S Microservice Deployment |

---

## 👨‍💻 Author

Built with ❤️ by **Vinay Steja**  
🔗 [GitHub](https://github.com/vinaysteja2)

---

## 🪪 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
