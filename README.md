# Kubernetes-repo

kubectl create secret docker-registry aws-ecr --docker-server=008089408493.dkr.ecr.us-east-1.amazonaws.com --docker-username=AWS --docker-password=$(aws ecr get-login-password)