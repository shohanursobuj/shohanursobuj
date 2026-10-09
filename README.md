### Hi, I'm Shohanur 👋

**Machine Learning Engineer · MLOps · LLMs** — Köln, Germany · he/him

I build and run ML systems in production. At [Anymate Me GmbH](https://anymateme.com) I own an agentic slide-to-video pipeline (PDF/PPTX → RAG agent → TTS → avatar lip-sync) on GCP: **p95 < 3 min per 10-slide deck, 99.4% uptime, error rate < 4%**, with LLM evaluation gates (groundedness, guardrails), canary deploys and automated rollback.

6+ years in ML — 13 AI products shipped at Anchorblock, real-time CDC pipelines (Kafka/Debezium) at Business Automation, and 12 peer-reviewed papers on the side (225+ citations, h-index 8).

[![Portfolio](https://img.shields.io/badge/Portfolio-shohanursobuj.dev-0d1117?style=flat-square&logo=googlechrome&logoColor=white)](https://shohanursobuj.dev)
[![Resume](https://img.shields.io/badge/Resume-PDF-0d1117?style=flat-square&logo=readthedocs&logoColor=white)](https://shohanursobuj.dev/resume)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shohanursobuj-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shohanursobuj/)
[![Scholar](https://img.shields.io/badge/Google_Scholar-225%2B_citations-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=tBc62IMAAAAJ&hl=en)
[![Email](https://img.shields.io/badge/Email-contact%40shohanursobuj.dev-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:contact@shohanursobuj.dev)

---

#### 🔧 Featured project

**[production-ml-platform](https://github.com/shohanursobuj/production-ml-platform)** — reference platform for running a model in production, end to end:
train → evaluation gate (vs. thresholds and current champion) → container → Kubernetes with Argo Rollouts canary gated by Prometheus SLOs → Grafana dashboards → in-process drift detection (PSI) → retraining that promotes models through reviewed PRs.
Terraform for GKE Autopilot in `europe-west3` with keyless GitHub OIDC; CI deploys every commit into a kind cluster and smoke-tests it.

`FastAPI` `Helm` `Argo Rollouts` `Prometheus` `Grafana` `Terraform` `GKE` `MLflow` `GitHub Actions`

#### 📄 Selected research

| Paper | Venue |
|---|---|
| [LLM-Mixer: Multiscale Mixing in LLMs for Time Series Forecasting](https://arxiv.org/abs/2410.11674) · [code](https://github.com/Kowsher/LLMMixer) | NeurIPS Workshop 2025 |
| [Parameter-Efficient Fine-Tuning of LLMs Using Semantic Knowledge Tuning](https://www.nature.com/articles/s41598-024-75599-4) | Scientific Reports (Nature) 2024 |
| [ML-Driven Fault Detection and Classification for Electric Vehicles](https://ieeexplore.ieee.org/document/10530324) | IEEE Access 2024 |
| [L-TUNING: Synchronized Label Tuning for Prompt and Prefix Tuning in LLMs](https://openreview.net/forum?id=zv3xpxqjjB) · [code](https://github.com/Kowsher/L-Tuning) | ICLR 2024 Tiny Papers |
| [Contrastive Learning for Universal Zero-Shot NLI](https://aclanthology.org/2023.mrl-1.18/) | EMNLP 2023 Workshop (MRL) |
| [Pre-trained CNNs for Rice Leaf Disease Classification](https://arxiv.org/abs/2405.00025) · [code](https://github.com/shohanursobuj/LeafExtractCNN) | IEEE iCACCESS 2024 |

[All publications →](https://shohanursobuj.dev/#research)

#### 🧰 Stack

- **ML / LLMs** — Python, PyTorch, Transformers, PEFT/LoRA, RAG, LangGraph, vector search (pgvector, Qdrant), TTS, computer vision
- **MLOps / Platform** — Docker, Kubernetes, Helm, Terraform, GCP, AWS, MLflow, Prometheus, Grafana/Loki, GitHub Actions, FastAPI
- **Data** — Kafka, Debezium, Airflow, PostgreSQL, Redis, Elasticsearch

---

Open to senior ML / MLOps engineering conversations in Germany, the EU and remote.
