# CGAM: Ceramic Grain Analysis Model


![dbbbce5020_visualization](https://github.com/user-attachments/assets/0ddd9aaa-2852-4a6e-ad61-5004b6295a08)
![dbbbce5020_comparison](https://github.com/user-attachments/assets/2a4d962c-628c-4ebf-bee4-8908dead82ca)

> **CGAM** (Ceramic Grain Analysis Model) for instance segmentation and characterization analysis in electron microscopy images using the EMPS dataset.

## 📖 Overview

This repository contains the implementation of CGAM (Ceramic Grain Analysis Model) for comprehensive ceramic grain analysis in electron microscopy images. The project demonstrates a complete workflow from data preprocessing, instance segmentation, model training and evaluation, to characterization computation and quantitative analysis using deep learning techniques specifically designed for ceramic grain analysis.

## 📊 Dataset

### EMPS Dataset
We use the **Electron Microscopy Particle Segmentation (EMPS) Dataset** for training and evaluation. The EMPS dataset provides high-quality annotations for particle segmentation in electron microscopy images, making it an ideal benchmark for developing and testing instance segmentation algorithms.

**Dataset Features:**
- High-resolution electron microscopy images
- Pixel-level instance annotations
- Diverse particle shapes and sizes
- Complex overlapping scenarios

## 📁 Project Structure

```
├── CGAM.ipynb              # Main notebook: Complete workflow
```

## 🚀 Quick Start

### Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/zzzxyb/CGAM.git
   cd CGAM
   ```

2. **Run the complete workflow:**
   ```bash
   jupyter notebook CGAM.ipynb
   ```

## 🛠️ Requirements

- Python 3.9+
- TensorFlow 2.12.0+
- CUDA-compatible GPU (recommended)
- 8GB+ RAM

## 📚 Citation

### EMPS Dataset Citation

```bibtex
@article{yildirim2021bayesian,
  title={Bayesian Particle Instance Segmentation for Electron Microscopy Image Quantification},
  author={Yildirim, B. and Cole, J. M.},
  journal={Journal of Chemical Information and Modeling},
  year={2021},
  doi={10.1021/acs.jcim.0c01455},
  url={https://doi.org/10.1021/acs.jcim.0c01455}
}
```

## 🙏 Acknowledgments

- [EMPS Dataset](https://doi.org/10.1021/acs.jcim.0c01455) creators for providing high-quality annotations
- TensorFlow team for the excellent deep learning framework
- Scikit-image community for robust image processing tools

---

⭐ **Star this repository if you find it helpful!** ⭐
