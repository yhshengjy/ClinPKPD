# ClinPKPD: An Interactive PK/PD Learning Environment for Pharmacy Education

**ClinPKPD** is a Google Colab–based modular learning tool designed to support the teaching and learning of pharmacokinetic/pharmacodynamic (PK/PD) concepts in pharmacy education.

This repository contains **seven interactive Jupyter notebooks** that allow students to modify pharmacokinetic parameters, visualize changes in drug concentration–time profiles, and explore how PK/PD principles relate to clinical dosing decisions.

The notebooks were developed as part of an educational study evaluating an interactive PK/PD learning environment for undergraduate pharmacy students.

---

## Overview

Traditional PK/PD instruction often requires students to move between mathematical equations, static figures, and clinical examples. ClinPKPD was designed to provide a more interactive learning environment in which students can directly manipulate model parameters and observe their effects on pharmacokinetic profiles and dosing outcomes.

The notebooks are intended to complement, rather than replace, conventional instruction.

Across the seven modules, students can explore topics including:

* pharmacokinetic parameters and concentration–time profiles;
* clearance and volume of distribution;
* elimination half-life;
* multiple dosing and drug accumulation;
* steady-state pharmacokinetics;
* the effects of renal function on drug clearance and dose adjustment;
* antimicrobial PK/PD concepts and their relationships with clinical dosing decisions.

---


## Interactive Modules

ClinPKPD consists of seven instructional modules covering fundamental pharmacokinetic concepts, renal function–based dose adjustment, and antimicrobial PK/PD applications. Each module is available in both English and Chinese.

| Module | Topic                                           | Learning Focus                                                                                                                                                                                                                 | Notebooks                                                                                                                                                                                                                                          |
| ------ | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1**  | **Basic One-Compartment PK/PD Simulation**      | Explore dose–concentration–effect relationships, compare intravenous and oral administration, and examine the effects of clearance, volume of distribution, bioavailability, and absorption rate on drug exposure and response | [English](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook1_one_compartment_pkpd_english.ipynb) · [中文](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook1_一室模型基础.ipynb)                 |
| **2**  | **Multiple Dosing and Steady State**            | Understand drug accumulation, steady-state behavior, peak and trough concentrations, and the effects of dose, dosing interval, and elimination half-life during repeated dosing                                                | [English](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook2_multiple_dosing_steady_state_english.ipynb) · [中文](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook2_多剂量给药与稳态浓度.ipynb)     |
| **3**  | **Renal Function and Dose Adjustment**          | Estimate renal function, examine the effects of renal impairment on clearance, exposure, and half-life, and compare dose reduction with dosing-interval extension strategies                                                   | [English](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook3_renal_function_dose_adjustment_english.ipynb) · [中文](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook3_肾功能变化与剂量调整.ipynb)   |
| **4**  | **Two-Compartment Model and Drug Distribution** | Distinguish distribution and elimination phases, understand central and peripheral compartments, and explore how volume of distribution, clearance, and intercompartmental clearance influence concentration–time profiles     | [English](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook4_Two_Compartment_Model_english.ipynb) · [中文](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook4_二室模型与药物分布.ipynb)             |
| **5**  | **Vancomycin PK/PD Simulation**                 | Interpret AUC24/MIC, examine vancomycin exposure under different dosing regimens, and explore the effects of dose, dosing interval, infusion duration, clearance, volume of distribution, and renal function                   | [English](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook5_vancomycin_PKPD_simulation_english.ipynb) · [中文](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook5_万古霉素_PKPD模拟.ipynb)      |
| **6**  | **β-Lactam PK/PD Simulation**                   | Understand %fT > MIC, compare intermittent, extended, and continuous infusion strategies, and examine how clearance, protein binding, MIC, and dosing regimen affect PK/PD target attainment                                   | [English](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook6_beta_lactam_PKPD_simulation_english.ipynb) · [中文](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook6_β内酰胺类_PKPD模拟.ipynb)    |
| **7**  | **Aminoglycoside PK/PD Simulation**             | Understand concentration-dependent antibacterial activity, interpret Cmax/MIC, compare extended-interval and divided dosing, and examine the effects of renal function on accumulation and trough concentrations               | [English](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook7_aminoglycoside_PKPD_simulation_english.ipynb) · [中文](https://colab.research.google.com/github/yhshengjy/ClinPKPD/blob/main/Notebook7_氨基糖苷类_PKPD模拟.ipynb) |

### How to Use

The notebooks can be run directly in **Google Colab** without installing Python locally.

1. Select the English or Chinese version of a module from the table above.
2. Open the notebook in Google Colab.
3. Run the cells sequentially.
4. Adjust the interactive parameters using the sliders or dropdown menus.
5. Observe how parameter changes affect concentration–time profiles and relevant PK/PD outcomes.

Users who wish to modify or save a notebook can create a personal copy in their own Google Drive.

> **Educational use only:** ClinPKPD is designed for teaching and learning. The simulations and example dosing regimens are not intended for individual patient care or clinical prescribing decisions.



## Intended Users

ClinPKPD was developed primarily for:

* undergraduate pharmacy students;
* students learning introductory or intermediate pharmacokinetics;
* instructors teaching pharmacokinetics, clinical pharmacokinetics, or PK/PD;
* educators interested in incorporating interactive computational tools into pharmacy education.

Basic prior knowledge of pharmacokinetic concepts is recommended.

---

## Educational Objectives

ClinPKPD is intended to help learners:

1. visualize relationships among fundamental pharmacokinetic parameters;
2. understand how changes in clearance, volume of distribution, and dosing regimens affect drug concentration–time profiles;
3. explore drug accumulation and steady-state behavior during repeated dosing;
4. understand the influence of renal function on drug exposure and dose adjustment;
5. connect antimicrobial PK/PD concepts with clinically relevant dosing decisions;
6. develop a more intuitive understanding of relationships that may be difficult to appreciate from equations or static figures alone.

---


## Use in Teaching

The notebooks may be incorporated into:

* classroom demonstrations;
* computer-based workshops;
* small-group learning activities;
* self-directed learning;
* PK/PD review sessions.

Instructors can select individual modules according to the learning objectives of a course or use all seven modules as a structured workshop.

---

## Educational and Clinical Disclaimer

ClinPKPD was developed **for educational purposes only**.

The simulations and dosing examples provided in these notebooks are intended to illustrate pharmacokinetic and pharmacodynamic principles. They should **not** be used for individual patient care, clinical decision-making, or therapeutic drug dosing without appropriate clinical evaluation and validated clinical tools.

---



## Citation

If you use ClinPKPD in teaching, research, or educational material, please cite this repository and the associated publication once available.

A formal citation will be provided here after publication.

---





