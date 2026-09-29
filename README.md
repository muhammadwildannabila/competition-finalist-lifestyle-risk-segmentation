<div align="center">

# Lifestyle Risk Segmentation for Public Health Campaigns

### Explainable Risk Analytics · Population Segmentation · Public Health Intelligence

**Finalist - Data Analyst Competition, DevFest Surabaya 2025**

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![EDA](https://img.shields.io/badge/EDA-0F766E?style=flat-square)
![Risk Analytics](https://img.shields.io/badge/Risk%20Analytics-7C3AED?style=flat-square)
![Public Health](https://img.shields.io/badge/Public%20Health-DC2626?style=flat-square)

<br>

![Competition](https://img.shields.io/badge/DEVFEST%20SURABAYA-2025-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Achievement](https://img.shields.io/badge/ACHIEVEMENT-FINALIST-22C55E?style=for-the-badge)

<br><br>

**1,545 Individuals · 3 Risk Segments · Explainable Scoring · Campaign Intelligence**

<br>

[![Presentation](https://img.shields.io/badge/View-Competition%20Presentation-00C4CC?style=for-the-badge&logo=canva&logoColor=white)](https://canva.link/7m8dcxcqrklozjo)

</div>

---

## Project at a Glance

<table>
<tr>
<td align="center" width="20%">
<strong>1,545</strong><br>
Individuals
</td>
<td align="center" width="20%">
<strong>3</strong><br>
Risk Segments
</td>
<td align="center" width="20%">
<strong>≈28%</strong><br>
High Risk
</td>
<td align="center" width="20%">
<strong>Explainable</strong><br>
Risk Scoring
</td>
<td align="center" width="20%">
<strong>Finalist</strong><br>
DevFest 2025
</td>
</tr>
</table>

> **Project focus:** Transforming lifestyle and physiological indicators into interpretable population-risk segments for more targeted public health campaign planning.

---

# Problem Context

Public health campaigns often address populations with substantially different lifestyle and physiological risk profiles.

A uniform intervention strategy may overlook these differences.

The analytical challenge is therefore not simply to identify whether risk factors exist, but to determine:

> ### How can multiple lifestyle and physiological indicators be transformed into transparent population segments that support targeted preventive campaigns?

This project develops an **explainable risk-segmentation framework** that converts selected indicators into an interpretable composite score and groups individuals into:

<div align="center">

![Low Risk](https://img.shields.io/badge/LOW%20RISK-Priority%203-22C55E?style=for-the-badge)
![Medium Risk](https://img.shields.io/badge/MEDIUM%20RISK-Priority%202-F59E0B?style=for-the-badge)
![High Risk](https://img.shields.io/badge/HIGH%20RISK-Priority%201-DC2626?style=for-the-badge)

</div>

The framework is intended for **analytical segmentation and campaign prioritization**, not medical diagnosis or individual clinical decision-making.

---

## Project Visualization

<p align="center">
  <img src="assets/problem-overview.png" alt="Lifestyle Risk Segmentation Problem Overview" width="900">
</p>

The analysis connects lifestyle and physiological indicators with an interpretable segmentation framework designed to support population-level prevention strategies.

---

# Analytical Objectives

The project was designed to:

- Quantify selected lifestyle-related risk indicators.
- Construct an interpretable composite risk score.
- Segment individuals into Low, Medium, and High Risk groups.
- Identify variables associated with elevated risk profiles.
- Analyze demographic and behavioral patterns across segments.
- Translate analytical findings into campaign-oriented recommendations.
- Preserve interpretability throughout the analytical workflow.

---

# Dataset & Analytical Scope

| Dimension | Scope |
|---|---|
| **Sample size** | **1,545 individuals** |
| **Domain** | Public Health Analytics |
| **Primary variables** | BMI, Blood Pressure, Smoking, Physical Activity, Diabetes History |
| **Output** | Low · Medium · High Risk |
| **Scoring strategy** | Weighted Composite Risk Score |
| **Segmentation strategy** | Quantile-Based Segmentation |
| **Analysis** | EDA · Risk Profiling · Segment Comparison |
| **Primary use case** | Public Health Campaign Prioritization |

The framework combines behavioral and physiological information to create a **population-level analytical representation of relative risk**.

---

# Analytical Framework

```text
                    RAW HEALTH & LIFESTYLE DATA
                               │
                               ▼
                       Data Validation
                               │
                               ▼
                     Cleaning & Normalization
                               │
                               ▼
                      Feature Engineering
                               │
                  ┌────────────┴────────────┐
                  ▼                         ▼
             BMI Parsing             Blood Pressure
                  │                         │
                  └────────────┬────────────┘
                               ▼
                  Composite Risk Scoring
                               │
                               ▼
                   Quantile Segmentation
                               │
             ┌─────────────────┼─────────────────┐
             ▼                 ▼                 ▼
          LOW RISK        MEDIUM RISK        HIGH RISK
             │                 │                 │
             └─────────────────┼─────────────────┘
                               ▼
                 Segment-Level Analysis
                               │
                               ▼
                    Insight Extraction
                               │
                               ▼
                  Campaign Recommendations
```

The workflow emphasizes **transparency and traceability**: each analytical stage can be interpreted without relying on a black-box prediction mechanism.

---

# Risk Segmentation Logic

Rather than producing a clinical diagnosis, the framework combines selected indicators into a **composite analytical score**.

Conceptually:

```text
Risk Score
    │
    ├── BMI-related indicator
    ├── Blood-pressure indicator
    ├── Smoking behavior
    ├── Physical activity
    └── Diabetes history
            │
            ▼
     Weighted Aggregation
            │
            ▼
       Relative Risk Score
            │
            ▼
     Quantile Segmentation
```

This design prioritizes two properties:

| Principle | Purpose |
|---|---|
| **Interpretability** | Make the contribution of selected indicators understandable |
| **Segmentation** | Convert continuous scores into operational population groups |

> Risk categories represent **relative analytical segments within the studied dataset** and should not be interpreted as validated clinical classifications.

---

# Evidence at a Glance

<table>
<tr>
<td align="center" width="33%">

### ≈28%

**High-Risk Segment**

Approximately 28% of the analyzed population was assigned to the High Risk group.

</td>
<td align="center" width="33%">

### 3 Segments

**Population Stratification**

Low Risk · Medium Risk · High Risk

</td>
<td align="center" width="33%">

### Multi-Factor

**Risk Profiling**

Lifestyle and physiological indicators were analyzed jointly.

</td>
</tr>
</table>

---

# Key Analytical Findings

## 01 · A Distinct High-Risk Segment Emerged

<div align="center">

![High Risk Population](https://img.shields.io/badge/HIGH%20RISK%20SEGMENT-%E2%89%8828%25-DC2626?style=for-the-badge)

</div>

Approximately **28% of the analyzed population** was classified within the High Risk segment under the project's scoring and quantile-segmentation framework.

This group represents a potential priority population for further assessment and targeted preventive communication.

---

## 02 · Multiple Indicators Shaped Elevated Risk Profiles

The analysis highlighted three particularly important dimensions:

<div align="center">

![Blood Pressure](https://img.shields.io/badge/Blood%20Pressure-Key%20Indicator-E11D48?style=flat-square)
![BMI](https://img.shields.io/badge/BMI-Key%20Indicator-F97316?style=flat-square)
![Physical Activity](https://img.shields.io/badge/Physical%20Activity-Key%20Indicator-2563EB?style=flat-square)

</div>

Within the project's scoring framework, blood-pressure characteristics, BMI, and physical inactivity contributed substantially to elevated risk profiles.

These findings provide interpretable dimensions for segment-level analysis.

---

## 03 · Risk Profiles Varied Across Age and Obesity Indicators

Higher-risk segments showed stronger representation among observations associated with increasing age and obesity-related indicators.

This suggests that population segmentation can reveal patterns that are less visible when all individuals are analyzed as a single homogeneous group.

---

## 04 · Interpretability Was Preserved by Design

The analytical framework intentionally favors a transparent scoring architecture.

Instead of asking only:

> **Who belongs to the highest-risk segment?**

the framework also supports:

> **Which measured indicators contributed to that segmentation?**

This distinction improves analytical traceability and makes the resulting segmentation easier to communicate to non-technical stakeholders.

---

# Analytical Workflow

## Problem Definition

<p align="center">
  <img src="assets/problem-overview.png" alt="Public Health Problem Definition" width="880">
</p>

---

## Data Understanding

<p align="center">
  <img src="assets/data-understanding.png" alt="Dataset Understanding" width="880">
</p>

---

## Data Preparation

<p align="center">
  <img src="assets/data-preparation.png" alt="Health Data Preparation" width="880">
</p>

---

## Exploratory Data Analysis

<p align="center">
  <img src="assets/exploratory-data-analysis.png" alt="Exploratory Data Analysis" width="880">
</p>

---

## Risk Modeling & Segmentation

<p align="center">
  <img src="assets/modeling-analysis.png" alt="Risk Modeling and Segmentation" width="880">
</p>

---

## Visualization & Insight

<p align="center">
  <img src="assets/visualization-insight.png" alt="Risk Segmentation Visualization and Insight" width="880">
</p>

---

## Results & Recommendations

<p align="center">
  <img src="assets/results-recommendation.png" alt="Results and Public Health Recommendations" width="880">
</p>

---

## Conclusion

<p align="center">
  <img src="assets/conclusion.png" alt="Project Conclusion" width="880">
</p>

---

# From Segmentation to Campaign Intelligence

```text
                  POPULATION DATA
                        │
                        ▼
                  RISK PROFILING
                        │
        ┌───────────────┼───────────────┐
        ▼               ▼               ▼
     LOW RISK       MEDIUM RISK      HIGH RISK
        │               │               │
        ▼               ▼               ▼
   Awareness         Prevention      Priority
   Messaging         Education       Outreach
        │               │               │
        └───────────────┼───────────────┘
                        ▼
               TARGETED CAMPAIGN
```

The analytical value lies in converting a heterogeneous population into **interpretable segments that can support differentiated campaign strategies**.

---

# Potential Campaign Applications

| Segment | Potential Campaign Strategy |
|---|---|
| **Low Risk** | General health awareness and maintenance |
| **Medium Risk** | Preventive education and behavior-focused engagement |
| **High Risk** | Prioritized outreach and recommendation for appropriate professional assessment |

The framework may support:

- Population prioritization
- Campaign audience segmentation
- Preventive communication design
- Resource-allocation analysis
- Health-promotion planning
- Evidence-informed program discussion

> These are **potential analytical applications**, not demonstrated clinical or population-health outcomes.

---

# Explainability by Design

A central design requirement was ensuring that segmentation remained understandable.

```text
BLACK-BOX APPROACH
Input ───────────────► Prediction
          ?

EXPLAINABLE APPROACH
Input
  │
  ▼
Risk Indicators
  │
  ▼
Explicit Scoring
  │
  ▼
Risk Segment
  │
  ▼
Interpretable Rationale
```

For this use case, interpretability is particularly important because analytical outputs may ultimately be communicated to stakeholders who need to understand **why a population segment receives greater campaign priority**.

---

# Technical Challenge

### Challenge

The central challenge was combining multiple behavioral and physiological indicators while maintaining an analytical framework that remained:

`Transparent` · `Interpretable` · `Comparable` · `Actionable`

### Approach

The team used:

1. Structured data cleaning and normalization.
2. Domain-oriented feature engineering.
3. Explicit weighted risk scoring.
4. Quantile-based segmentation.
5. Segment-level exploratory analysis.
6. Visual interpretation of resulting patterns.

The resulting framework balances **analytical structure with practical interpretability** without presenting the output as a clinical diagnostic model.

---

# My Contribution

### Muhammad Wildan Nabila
**Lead Data Scientist**

I led the analytical design of the project, with primary responsibilities including:

- Designing the analytical framework and methodology.
- Developing the weighted risk-scoring approach.
- Defining population segmentation logic.
- Conducting Exploratory Data Analysis.
- Interpreting segment-level patterns.
- Identifying major analytical risk indicators.
- Translating results into campaign-oriented insights.
- Developing strategic recommendations.
- Supporting competition presentation and analytical storytelling.

My contribution centered on connecting **data methodology, explainability, and practical decision context**.

---

# Team

| Member | Role | Primary Contribution |
|---|---|---|
| **Muhammad Wildan Nabila** | **Lead Data Scientist** | **Analytical design, risk scoring, segmentation, EDA, insight generation** |
| Ilman Nafian | Full Stack Developer | Web application development and deployment |
| Irawana Juwita | Data Analyst | Data preprocessing, exploratory analysis, validation |

Developed collaboratively for the **Data Analyst Competition — DevFest Surabaya 2025**, where the team reached the **Finalist** stage.

---

# Technology Ecosystem

<div align="center">

<img src="https://skillicons.dev/icons?i=python" height="48" alt="Python">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/numpy/013243" height="44" alt="NumPy">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/pandas/150458" height="44" alt="Pandas">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/jupyter/F37626" height="44" alt="Jupyter">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/github/ffffff" height="44" alt="GitHub">

<br><br>

`Python` · `NumPy` · `Pandas` · `Feature Engineering` · `EDA` · `Risk Scoring` · `Data Visualization`

</div>

---

# Skills Demonstrated

<table>
<tr>
<td width="33%" valign="top">

**Data Analytics**

- Exploratory Data Analysis
- Data Cleaning
- Data Validation
- Population Profiling

</td>
<td width="33%" valign="top">

**Analytical Modeling**

- Feature Engineering
- Composite Scoring
- Quantile Segmentation
- Explainable Analytics

</td>
<td width="33%" valign="top">

**Decision Intelligence**

- Insight Generation
- Population Segmentation
- Campaign Prioritization
- Analytical Storytelling

</td>
</tr>
</table>

---

# Analytical Limitations

This project should be interpreted as a **competition-based analytical framework**, not as a validated medical risk-assessment instrument.

Key limitations include:

**Non-clinical segmentation**  
The Low, Medium, and High Risk groups are analytical categories derived from the project's scoring framework and are not clinical diagnoses.

**Weight specification**  
Results depend on the weights assigned to individual indicators. Different weighting strategies may produce different scores.

**Quantile dependency**  
Quantile-based thresholds are relative to the analyzed dataset and may not generalize directly to another population.

**Observational associations**  
Patterns identified through EDA should not be interpreted as causal relationships.

**Limited variables**  
Health outcomes may be influenced by additional clinical, socioeconomic, environmental, and behavioral variables not represented in the analysis.

**External validation**  
The framework would require independent validation and appropriate domain expertise before any real-world health decision application.

---

# Future Development

Potential extensions include:

- Sensitivity analysis for indicator weights
- Comparison with clustering-based segmentation
- Validation using independent datasets
- Additional socioeconomic indicators
- Geographic population analysis
- Longitudinal risk analysis
- Statistical testing across segments
- Interactive risk-profile dashboards
- Fairness and subgroup analysis
- Expert-informed threshold validation

---

# Competition Achievement

<div align="center">

![DevFest](https://img.shields.io/badge/DEVFEST%20SURABAYA-DATA%20ANALYST%20COMPETITION-4285F4?style=for-the-badge&logo=google&logoColor=white)

<br>

# Finalist

**Data Analyst Competition · DevFest Surabaya 2025**

<br>

[![Presentation](https://img.shields.io/badge/CANVA-View%20Competition%20Presentation-00C4CC?style=for-the-badge&logo=canva&logoColor=white)](https://canva.link/7m8dcxcqrklozjo)

</div>

---

# Project Summary

| Dimension | Result |
|---|---|
| **Problem** | Lifestyle-related population risk segmentation |
| **Sample** | **1,545 individuals** |
| **Primary indicators** | BMI · Blood Pressure · Smoking · Physical Activity · Diabetes History |
| **Method** | Weighted Risk Scoring |
| **Segmentation** | Quantile-Based |
| **Output** | Low · Medium · High Risk |
| **High-Risk Segment** | **≈28%** |
| **Design Principle** | Explainability |
| **Decision Context** | Public Health Campaign Prioritization |
| **Achievement** | **Finalist — DevFest Surabaya 2025** |

---

# Project Resources

<div align="center">

[![Competition Presentation](https://img.shields.io/badge/CANVA-Competition%20Presentation-00C4CC?style=for-the-badge&logo=canva&logoColor=white)](https://canva.link/7m8dcxcqrklozjo)

</div>

---

# Author

**Muhammad Wildan Nabila**  
Bachelor of Informatics · Universitas Muhammadiyah Malang

<div align="left">

![Data Science](https://img.shields.io/badge/Data%20Science-2563EB?style=flat-square)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-7C3AED?style=flat-square)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-0F766E?style=flat-square)
![Artificial Intelligence](https://img.shields.io/badge/Artificial%20Intelligence-DC2626?style=flat-square)

</div>

---

<div align="center">

### Lifestyle Data → Explainable Segmentation → Campaign Intelligence

**Public Health Analytics · Risk Segmentation · Explainability · Decision Support**

</div>
