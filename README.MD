# [Draft] Ansible role to install Microk8s

## What is MicroK8s?

MicroK8s is a powerful, lightweight, reliable production-ready Kubernetes distribution. It is an enterprise-grade Kubernetes distribution that has a small disk and memory footprint while offering carefully selected add-ons out-the-box, such as Istio, Knative, Grafana, Cilium and more. Whether you are running a production environment or interested in exploring K8s, MicroK8s serves your needs.

## Why MicroK8s?

MicroK8s is the smallest, fastest multi-node Kubernetes. Single-package fully conformant lightweight Kubernetes that works on Linux, Windows and Mac. Perfect for: Developer workstations, IoT, Edge, CI/CD.

Anyone who’s tried to work with Kubernetes knows the pain of having to deal with getting set up and running with the deployment. There are minimalist solutions in the market that reduce time-to-deployment and complexity but the lightweight solutions come at the expense of critical extensibility and missing add-ons.

## Prerequisites

To run MicroK8s, you will need a computer with a Linux distribution that supports Snaps such as Ubuntu and Ansible 2.8

## Run playbook

```sh
ansible-playbook -u root --key-file=~/.ssh/id_rsa -i inventory/hosts.ini -l cluster cluster.yaml
```
