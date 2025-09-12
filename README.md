
# MIT 805 – Assignment Part 1: Breast Cancer Imaging (BACH / ICIAR 2018)

[![Made with Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)](https://jupyter.org/)
[![License: choose](https://img.shields.io/badge/License-choose-green.svg)](#license)

Exploratory analysis for **Part 1** of MIT 805. The goal is to **collect and describe** a large imaging dataset and analyze it using the **7 Vs of Big Data** (plus value), producing figures and a short report.

**Notebook:** [`breastCancerAnalysis.ipynb`](breastCancerAnalysis.ipynb)  
**Report (LaTeX/PDF):** see `/report/`

---

## TL;DR (Results)

- **Total size:** **10.53 GB**  
- **Images:** **660**  
- **Formats:** 600 × `.tif`, 60 × `.png` (thumbnails)  
- **Velocity sample:** decoded 300 images (≈4895.8 MB) in 42.89 s → **~114.16 MB/s** 
- **Local snapshot day (file mtimes):** **2025-08-19**  
- **Diagnostic-type counts (from path tokens):**  
  | Diagnostic type         | Count |
  |-------------------------|------:|
  | Malignant (unspecified) |   260 |
  | Normal/Benign           |   200 |
  | In-situ (DCIS)          |   100 |
  | Invasive carcinoma      |   100 |

**Per-root breakdown:**

| Root                                                       | Images | Size (GB) |
|------------------------------------------------------------|-------:|---------:|
| `/kaggle/input/bach-breast-cancer-histology-images`        |    550 |     8.75 |
| `…/thumbnails`                                             |    110 |     1.79 |
| **Combined**                                               | **660**| **10.53**|

---

## Repository Structure

