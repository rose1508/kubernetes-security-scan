# Kubernetes Security Scan

This project performs a Kubernetes security scan on a local Minikube cluster using **Kubescape** with the **NSA Hardening Framework**.

##  Tools Used
- Minikube (local Kubernetes cluster)
- Kubescape (security scanner)

## What it does
- Scans the Kubernetes cluster for security misconfigurations
- Uses the "NSA" framework for auditing
- Outputs the results in JSON format

## 📄 Output
The results are saved in this file:
results.json

##  How to Reproduce
1. Install Minikube and start a cluster.
2. Download `kubescape` binary.
3. Run the following scan:
4. kubescape scan framework nsa --format json --output results.json

##  Author
[rose1508](https://github.com/rose1508)
