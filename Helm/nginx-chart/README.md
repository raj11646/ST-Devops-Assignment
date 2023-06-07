helm-chart/
  ├── Chart.yaml
  ├── values.yaml
  ├── tls.crt
  ├── tls.key
  └── templates/
      ├── deployment.yaml
      ├── service.yaml
      ├── ingress.yaml
      └── tls-secret.yaml


To install helm chart please run below command from root dir(nginx-chart)

helm install nginx-chart .

