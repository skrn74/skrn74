# 👋 Hi, I'm Sai Kiran Tiridu

### Cloud | DevOps | SRE | AIOps Engineer

I work at the intersection of **Cloud Infrastructure, DevOps, Site Reliability Engineering, Automation, and AI-assisted Operations**.

My experience is centered around building and operating cloud-native environments using **AWS, Kubernetes, Docker, Terraform, CI/CD, Python, Linux, and observability tooling**.

More recently, I've been exploring how **Generative AI can augment traditional SRE workflows**, particularly by combining deterministic monitoring with evidence-grounded LLM analysis.

> **Automate the repetitive. Observe the critical. Use AI to accelerate investigation. Keep humans in control.**

---

## 🚀 What I'm Working On

- ☁️ **Cloud & AWS**: Cloud infrastructure, networking, deployments, troubleshooting, and cost optimization
- ⚙️ **DevOps**: CI/CD automation, Docker, Git-based delivery workflows, and Infrastructure as Code
- ☸️ **Kubernetes**: Application deployments, troubleshooting, monitoring, incident simulation, and GitOps
- 📊 **SRE & Observability**: Prometheus, Alertmanager, Kubernetes metrics, operational troubleshooting, and incident analysis
- 🤖 **AIOps**: Experimenting with LLM-assisted Kubernetes incident triage and evidence-grounded AI
- 🐍 **Python Automation**: Building automation around cloud and Kubernetes operational workflows

---

# 🤖 AIOps & AI-Assisted SRE

I'm currently exploring how **AI can complement traditional observability and incident-response systems rather than replace them**.

My approach is:

```text
Monitoring detects the problem
          ↓
Automation gathers evidence
          ↓
AI analyzes the evidence
          ↓
SRE validates the recommendation
          ↓
Human-controlled remediation
```

The goal is to reduce repetitive investigation effort while keeping operational decisions **observable, explainable, and human-controlled**.

---

# 🧠 Featured Project: Kubernetes Incident Copilot

### AI-Assisted Kubernetes Incident Triage

I built an event-driven **Kubernetes Incident Copilot** as a personal AIOps/SRE project.

```text
Kubernetes
     ↓
kube-state-metrics
     ↓
Prometheus
     ↓
Alertmanager
     ↓
Python / Flask
     ↓
Kubernetes Evidence Collection
     ↓
Ollama
     ↓
Mistral LLM
     ↓
Grounded Incident Diagnosis
     ↓
Human SRE
```

The project detects abnormal Kubernetes container restart behavior using **Prometheus** and automatically routes the alert through **Alertmanager** to a **Python Flask webhook**.

Python collects runtime evidence such as **pod state, Kubernetes events, and previous container logs** before sending the evidence to a locally hosted **Mistral** model through **Ollama**.

The LLM produces:

- 🔍 Incident diagnosis
- 📊 Confidence level
- 🛠️ Suggested read-only troubleshooting checks

The AI component remains **read-only and advisory**, with remediation intentionally left under human control.

### 💡 Key Design Principle

> **Prometheus detects. Alertmanager triggers. Python investigates. Kubernetes provides evidence. Ollama serves Mistral. Mistral interprets the evidence. The SRE decides.**

---

# 🛠️ Technical Skills

### ☁️ Cloud

![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?logo=amazonaws&logoColor=white)

- AWS
- EC2, VPC, S3, IAM
- ALB, ECR, EKS, CloudWatch
- AWS networking and security

### ☸️ Containers & Kubernetes

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

- Kubernetes
- Docker
- Kind
- Helm
- Argo CD
- Kubernetes troubleshooting
- GitOps

### 🏗️ Infrastructure as Code

![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)

- Terraform
- Modular infrastructure
- Infrastructure automation
- Environment provisioning

### 🔄 CI/CD

![GitLab](https://img.shields.io/badge/GitLab_CI/CD-FC6D26?logo=gitlab&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)

- Git
- GitHub
- GitLab CI/CD
- Docker image pipelines
- Deployment automation
- AWS deployment workflows

### 📊 SRE & Observability

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)

- Prometheus
- Alertmanager
- kube-state-metrics
- Kubernetes events & logs
- Incident troubleshooting
- Monitoring and alerting

### 🤖 AIOps / Generative AI

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-000000?logo=ollama&logoColor=white)

- Ollama
- Mistral
- Evidence-grounded prompting
- LLM-assisted incident triage
- Python-based Kubernetes evidence collection
- Human-in-the-loop operational workflows

---

# 🔬 Projects

## 🤖 Kubernetes Incident Copilot

**Prometheus | Alertmanager | Python | Kubernetes | Ollama | Mistral**

Event-driven AIOps project that automatically collects Kubernetes incident evidence and provides an AI-assisted diagnosis while keeping remediation human-controlled.

## ☸️ Kubernetes / AWS EKS Deployments

Hands-on containerization and Kubernetes deployment projects covering application packaging, Amazon ECR, EKS deployments, and troubleshooting.

## ☁️ Cloud & DevOps Automation

Hands-on work and personal labs around:

- AWS infrastructure
- Terraform
- Docker
- Kubernetes
- CI/CD
- Python automation
- Monitoring
- Operational troubleshooting

---

# 🎯 Currently Exploring

```text
Traditional SRE
      +
Observability
      +
Python Automation
      +
Generative AI
      ↓
     AIOps
```

I'm particularly interested in:

- AI-assisted incident investigation
- Kubernetes troubleshooting automation
- Observability + LLM integration
- Evidence-grounded AI
- Automated operational runbooks
- GitOps
- Cloud cost optimization
- SRE engineering

---

# 🧩 Engineering Philosophy

I prefer using AI as an **operational copilot rather than an autonomous administrator**.

```text
Detect → Collect Evidence → Analyze → Recommend → Human Decision
```

This keeps automation useful while preserving **safety, transparency, and operational control**.

---

# 📜 Certification

### AWS Certified Solutions Architect – Associate

---

# 📚 Continuous Learning

Currently strengthening my skills across:

```text
AWS
Kubernetes
Terraform
Python
SRE
Observability
AIOps
Generative AI
```

I enjoy building hands-on labs, deliberately breaking systems, troubleshooting the failures, and converting what I learn into reusable automation.

---

# 🤝 Let's Connect

I'm interested in opportunities and conversations around:

**Cloud Engineering • DevOps • SRE • Kubernetes • AWS • Platform Engineering • AIOps • AI-Assisted Operations**

📍 Hyderabad, India

🔗 [GitHub Profile](https://github.com/skrn74)

---

### ⭐ Build. Break. Observe. Automate. Learn. Repeat.
