# 🩺 Skin Lesion Classification | EfficientNetV2S + ECA + SE + Focal Loss

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)]()
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.9%2B-orange)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()
[![Dataset](https://img.shields.io/badge/Dataset-HAM10000-red)](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000)

> A deep learning model for skin lesion classification using EfficientNetV2S with ECA and SE attention mechanisms, optimized with Focal Loss for imbalanced datasets.

---

## 📌 Overview
This project trains a **skin lesion classification model** that can classify images into:
- **BCC** — Basal Cell Carcinoma  
- **MEL** — Melanoma  
- **NV** — Melanocytic Nevi  

The model:
- Uses **EfficientNetV2S** as the main backbone
- Integrates **ECA** (Efficient Channel Attention) and **SE** (Squeeze-and-Excitation) modules
- Applies **Focal Loss** to handle class imbalance
- Trained on the **HAM10000** dataset

---

## 🚀 How to Run

### Option 1 — Google Colab
1. Open the notebook in Google Colab  
2. Upload the `Skin_Cancer_Model_EfficientNetV2S.ipynb` file  
3. Run all cells sequentially  

### Option 2 — Local Jupyter
```bash
# 1️⃣ Clone the repository
git clone https://github.com/username/Skin_Cancer_Model_EfficientNetV2S.git
cd Skin_Cancer_Model_EfficientNetV2S

# 2️⃣ Install dependencies
pip install -r requirements.txt

# 3️⃣ Launch Jupyter
jupyter notebook Skin_Cancer_Model_EfficientNetV2S.ipynb
````

---

## 📊 Results

| Phase      | Accuracy |
| ---------- | -------- |
| Training   | 97%      |
| Validation | 93–97%   |

---

## 📜 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

## 🙌 Contribution

Pull requests and issues are welcome.

