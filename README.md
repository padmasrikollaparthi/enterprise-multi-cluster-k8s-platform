# Enterprise Multi-Cluster Kubernetes Platform

This project implements an enterprise-grade Kubernetes Internal Developer Platform (IDP)
supporting multi-cluster, multi-region deployments using GitOps, Istio service mesh,
centralized observability, and policy enforcement.

## Features
- Multi-cluster Kubernetes (3 clusters, 2 regions)
- GitOps using ArgoCD (App of Apps)
- Istio multi-cluster service mesh with mTLS
- Centralized monitoring, logging, tracing
- OPA Gatekeeper policy enforcement
- Backstage Internal Developer Portal

## Getting Started
```bash
./scripts/setup.sh
./scripts/deploy.sh
./scripts/test.sh
