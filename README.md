# activity-3.9

helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm upgrade --install tk-prom prometheus-community/prometheus --version 27.5.1 --values prometheus-values.yaml --create-namespace --namespace tk-prom
