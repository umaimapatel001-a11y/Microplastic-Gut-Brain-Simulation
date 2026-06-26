# Multi-Omic Gut-Brain Axis Simulation: Modeling Microplastic-Induced Dysbiosis

An advanced computational framework simulating a 500-subject clinical cohort to analyze the systemic impacts of microplastic body burden on gut microbial ecology, systemic dysbiosis, and fecal metabolomics pathways.

## 🧬 Project Overview
This repository contains a localized data science pipeline designed to model how quantified microplastic exposure loads correlate with computed gut dysbiosis scores (Inflammatory / SCFA ratios) and downstream metabolic collapses. The model evaluates 10 key multi-omic target variables across neurotransmitter modulation, inflammatory pathways, and gut-brain axis signaling.

## 📊 Key Analytical Features
* **Cohort Generation ($N=500$):** Synthetic high-throughput clinical data matrix capturing microplastic exposure dynamics.
* **Metabolic Mapping:** Automated extraction and indexing of structural identifiers for microplastic-impacted networks.
* **Advanced Visualizations:** * High-resolution Pearson Correlation Matrices detailing co-abundance structures.
  * Kernel Density Estimation (KDE) population cluster maps identifying systemic metabolic collapses under heavy exposure loads.

## 🛠️ Tech Stack & Dependencies
* **Environment:** Python 3.10+ via localized virtual environments (`toxin-env`)
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `networkx`

## 🚀 How to Run Locally
1. Clone this repository to your machine.
2. Ensure your virtual environment is active and run the package installer cell:
   ```python
   %pip install pandas requests numpy matplotlib seaborn networkx scipy
   