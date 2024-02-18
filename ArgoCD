Before we need to install kubernetse after that follow this steps:
-----------------------------------------------------------------

Installing with K8s and applying 
---------------------------------
# kubectl create namespace argocd
# kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

port fowarding the services
---------------------------
# kubectl port-forward svc/argocd-server -n argocd 1111:443 --address 0.0.0.0

userid:admin
pass: use bellow command
get a password for argocd with this command:
--------------------------------------------
# kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
