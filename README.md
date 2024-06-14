# Kubernetes Installation
Run the following commands (master and worker) -
``` sudo apt update
``` sudo apt upgrade

### Now run this command -
``` nano /etc/hostname
### change the hostname to master in master vm and worker in worker vm

### Run this command , and update the /etc/hosts with master and worker ips
``` nano /etc/hosts

### Reboot the system
``` reboot

### Now, create a script file in master node and run the master.sh script in that node
### Create a script in worker node(s) and run the worker.sh script in the node

### if error of unable to locate package kubeadm ,kubelet , kubectl , kubernetes-cni is there, then run the xenial_error.sh script





