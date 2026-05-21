---
icon: fontawesome/solid/dharmachakra
---

# CKA Certification

> **No fluff. Just the details engineers care about.**

A complete, hands-on guide to mastering Docker and Kubernetes — from first principles to CKA exam readiness. Every day builds on the last with real YAML manifests, practical demos, and the *why* behind every concept.

<div class="grid cards" markdown>

-   :fontawesome-brands-youtube:{ .lg } **Video Course**

    ---

    Follow along with the full YouTube playlist — each day pairs directly with a video lesson.

    [:octicons-arrow-right-24: Watch on YouTube](https://www.youtube.com/playlist?list=PLmPit9IIdzwRjqD-l_sZBDdPlcSfKqpAt)

-   :fontawesome-brands-github:{ .lg } **Source Code**

    ---

    All Dockerfiles, YAML manifests, and code examples are in the repository, organized by day.

    [:octicons-arrow-right-24: Browse on GitHub](https://github.com/CloudWithVarJosh/CKA-Certification-Course-2025)

-   :fontawesome-solid-graduation-cap:{ .lg } **CKA Exam**

    ---

    Content is aligned with the official CNCF CKA curriculum — every major exam topic is covered.

    [:octicons-arrow-right-24: CKA Exam Details](https://www.cncf.io/certification/cka/)

-   :fontawesome-brands-linkedin:{ .lg } **Stay Connected**

    ---

    Follow Varun Joshi on LinkedIn for updates, tips, and community discussions.

    [:octicons-arrow-right-24: Connect on LinkedIn](https://www.linkedin.com/in/varun-joshi-2b516752/)

</div>

---

## What You'll Learn

The course is structured as a **59-day curriculum** covering the full CKA exam scope:

| Phase | Days | Topics |
|---|---|---|
| **Docker Foundations** | 1–5 | Containers, Dockerfiles, multi-stage builds |
| **Kubernetes Basics** | 6–14 | Architecture, pods, deployments, services, namespaces |
| **Scheduling & Resources** | 15–20 | Affinity, taints, limits, HPA, VPA |
| **Advanced Pods** | 21–25 | Init containers, sidecars, probes, volumes intro |
| **Storage** | 26–30 | PV/PVC, StorageClass, ConfigMaps, Secrets, Jobs |
| **Security & TLS** | 31–40 | mTLS, RBAC, admission controllers, CRDs, operators |
| **Advanced Topics** | 41–48 | Pod security, Kustomize, Helm, StatefulSets, network policies |
| **Ingress & Networking** | 49–53 | Ingress, Gateway API, path routing, TLS termination |
| **Cluster Administration** | 54–59 | kubeadm, upgrades, monitoring, troubleshooting, JSONPath |

---

## Getting Started

### Prerequisites

- Linux or macOS (Windows with WSL2 works too)
- Docker installed and running
- `kubectl` installed
- A local cluster via [Kind](https://kind.sigs.k8s.io/) or [Minikube](https://minikube.sigs.k8s.io/)

### Quick Setup

```bash
# Install Kind (recommended)
curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.20.0/kind-linux-amd64
chmod +x ./kind && sudo mv ./kind /usr/local/bin/kind

# Create a cluster
kind create cluster --name cka

# Verify
kubectl cluster-info
kubectl get nodes
```

---

## How to Use This Guide

1. **Navigate by day** — use the left sidebar to jump to any topic
2. **Read the README** — each day has context, diagrams, and key concepts
3. **Run the examples** — clone the repo and apply the YAMLs yourself
4. **Review and repeat** — concepts build on each other; revisit previous days

!!! tip "Exam Tip"
    The CKA is an open-book, hands-on exam. Focus on speed with `kubectl`, understanding YAML structure, and debugging — not memorization.

---

## Contribute

Found a typo or have a suggestion? Open a PR or issue on [GitHub](https://github.com/CloudWithVarJosh/CKA-Certification-Course-2025). All contributions are welcome.
