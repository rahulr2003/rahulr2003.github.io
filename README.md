---
layout: default
title: Rahul Ravi
description: Machine Learning Researcher — Medical Imaging, Geoscience, Electron Microscopy
---

# Rahul Ravi

Interested in developing and rigorously evaluating resource-efficient scientific ML methods that generalise across acquisition regimes and deployment contexts — with experience spanning medical imaging, geoscience, electron microscopy, and power electronics through independent and collaborative research.

📧 rahul.ravi0623@gmail.com&nbsp;&nbsp;|&nbsp;&nbsp;📱 (+91) 9606736263&nbsp;&nbsp;|&nbsp;&nbsp;[LinkedIn](#)&nbsp;&nbsp;|&nbsp;&nbsp;[GitHub](#)

---

## Education

**MSc (Integrated) Computer Science** — University of Nottingham *(Sept 2021 – July 2025)*
2:1 Honours · Specialization: Machine Learning, Data Science, Computer Vision
Best Individual CS Research Project (Runner-up)

---

## Publications

<details>
<summary><strong>Cross-Regional Seismic Hazard Forecasting Across Diverse Tectonic Regimes via Frozen Geological Priors</strong> — Under review, Computers & Geosciences, 2026 (Preprint)</summary>

R. Ravi. Proposes a frozen geological prior GNN architecture for parameter-efficient cross-regional seismic hazard transfer, evaluated via a Monte Carlo Patch Cycling framework across 8 tectonic regimes.
</details>

<details>
<summary><strong>Breast Cancer Neoadjuvant Chemotherapy Treatment Response Prediction Using Aligned Longitudinal MRI and Clinical Data</strong> — Under review, Informatics in Medicine Unlocked, 2025 (Preprint)</summary>

R. Ravi, R. Li, T. Abdelfatah, S. Chan, X. Chen. Predictive modelling framework combining registered longitudinal MRI and clinical data to forecast pathological complete response and relapse-free survival.
</details>

---

## Experience & Research Projects

*Sorted by most recent (ongoing roles listed first, then by end date)*

<details>
<summary><strong>Co-Founder | Auxi Studios</strong> — Sept 2025 – Present</summary>

- Designed and productionized ORAS, an interactive business simulation tool with a real-time resource allocation engine
- Ran production testing with 28 users across two focus groups, identifying and fixing critical race conditions
- Built a scalable, zero-install, browser-based architecture optimized for accessibility and concurrent usage
</details>

<details>
<summary><strong>ATP: An Auto-Tagging Pipeline for Wildlife Conservatories</strong> — May 2026 – Present</summary>

- Applied transfer learning for animal detection using pre-trained models (SpeciesNet, built on YOLOv5)
- Ran ablations on dynamic thresholding and custom evaluation methods, achieving >97% accuracy (<1% std) under low-light, blurry, and distorted conditions
- Architected a hierarchical detection and species classification pipeline across >75k camera-trap images spanning 40 species and 10 families
- Implemented Grad-CAM for feature attribution via backward gradient propagation
- Extending the pipeline with re-identification and longitudinal health monitoring methods
</details>

<details>
<summary><strong>Research Assistant — Computer Science | University of Nottingham</strong> — Sept 2023 – Present</summary>

**Breast Cancer Treatment Response Prediction** ([Paper](#))
- Built a predictive modelling framework analysing 1,700+ longitudinal MRI scans across 600 patients to forecast pathological treatment response (PCR) and relapse-free survival (RFS)
- Engineered an automated feature extraction pipeline combining radiomics and deep learning representations, reducing manual feature engineering
- Implemented intensity-based image registration, improving PCR/RFS prediction AUC by 0.02 (Wilcoxon signed-rank, p=0.01)
- Showed radiomic features outperform deep learning representations pretrained on external medical tasks, preserving interpretability without sacrificing performance (p < 0.05)

**High Spatial-Temporal Resolution Electron Microscopy Imaging**
- Developing self-supervised denoising models for electron microscopy under zero ground-truth conditions across STEM/HRTEM modalities
- Designed an adaptive quantile-based patch sampling algorithm, cutting training time by 25% while maintaining ~4 dB SNR improvement
- Validated robustness across microscopy modalities and noise regimes through systematic benchmarking
</details>

<details>
<summary><strong>Seismic Hazard Modelling using Geological Priors and Catalog Features</strong> — Jan 2026 – June 2026</summary>

- Developed **GeoSeisML-12**, the first multi-regime ML-ready seismic hazard benchmark spanning 12 patches across 8 tectonic regimes on 4 continents
- Proposed a frozen geological prior GNN architecture enabling parameter-efficient cross-regional transfer by adapting only 1.6% of model parameters
- Introduced the **Monte Carlo Patch Cycling (MCPC)** evaluation framework — 1,299 randomised cross-regional evaluations with leakage-free prior construction
- Achieved mean cross-regional transfer degradation of just 0.20% relative to in-distribution performance across 5 checkpoints and 8 tectonic regimes
- *Paper under review at Computers & Geosciences*
</details>

<details>
<summary><strong>Research Assistant — Engineering (PEMC) | University of Nottingham</strong> — Feb 2025 – Jan 2026</summary>

**MotorGPT: Data-Driven Electrical Machine Design Optimization**
- Developed surrogate ML models replacing expensive physics simulations, cutting design evaluation time from hours to minutes
- Integrated hard engineering constraints to ensure physical feasibility of generated designs
- Quantified accuracy-efficiency trade-offs between surrogate predictions and simulation baselines
- Built a user-facing interface for domain experts with no programming background
</details>

<details>
<summary><strong>Research Intern — High-Performance Computing | Shell</strong> — Jun 2023 – Sept 2023</summary>

- Developed a semi-automatic seismic image segmentation framework for mineral exploration using foundation vision models
- Finetuned SAM (Segment Anything Model) for seismic facies segmentation on a large-scale internal dataset
- Implemented GPU-accelerated training on HPC clusters, cutting model iteration time from days to hours
- Built reproducible PyTorch pipelines with version control, experiment tracking, and automated testing
</details>

---

## Skills

**Programming:** Python (PyTorch, Scikit-learn, Pandas, NumPy), MATLAB, SQL, Git
**ML & Methods:** Self-supervised learning, image segmentation & registration, feature extraction, graph neural networks, surrogate modelling, statistical hypothesis testing
**Computing:** HPC/GPU acceleration (CUDA), Databricks, Slurm
**Domain Tools:** Medical imaging & longitudinal clinical data, geospatial analysis (ArcGIS Pro, QGIS), electron microscopy (HRTEM/STEM, Fiji)

---

## Get in Touch

Feel free to reach out via [email](mailto:rahul.ravi0623@gmail.com) or connect on [LinkedIn](#).
