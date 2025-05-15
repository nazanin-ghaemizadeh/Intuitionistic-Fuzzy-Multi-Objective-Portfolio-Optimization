
# 💼 Iterative Intuitionistic Fuzzy Linear Programming Approach to Multi-Objective Portfolio Optimization: A Sustainable Integration of Mean-Variance Framework and Return Entropy

This repository presents a novel sustainable investment framework for portfolio optimization. The model integrates **sustainability**, **return**, **risk (variance)**, and **uncertainty (entropy)** using **Trapezoidal Intuitionistic Fuzzy Sets (TIFS)**. Optimization is performed through a customized **Iterative Intuitionistic Fuzzy Linear Programming (IIFLP)** method under real-world constraints.

---

## 📘 Project Summary

Traditional models often ignore sustainability and uncertainty in financial decision-making. This research introduces a fuzzy multi-objective model that:

* Models ambiguity using **TIFS**
* Uses **Shannon entropy** to represent uncertainty
* Incorporates **social, environmental, and economic (SEE)** sustainability factors
* Applies **IIFLP** for iterative fuzzy optimization
* Benchmarks performance against a **Buy-and-Hold** strategy

A real-world case study using **Tehran Stock Exchange (TSE)** data validates the model.

---

## 🎯 Objectives

Maximize:

* ✅ Sustainability
* ✅ Expected Return

Minimize:

* ⚠️ Risk (Variance)
* ⚠️ Uncertainty (Entropy)

All objectives are modeled with **membership and non-membership functions** in an intuitionistic fuzzy environment.

---

## 🔍 Dataset

* **Market**: Tehran Stock Exchange (TSE), Iran
* **Assets**: 10 risky assets
* **Inputs**:

  * Historical return data
  * Expert-rated sustainability scores (via fuzzy linguistic terms)
* **Evaluators**: 3 domain experts using SEE criteria

---

## 🧮 Methodology Highlights

* **TIFNs** for modeling vagueness in sustainability and return
* **TIF-SEW**: New Shannon entropy-based weighting for sustainability
* **MCGDM**: Multi-expert aggregation for sustainability scoring
* **IIFLP**: Solves a fuzzy multi-objective model iteratively
* **Scenarios**: Sustainable, Bearable, Viable, Equitable

---

## ⚙️ Workflow

1. Fuzzy evaluation of sustainability
2. Entropy-based TIF-SEW weighting
3. TIFS modeling of sustainability and returns
4. IF objective formulation: return, risk, sustainability, entropy
5. Apply constraints:

   * Capital budget
   * Cardinality
   * Flexible bounds
   * No short-selling
6. Solve using Pyomo (IIFLP)
7. Perform scenario and sensitivity analysis (γ ∈ \[0,1])
8. Benchmark against Buy-and-Hold

![Framework](https://github.com/user-attachments/assets/f5f6c360-f179-44b3-ad3e-d1695ef3b79b)

---

## 🛠 Tools

* **Language**: Python 3.10
* **Framework**: Pyomo
* **Solver**: GLPK
* **Libraries**: `numpy`, `pandas`, `matplotlib`

---

## 📊 Results Snapshot

* TIF-SEW effectively ranked SEE sub-criteria based on expert input
* IIFLP outperformed Buy-and-Hold in return and sustainability metrics
* Trade-offs visible through γ sensitivity (sustainability vs. return)
* Flexible portfolios aligned with investor sustainability preferences

---

## 📈 Key Contributions

🔹 **Enhanced Uncertainty Representation with TIFS**
Utilizes flexible continuous membership/non-membership functions, offering more nuanced modeling than classic fuzzy sets.

🔹 **TIF Linguistic Scale Framework**
Bridges qualitative sustainability ratings with quantitative optimization objectives in uncertain environments.

🔹 **Customizable Sustainability Evaluation**
Supports portfolio tailoring across SEE-based priorities: bearable, viable, and equitable.

🔹 **Advanced MCDGM & TIF-SEW Weighting**
Incorporates expert judgment and entropy-based dispersion measures to derive robust sustainability scores.

🔹 **Expanded Financial Metrics & Realistic Constraints**
Integrates entropy into the traditional return-risk model, with practical constraints like budget, cardinality, and flexible bounds.

🔹 **IF Multi-Objective Model via IIFLP**
Maximizes fuzzy membership and minimizes non-membership through iterative refinement.

🔹 **Practical Python Package**
Includes tools for TIFS operations, sustainability assessment, fuzzy aggregation, entropy modeling, and portfolio optimization with comparison tools.
