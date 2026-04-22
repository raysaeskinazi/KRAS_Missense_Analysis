# KRAS_Missense_Analysis
# Pan-Cancer KRAS Missense Mutation Analysis: From Clinical Data to 3D Structure

![Data Analysis](https://img.shields.io/badge/Data_Analysis-Pandas-blue)
![Structural Biology](https://img.shields.io/badge/Structural_Biology-ChimeraX-green)
![Oncology](https://img.shields.io/badge/Clinical_Oncology-Translational-orange)

## 📌 Project Overview
The *KRAS* oncogene is one of the most frequently mutated genes in human cancers. This project bridges data science and structural biology by filtering a large-scale clinical dataset and mapping the identified missense mutations onto the 3D protein structure to understand their functional impact.

## 🔬 Data Processing Pipeline (Dry-Lab)
A clinical dataset comprising 247 cancer patients was processed and filtered using **Python (Pandas)**.
* **Data Cleaning:** Handled missing values and standardized patient records.
* **Variant Filtering:** Isolated clinically actionable missense mutations within the KRAS gene.
* **Output:** A refined dataset highlighting the most recurrent and structurally significant mutations (e.g., Codon 12 alterations).

## 🧬 Structural Consequence (Wet-Lab Perspective)
Using **UCSF ChimeraX**, the critical mutations identified in the dataset were mapped onto the 3D crystal structure of the KRAS protein. 

Mutations at critical residues (such as G12 or Q61) disrupt the intrinsic GTPase activity of KRAS, locking the protein in a constitutively active (GTP-bound) state. This structural visualization demonstrates how a single amino acid substitution directly alters the binding pocket, driving uncontrolled cellular proliferation.

### 3D Structural Visualization
> **[GÖRSEL BURAYA GELECEK: İleride ChimeraX'ten alacağın bir KRAS fotoğrafını buraya ekleyebilirsin]**
*Visualization of the KRAS functional domains and the highlighted missense mutation hotspots derived from the clinical dataset.*

## 📂 Repository Structure
* `kras_missense.py`: The Python script utilizing Pandas for clinical data filtering and mutation frequency analysis.
* `README.md`: Project documentation and structural interpretation.

## 🎯 Conclusion
This project highlights a translational approach: effectively handling and filtering raw clinical patient data, and critically evaluating the molecular consequences of those findings using advanced 3D structural modeling.
