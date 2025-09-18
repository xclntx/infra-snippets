# Infra Snippets ⚙️

Microservice demo with frontend + backend, TLS and autoscaling.  

## Includes
- **Backend** (port 8080) with ConfigMap injection  
- **Frontend** (port 80) consuming backend  
- **Ingress** with TLS (cert-manager ClusterIssuer)  
- **Horizontal Pod Autoscaler** for backend  

## Usage
```bash
kubectl apply -f config/
kubectl apply -f certs/
kubectl apply -f k8s/
