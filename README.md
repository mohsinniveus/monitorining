# monitorining

kubectl get pods --namespace=monitoring
kubectl port-forward prometheus-deployment-74dc6c7466-zhmw5 8080:9090 -n monitoring


Alert Manager
http://localhost:31000/#/alerts

Grafaan
http://localhost:32000/?orgId=1