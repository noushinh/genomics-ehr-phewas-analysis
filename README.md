# Multi-Omic Analysis: Genomics, EHR, and PheWAS

This repository contains Jupyter Notebooks for conducting large-scale genetic association studies and integrating Electronic Health Record (EHR) data. The project covers the end-to-end pipeline from raw genomic data processing to Phenome-Wide Association Studies (PheWAS).

## 📂 Repository Structure

* **`Noushin_genomicsdata.ipynb`**: Core notebook for genomic data processing. Includes quality control (QC), filtering, and preparation of genetic variants for downstream analysis.
* **`gwas_practice.ipynb`**: Implementation of Genome-Wide Association Study (GWAS) workflows. Focuses on testing associations between genetic variants and specific traits, including the generation of Manhattan and QQ plots.
* **`PHEWAS_practice.ipynb`**: Phenome-Wide Association Study (PheWAS) pipeline. This notebook integrates EHR-derived phenotypes (Phecodes) to scan for associations across a broad spectrum of clinical traits for specific genetic markers.

## 🛠 Features

- **Genomic Quality Control:** Scripts for filtering by minor allele frequency (MAF), Hardy-Weinberg Equilibrium (HWE), and call rates.
- **EHR Phenotyping:** Methods for mapping ICD-9/10 codes to Phecodes for clinical analysis.
- **Data Visualization:** High-quality plotting for statistical genetic results (Manhattan plots, distribution charts).
- **Scalable Workflows:** Designed for use with common bioinformatics tools and Python libraries (Pandas, Scipy, Matplotlib, Seaborn).
