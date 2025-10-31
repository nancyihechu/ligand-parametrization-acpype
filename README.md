# 🧪 Ligand Parameterization using ACPYPE and RDKit

This repository provides a simple Python-based workflow for generating **GROMACS topology files** (`.itp`) for small-molecule ligands using **ACPYPE** and **GAFF2** parameters. The workflow integrates **RDKit** for molecule handling and **ACPYPE** for topology generation.

---

## ⚙️ Requirements

- Python 3.x  
- RDKit  
- ACPYPE  
- AmberTools (for GAFF2)  
- GROMACS (optional, for downstream use)

Install dependencies:
```bash
conda install -c conda-forge rdkit ambertools acpype
