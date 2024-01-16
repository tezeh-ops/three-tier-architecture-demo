# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name robot-cluster --region us-west-1
```

## Delete the cluster

```
eksctl delete cluster --name robot-cluster --region us-west-1
```



