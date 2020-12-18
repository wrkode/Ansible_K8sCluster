# Kubernetes Cluster Build With Ansible

Builds a K8s cluster with Single Control Plane:
- 1 Master and 3 nodes

+ Calico Pod Network with CIDR 10.15.0.0/16
+ Calico YAML file needs to be updated to match the CIDR

Assumptions:
- K8s Cluster OS = Centos 7/8
- Ansible user has passwordless escalation rights


