# 👋 Hi, I'm Sadra Saremi

### 🧠 Senior AI/ML Engineer | LLM Infrastructure • RAG/Graph-RAG • Production MLOps

<p align="center">
  <a href="mailto:saremi.sadra@gmail.com">
    <img src="https://img.shields.io/badge/Email-saremi.sadra@gmail.com-blue?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://linkedin.com/in/sadra-saremi">
    <img src="https://img.shields.io/badge/LinkedIn-sadra--saremi-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://sadrasaremi1997.pythonanywhere.com">
    <img src="https://img.shields.io/badge/Portfolio-Visit%20Site-green?style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio">
  </a>
  <br>
  <img src="https://img.shields.io/badge/Location-Tehran,%20Iran-orange?style=for-the-badge&logo=map-marker-alt&logoColor=white" alt="Location">
  <img src="https://img.shields.io/badge/Open%20to-Remote%20%7C%20Relocation-brightgreen?style=for-the-badge" alt="Work Status">
</p>

---

## 🚀 Professional Snapshot

> **4+ years** architecting production-grade AI systems | **LLM/VLM/Speech AI** at scale | **60% latency reduction** | **99.9% uptime SLA**

I specialize in building end-to-end AI solutions—from data engineering and model fine-tuning to Dockerized microservices deployed on cloud and on-prem infrastructure. My focus: **reliable, optimized, and impactful AI products** for healthcare, fintech, SaaS, and enterprise domains.

### 🔑 Key Achievements
| Impact | Metric |
|--------|--------|
| ⚡ Inference Optimization | **60%↓ P99 latency**, **4x↑ throughput** using vLLM (PagedAttention, speculative decoding) |
| 🎯 Domain ASR | **35%↑ accuracy** fine-tuning Whisper; **12 min/user** time saved |
| 🤗 Structured LLM Output | **42%↓ hallucinations** via instruction-tuning Qwen on **500K+ samples** |
| 🔍 Retrieval Precision | **28%↑ precision@5** with agentic Graph-RAG + hybrid fusion |
| 🏗️ Production Reliability | **10K+ daily requests**, **99.9% uptime** via FastAPI + circuit breakers + observability |
| 🐳 Deployment Efficiency | **70%↓ cold-start** with Docker multi-stage + distroless images |

---

## 🛠️ Core Technical Stack

### 🧬 Large Language Models & Training
```python
# Fine-tuning & Alignment
SFT • DPO • RLHF • LoRA/QLoRA • Prefix/P-Tuning • Structured Output

# Model Families
Qwen • DeepSeek • Mistral • Llama 2/3 • Gemma • Phi • OpenAI • Claude

# Evaluation
BLEU/ROUGE • BERTScore • LLM-as-a-Judge • Bias/Fairness Auditing
```

### 🔍 RAG & Knowledge Systems
```python
# Vector DBs
Milvus • FAISS • Pinecone • Qdrant • Weaviate (HNSW, IVF, Quantization)

# Hybrid & Graph-RAG
Dense+Sparse Fusion • RRF • Cross-Encoder Reranking • Neo4j • Entity Linking • Path-Based Reasoning

# Agentic Patterns
ReAct • Plan-and-Execute • Tool Selection • Human-in-the-Loop • Multi-Tenant Isolation
```

### ⚙️ Inference Optimization & Serving
```python
# vLLM Internals
PagedAttention • Continuous Batching • Prefix Caching • Speculative Decoding • Chunked Prefill

# Quantization & Acceleration
AWQ • GPTQ • bitsandbytes (4/8-bit) • TensorRT-LLM • ONNX Runtime

# Observability
Prometheus/Grafana • OpenTelemetry • P50/P95/P99 Latency Tracking
```

### 🎙️ Speech & Multimodal AI
```python
# ASR & Audio
Whisper Fine-tuning • Domain Adaptation • Streaming Transcription • pyannote • RNNoise • VAD

# Vision-Language
CLIP • BLIP-2 • LLaVA • Medical Image Preprocessing • Histopathology Patch Analysis
```

### 🌐 Backend & MLOps
```python
# APIs & Data
FastAPI (4+ yrs) • Async/Await • PostgreSQL • Redis • MongoDB • GraphQL • gRPC

# Infrastructure
Docker (Multi-stage) • Kubernetes Concepts • GitHub Actions • AWS/GCP/Azure • Helm

# Reliability
Circuit Breakers • Retry/Backoff • Type Safety (mypy/pydantic) • Load Testing (Locust)
```

<details>
<summary><strong>📦 View Full Tooling & Languages</strong></summary>

**Languages**: Python (Expert) • SQL (Advanced) • Bash • TypeScript • C++ (Reading)  
**ML Frameworks**: PyTorch • TensorFlow • Scikit-learn • XGBoost • Hugging Face  
**LLM Tooling**: vLLM • TGI • LangChain • LlamaIndex • Guidance • Outlines • W&B • MLflow  
**Data Tools**: Pandas • Polars • Dask • Apache Arrow • DuckDB • dbt concepts  
**Dev Tools**: Git • pre-commit • ruff/black/mypy • VS Code • Jupyter • GitHub Copilot

</details>

---

## 💼 Featured Experience

### **Senior ML Engineer (AI Platform)** | Iran Nobat — *Apr 2024 – Present*
- Architected production AI platform: voice-to-structured-output, multimodal RAG, clinical workflow integration (**500+ DAU, 99.9% uptime**)
- Fine-tuned **Whisper-large-v3** for domain ASR: **+35% accuracy**, **-12 min/session** documentation time
- Instruction-tuned **Qwen-Instruct** on **500K+ samples** with LoRA/QLoRA: **-42% hallucinations**, **-68% formatting errors**
- Optimized inference with **vLLM**: **-60% P99 latency**, **4x throughput** via PagedAttention + speculative decoding
- Designed **Graph-RAG** system (Neo4j + Milvus): **+28% precision@5**, **+31% recall@10** via hybrid fusion & reranking
- Built unified LLM gateway (OpenAI/Gemini/Anthropic) with intelligent routing: **-22% inference costs**
- Containerized services with **Docker multi-stage + distroless**: **-70% cold-start**, zero-downtime blue-green deploys
- Delivered **PySide6 desktop app** packaged as Windows EXE via PyInstaller with automated Git release workflows

### **AI Engineer (Contract)** | OsLLM — *Remote (USA) • Jul–Oct 2024*
- Delivered production **hybrid RAG pipeline** (Milvus + FAISS): **+33% recall@10**, **-45% p95 latency** for multi-tenant apps
- Built **FastAPI wrappers** with async streaming, JWT auth, Redis caching; fully documented & tested for seamless handoff
- Implemented retrieval evaluation harnesses (NDCG, MRR) + observability layer (Prometheus, OpenTelemetry)

### **AI/ML Engineer** | KarLancer — *Remote • Mar 2023 – Apr 2024*
- Deployed **LLM-powered RAG chatbots** for customer support: **5K+ queries/month**, **92% resolution rate** without escalation
- Built **CNN models** for ECG/CT analysis: **94.2% AUC** with reproducible pipelines & model cards
- Designed **LSTM/Transformer forecasting** for financial time-series with async FastAPI deployment & autoscaling
- Implemented **DVC + W&B** for data versioning, experiment tracking, and model registry across client projects

<details>
<summary><strong>🔬 Earlier Experience & Projects</strong></summary>

### **ML Engineer (Computer Vision)** | Exon — *May–Oct 2023*
- Trained **YOLOv8** for real-time detection: **+18% mAP@0.5** via custom augmentations & hyperparameter tuning
- Optimized inference for edge: **3x speedup** via ONNX + TensorRT with minimal accuracy trade-off

### 🌟 Selected Projects
| Project | Tech Stack | Outcome |
|---------|-----------|---------|
| **Multimodal AI Assistant** | Whisper + Qwen + VLM + vLLM + FastAPI | **-40% documentation time**, sub-2s median response for 500+ users |
| **Agentic Triage System** | LangGraph-style agents + Tool Registry + FastAPI | **+31% routing accuracy**, **-8 min intake time**, seamless human escalation |
| **Hybrid Retrieval Engine** | Graph-RAG (Neo4j) + Vector DB (Milvus) + Reranking | **+28% precision@5**, **-37% hallucinations**, improved user trust scores |
| **Colon Cancer Histopathology** | Graph-Transformer + PyTorch DDP + WSI preprocessing | **SOTA on internal validation**, pipeline published in arXiv:2509.02851 |

</details>

---

## 📚 Publications

### Peer-Reviewed
- 📄 *A Comprehensive Review on Breast Cancer Detection Using Machine Learning Techniques*  
  **Advances in Applied Nano-Bio Technologies**, 2024 | [DOI: 10.18502/AANBT.V6I1.18227](https://doi.org/10.18502/AANBT.V6I1.18227)

### Preprints (arXiv)
- 🧬 *Machine Learning-Integrated Hybrid Fluid-Kinetic Framework for Quantum Electrodynamic Laser Plasma Simulations* — [arXiv:2510.11174](https://arxiv.org/abs/2510.11174)
- 🔗 *Topological Regularization for Force Prediction in Active Particle Suspension with EGNN and Persistent Homology* — [arXiv:2509.06574](https://arxiv.org/abs/2509.06574)
- 🌀 *Multi-Scale Modeling and Predictive Control of Active Brownian Particles* — [arXiv:2509.06217](https://arxiv.org/abs/2509.06217)
- 🧫 *Multi-Scale Deep Learning for Colon Histopathology: A Hybrid Graph-Transformer Approach* — [arXiv:2509.02851](https://arxiv.org/abs/2509.02851)

---

## 🎓 Education

| Degree | Institution | Year | Details |
|--------|-------------|------|---------|
| **M.Sc., Plasma Physics** | Iran University of Science & Technology | 2020–2023 | GPA: **17.49/20** (Top 5%) • Thesis: ML-accelerated computational solvers |
| **B.Sc., Solid State Physics** | Kharazmi University | 2015–2020 | GPA: **15.09/20** • Focus: Condensed matter theory, computational materials |

### 🏆 Certifications
```
DeepLearning.AI: ML Specialization • DL Specialization • Advanced Algorithms • 
Hyperparameter Tuning • Unsupervised Learning/Recommenders/RL
IBM: Unsupervised Machine Learning
```

---

## 🌍 Additional Info

- 🗣️ **Languages**: Persian (Native) • English (Professional: technical writing, presentations, collaboration)
- 🛂 **Work Authorization**: Open to **remote roles worldwide** • Eligible for **relocation with visa sponsorship**
- ⏰ **Availability**: Immediate start • Flexible across timezones for async collaboration & overlap hours
- 🎯 **Domain Flexibility**: Healthcare • Fintech • SaaS • Enterprise AI • Scientific Computing • Computer Vision
- 💡 **Open Source**: Active contributor to Hugging Face ecosystem, vLLM discussions, and ML tooling — *happy to share code samples upon request*

---

## 📬 Let's Connect

<p align="center">
  <a href="mailto:saremi.sadra@gmail.com">
    <img src="https://img.shields.io/badge/✉️_Email_Me-saremi.sadra@gmail.com-critical?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://linkedin.com/in/sadra-saremi">
    <img src="https://img.shields.io/badge/💼_LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://sadrasaremi1997.pythonanywhere.com">
    <img src="https://img.shields.io/badge/🌐_Portfolio-Explore-green?style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://github.com/sadrasa97">
    <img src="https://img.shields.io/badge/🐙_GitHub-Follow-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</p>

> ✨ *Currently exploring opportunities to drive high-impact AI products in remote or relocation-friendly roles. If you're building something ambitious with LLMs, RAG, or production MLOps — let's talk.*

---

