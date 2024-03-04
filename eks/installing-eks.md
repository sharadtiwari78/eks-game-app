# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name this-cluster --region us-east-1 --fargate
```

## Delete the cluster

```
eksctl delete cluster --name this-cluster --region us-east-1
```



