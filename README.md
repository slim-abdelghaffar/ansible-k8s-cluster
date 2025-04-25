# Ansible-Kubernetes Cluster Setup
🚀 Kubernetes Cluster Setup with Ansible 
This project automates the deployment of a Kubernetes cluster using Ansible, with Docker as the container runtime. It streamlines the setup of Kubernetes across multiple nodes (master & worker), configures containerd, Flannel networking, and installs Helm for Kubernetes package management.

🌟 Key Features:
🔧 One-command setup for master & worker nodes

⚡ Automated node initialization and joining to the cluster

🐳 Docker-based container runtime configuration

🌐 Network setup with Flannel

📦 Helm installation for managing Kubernetes packages

📝 Instructions:
Update the IP addresses of the nodes in the k8s-cluster-init.yml file and in the /etc/hosts configuration.

Run the main_playbook.yml playbook to deploy the cluster across your nodes.

📋 Requirements:
Ubuntu 22.04+ nodes

Ansible 2.10+

Docker installed on all nodes 🐋

SSH access between all nodes 🔑
