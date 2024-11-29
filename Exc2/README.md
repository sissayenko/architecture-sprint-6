# architecture-sprint-6

kubectl get --raw /apis/metrics.k8s.io/v1beta1/namespaces/default/pods/sprint6-6879d699d-mqd9r

kubectl get hpa

kubectl top pods -A

kubectl top node

helm install sprint6 .\sprint6\ 

helm upgrade sprint6 .\sprint6\

helm uninstall sprint6

minikube service --all

wget https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml

(        - --kubelet-insecure-tls)

kubectl apply -f .\components.yaml
