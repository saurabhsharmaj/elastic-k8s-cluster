official links : https://www.elastic.co/guide/en/cloud-on-k8s/current/k8s-deploy-elasticsearch.html
password fetch for elastic: PASSWORD=$(kubectl get secret quickstart-es-elastic-user -o go-template='{{.data.elastic | base64decode}}')
