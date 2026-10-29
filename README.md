# Sergii Bezrukov

**AI Infrastructure / Platform Engineer** · AWS · Kubernetes · LLM systems · Ireland (GMT)

[![Open to work](https://img.shields.io/badge/Open_to_work-AI_Infrastructure_%2F_Platform_Engineer-2ea44f?style=for-the-badge)](#open-to-work)

I build and run the infrastructure and the LLM layer of production products: multi-account AWS estates in Terraform/Terragrunt, Kubernetes platforms with GitOps, observability that pages on signal rather than noise, and Claude-based assistants with RAG and tool calling, tested with evaluation harnesses before they ship. Over the last 1.5 years: ~4,800 commits across 40+ repositories, most of them infrastructure and AI repos I own end to end.

## Open to work

Looking for **AI Infrastructure, Platform or DevOps/SRE roles** where infrastructure and LLM systems meet. Remote, or on-site/hybrid in Ireland.

**Get in touch:** [LinkedIn](https://linkedin.com/in/sergiibezrukov) · [sergiibezrukov@proton.me](mailto:sergiibezrukov@proton.me)

## What I've built

- **Monolith → EKS migration** for a US SaaS: Terragrunt modules for the cluster, platform and policy layers, Pod Identity, network policies, quotas and PDBs; web tier, queue workers, scheduler, websockets and MySQL moved into the cluster with rehearsed rollbacks; ArgoCD GitOps and 30+ ADRs.
- **AWS estates owned end to end** for a US SaaS and a US fintech: multi-account Terragrunt, 5-tier VPC, KMS per data domain with envelope encryption for banking data, Cognito MFA, GuardDuty, CloudTrail and VPC Flow Logs.
- **SOC2 Type II readiness** with Vanta: Multi-AZ RDS with forced SSL, S3 replication and HTTPS-only policies, 365-day log retention, SCP region restrictions, auditor IAM role.
- **Production LLM assistant** (Python/FastAPI + AWS Bedrock/Claude): natural-language analytics over production MySQL through an agentic tool-calling loop with the platform's own permission scoping; RAG on Qdrant with hybrid search, RRF and reranking with degraded-mode fallback.
- **Evals for LLM systems**: an AI feature ships only when it passes tests. Golden test sets, server-side test runs, LLM-as-judge (Opus) with judge-agreement checks, and a methodology review pipeline with owner approval and versioned publishing.
- **Observability and on-call**: Grafana / Loki / Alloy / Prometheus; alerting rewritten from noise to signal (stable error classes, distribution-based thresholds, dead-man's switches, log-silence and queue-age alerts) with a runbook first action for every critical rule; an on-call dashboard that launches LLM-assisted investigations under a read-only IAM role.
- **CI/CD and load testing**: GitLab CI and GitHub Actions with OIDC (no stored keys), kaniko builds, automated GitOps image bumps, zero-SSH deploys via SSM; k6 suites covering 134 API endpoints with per-endpoint thresholds.

## Own projects

- **agentic-ops**: a Claude Code harness for infrastructure investigations (plan → evidence → report → independent critic verification) with tools for Grafana, CloudWatch Logs, SSM and DB dumps.
- **pdf-to-figma**: a Python + TypeScript Figma plugin that rebuilds a PDF as a component-based Figma file with a measured structural/perceptual diff.

## Tech stack

**Cloud & IaC**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Terragrunt](https://img.shields.io/badge/Terragrunt-1E2A3A?style=flat-square&logo=terraform&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F8B?style=flat-square&logo=amazonwebservices&logoColor=white)

**Kubernetes & delivery**

![Kubernetes](https://img.shields.io/badge/Kubernetes_(EKS)-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)

**AI / LLM**

![Amazon Bedrock](https://img.shields.io/badge/Amazon_Bedrock-01A88D?style=flat-square&logo=amazonwebservices&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logoColor=white)

**Observability**

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F46800?style=flat-square&logo=grafana&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazoncloudwatch&logoColor=white)

**Languages & data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

## Contact

- LinkedIn: [linkedin.com/in/sergiibezrukov](https://linkedin.com/in/sergiibezrukov)
- Email: [sergiibezrukov@proton.me](mailto:sergiibezrukov@proton.me)
- GitHub: [@serge-ai-infra](https://github.com/serge-ai-infra)

Languages: English, Ukrainian, Russian
