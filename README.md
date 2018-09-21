# helm-charts

Helm charts for deploying my applications in Kubernetes

## Usage

```
helm repo add weeco https://raw.githubusercontent.com/weeco/helm-charts/master
helm repo update
helm upgrade --install serviceName --namespace default --values values.yaml weeco/nodejs
```
