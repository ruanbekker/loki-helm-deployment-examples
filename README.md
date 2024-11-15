# loki-helm-deployment-examples
Grafana Loki Deployment Examples on Kubernetes

## About

This includes deployment examples for the following Loki Deployment methods:

1. [Monolithic / Single Binary](https://grafana.com/docs/loki/latest/get-started/deployment-modes/#monolithic-mode)
2. [Simple Scalable](https://grafana.com/docs/loki/latest/get-started/deployment-modes/#simple-scalable)
3. [Distributed / Microservices](https://grafana.com/docs/loki/latest/get-started/deployment-modes/#microservices-mode)

## Supporting Resources

If you need a Kubernetes cluster, you can deploy a 3 node cluster with KinD using Terraform:

```bash
terraform init
terraform apply
```

Then set:

```bash
export KUBECONFIG=/tmp/kube.config
```

