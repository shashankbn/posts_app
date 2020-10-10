## Steps to run

### Pre-requisites
Minikube and Kubectl

1. Update /etc/hosts => 127.0.0.1 posts.com
2. minikube start --vm=true
3. kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.40.2/deploy/static/provider/cloud/deploy.yaml
4. Skaffold dev
5. Minikube tunnel
6. Open posts.com in browser !!

Ref : microservices-with-node-js-and-react by Stephen Grider