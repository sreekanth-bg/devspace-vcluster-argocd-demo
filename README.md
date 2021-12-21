# [KubeSphere - Kubernetes Platform For Cloud-Native App Management](https://youtu.be/1OOLeCVWTXE)

refer for aks and argocd setup - https://github.com/sreekanth-bg/terraform-aks-azure/

and https://gist.github.com/vfarcic/ed8ad113fff4322ef309198d5455687f

'''
export GITHUB_ORG=sreekanth-bg export GITHUB_TOKEN= export INGRESS_HOST= export DOCKERHUB_TOKEN= export DOCKERHUB_USERNAME=infovein69
'''

kubectl apply -f ingress.yaml -n argocd

k3d kubeconfig merge devops-toolkit export KUBECONFIG=/home/bgs/.k3d/kubeconfig-devops-toolkit.yaml

vcluster list vcluster --namespace a-team delete a-team '''
