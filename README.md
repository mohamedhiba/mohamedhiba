<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=FFFFFF&center=true&vCenter=true&width=700&lines=Hey%2C+I'm+Hiba+%F0%9F%91%8B;AI%2FML+Engineer;Self-Supervised+Learning+%26+Computer+Vision;Building+production-grade+ML+systems" alt="Typing SVG" />

<br/>

**Computer Engineering @ CCNY · 4+1 M.S. Track · GPA 3.8**

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-mohamedhiba.com-0A0A0A?style=for-the-badge&logo=googlechrome&logoColor=white)](https://mohamedhiba.com/)
[![Email](https://img.shields.io/badge/Email-Contact-111111?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamedehiba@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mohamedhiba-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamedhiba)
[![Profile Views](https://komarev.com/ghpvc/?username=mohamedhiba&style=for-the-badge&color=0A0A0A&label=PROFILE+VIEWS)](https://github.com/mohamedhiba)

</div>

---

## About

I'm a Computer Engineering student at **The City College of New York** in the accelerated **4+1 M.S. track**, focused on building AI/ML systems that are not just trained — but evaluated, deployed, and usable.

My strongest interests:

- **Self-supervised & representation learning**
- **Computer vision & attention-aware systems**
- **NLP & language model fine-tuning**
- **ML productization** — inference, APIs, deployment, calibration

> **Currently:** Undergraduate researcher at the **CCNY Media Lab** (self-supervised learning for landslide susceptibility mapping) · ML intern at **Tactorum** (computer vision for behavioral research) · **CUNY Tech Prep** Data Science Fellow, Cohort 12

---

## 3D Contribution Graph

<div align="center">

![3D contribution graph](./profile-3d-contrib/profile-night-rainbow.svg)

</div>

---

## Featured Projects

### SSL for Landslide Susceptibility Mapping — CCNY Media Lab
> `PyTorch` &nbsp;·&nbsp; `ResNet-18` &nbsp;·&nbsp; `Self-Supervised Pretraining` &nbsp;·&nbsp; `Geospatial ML`

Full geospatial deep learning pipeline advised by Prof. YingLi Tian, in collaboration with Penn State and Stony Brook researchers. Self-supervised pretraining (masked-autoencoder + contrastive objectives) raised AUC **0.860 → 0.905** and worst-region robustness **0.59 → 0.85**. Scaled to a 24 GB, 13-channel terrain corpus (50k pretraining patches, 18k labels), reaching **0.955 ± 0.001 AUC** across 4 seeds / 5-fold CV. Found and fixed spatial leakage in the lab's k-fold splits via group-safe CV. Ran 300+ multi-seed training runs on rented GPUs for under $10 with automated job resumption and monitoring.

### ResolveNYC: 311 Complaint Resolution Classifier | PyTorch, Hugging Face Transformers, scikit-learn
> [repo](https://github.com/mohamedhiba/ResolveNYC) &nbsp;·&nbsp; [demo](https://huggingface.co/spaces/Mohamedhiba/resolvenyc-demo) &nbsp;·&nbsp; ML lead, 4-person team

Multimodal DistilBERT + tabular MLP for 4-class resolution-time classification over 100k NYC 311 records. Inverse-frequency weighting, ordinal loss, and dual learning rates took the best of five models to **77.7% accuracy / 0.753 macro-F1**, beating logistic regression and XGBoost baselines. Shipped to Hugging Face Hub with sub-2s CPU inference.

### focusedAI: Real-Time Attention State Classifier
> [repo](https://github.com/mohamedhiba/focusedAI) &nbsp;·&nbsp; [demo](https://huggingface.co/spaces/Mohamedhiba/focusedAI-demo) &nbsp;·&nbsp; `MobileNetV3-Small` &nbsp;·&nbsp; `PyTorch` &nbsp;·&nbsp; `OpenCV`

Webcam-based 3-class attention classifier (`focused / neutral / distracted`). Hit **0.918 macro-F1** at **4–5ms p95** on-device inference (M3 Pro, MPS), stabilized via temperature scaling, per-class logit biases, and hysteresis. Ships with an interactive Gradio demo.

### lstm-keyboard-v2 — Next-Word Prediction
> [repo](https://github.com/mohamedhiba/lstm-keyboard-v2) &nbsp;·&nbsp; [live API](https://lstm-keyboard-demo-743198811832.us-central1.run.app/) &nbsp;·&nbsp; `PyTorch LSTM` &nbsp;·&nbsp; `FastAPI` &nbsp;·&nbsp; `Docker` &nbsp;·&nbsp; `Cloud Run`

Word-level LSTM trained from scratch on WikiText-2, packaged as a portable model bundle and served via FastAPI on Cloud Run, with automated Docker container builds.

### FP8 Adder & Parallel Kernels | MIPS Assembly, VHDL, C

Parallel MIPS and VHDL kernels for an FP8 adder, dot product, and matrix-multiply benchmarks, with synchronization primitives and virtual-memory management implemented at the OS level.

**More public work:** [tabular-ml-playbook](https://github.com/mohamedhiba/tabular-ml-playbook) · [fastcard](https://github.com/mohamedhiba/fastcard) · [discord-pomodoro-bot](https://github.com/mohamedhiba/discord-pomodoro-bot) · [provisional](https://github.com/mohamedhiba/provisional) ([live](https://provisional-beta.vercel.app/))

---

## Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Backend & Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

## GitHub Activity

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=mohamedhiba&hide_border=true&theme=dark)](https://github.com/mohamedhiba)

</div>

<div align="center">
  
[![Mohamed's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=mohamedhiba&theme=high-contrast)](https://github.com/ashutosh00710/github-readme-activity-graph)
</div>

<br/>

---

## Experience

**Undergraduate Researcher — CCNY Media Lab (Prof. YingLi Tian)** · April 2026 – Present
Self-supervised learning for landslide susceptibility mapping; sole owner of the deep-learning codebase.

**Machine Learning Intern — Tactorum (Remote, via CCNY CiPASS)** · July 2026 – Present
Computer-vision pipeline for automated rodent behavioral analysis in pain-research assays.

**Data Science Fellow, Cohort 12 — CUNY Tech Prep** · May 2026 – Present
Year-long, industry-taught data science program; end-to-end ML projects presented at Demo Night.

**Computer Science Intern — Globetrotting Dominicana LLC** · May 2025 – July 2025
Admin dashboard, REST integrations, Docker containerization, GitHub Actions CI/CD.

**Undergraduate Teaching Assistant — Hunter College (CSCI 127/135)** · August 2023 – May 2026
Top-performing TA, two consecutive semesters. 100+ 1-on-1 sessions in Python & C++.

---

<div align="center">

*Open to ML engineering internships, AI research, and software roles with strong AI/ML exposure*

[![Email](https://img.shields.io/badge/mohamedehiba%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mohamedehiba@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamedhiba)

</div>
