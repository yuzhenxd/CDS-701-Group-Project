# CDS701 FreddieMac Project

**Does Macroeconomic Information Improve Mortgage Delinquency Prediction? Evidence from Freddie Mac Loan-Level Data**

香港岭南大学 CDS701 Fundamentals of Computer Science 小组机器学习项目。

Lingnan University, Hong Kong · CDS701 Fundamentals of Computer Science · Group Machine Learning Project

---

## 📦 Project Files

项目文件以压缩包形式放在 [Releases](../../releases) 中下载：

Project files are available for download in [Releases](../../releases):

- **`GitHub_Submission_2026-11-22.zip`** (5.9 MB)  
  精简后的内容，包含核心代码、notebooks、结果和文档。  
  Condensed version with core code, notebooks, results, and documentation.

- **`FreddieMac_Project.zip`** (367 MB)  
  完整项目，包含所有代码、notebooks、训练模型、结果和数据。  
  Full project with all code, notebooks, trained models, results, and data.

---

## 📖 Project Overview

本项目探究宏观经济信息是否能够改善房贷违约预测。基于 Freddie Mac 贷款级数据，我们构建了微观特征模型和宏观特征增强模型，并通过时间外验证评估预测能力。

This project investigates whether macroeconomic information improves mortgage delinquency prediction. Using Freddie Mac loan-level data, we build micro-feature models and macro-enhanced models, evaluating their predictive power through temporal out-of-sample validation.

**Key Features:**
- Loan-level analysis with 488,985 observations
- Temporal split: train on 2014–2022, validate on 2023, test on 2024
- Target: 90+ day serious delinquency within 12 months
- Models: Logistic Regression, Random Forest, XGBoost, CatBoost
- Macro features from FRED (ALFRED vintage data)

---

## 🚀 Quick Start

1. Download either zip file from [Releases](../../releases)
2. Extract and explore:
   - `notebooks/` — Jupyter notebooks for EDA and model training
   - `models/` — Trained model files
   - `results/` — Evaluation metrics and outputs
   - `README.md` (inside zip) — Detailed project documentation

---

## 📄 License & Data Source

**Data Source:**  
Freddie Mac Single-Family Loan-Level Dataset  
https://www.freddiemac.com/research/datasets/sf-loanlevel-dataset

**Usage Note:**  
原始数据受 Freddie Mac 使用条款约束，本仓库不直接包含原始数据文件。  
Raw data is subject to Freddie Mac terms of use and is not included directly in this repository.

---

## 👥 Team

CDS701 小组成员 | Group Members

*(Add team member names here)*

---

**Last Updated:** 2026-11-22
