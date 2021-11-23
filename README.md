# k8s_hands_on :(In progress)

* Deploying MongoDB and Mongo Express:

   - kubectl apply -f mongo-secret.yaml
   - kubectl apply -f mongo.yaml
   - kubectl apply -f mongo-configmap.yaml 
   - kubectl apply -f mongo-express.yaml

* give a URL to external service in minikube:

   -  minikube service mongo-express-service
----------------------------------------------------------------
- Install a Stateful Application on K8s using Helm

- Deploy App from Private Docker Registry

- Prometheus Operator  with Helm: Setup Prometheus Monitoring on Kubernetes

- Deploy Microservices Application