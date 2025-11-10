# 🦷 CavAI: AI-Assisted Cavity Detection and Teledentistry

> **Empowering smarter oral healthcare through AI-driven cavity detection and teledentistry integration**


---

## 📖 Overview

**CavAI** is an **AI-powered dental diagnosis system** that leverages the **YOLOv8 deep learning model** to detect and highlight cavity-affected regions in **intraoral and X-ray images**.

It enables **teledentistry integration**, allowing remote preliminary screening and seamless connection between patients and dental professionals for quick consultations.

By promoting early detection and accessible diagnosis, CavAI supports **SDG 3: Good Health and Well-being** and paves the way for **AI-assisted dental screening** in real-world clinical and telehealth environments.

---

## 🚀 Features

- 🧠 **Deep Learning Model:** YOLOv8 object detection fine-tuned for cavity localization  
- 📸 **Smartphone & X-ray Support:** Detect cavities from real intraoral images  
- 🌐 **Flask Web Interface:** Upload and visualize predictions instantly  
- 🧩 **Explainable AI (optional):** Grad-CAM for interpretability  
- 💬 **Teledentistry Ready:** Enables patient–dentist remote collaboration  
- ✅ **96% Accuracy:** Robust detection performance on real-world datasets  

---

## 🧠 Model Details

| Property | Description |
|-----------|-------------|
| **Model** | YOLOv8 (Ultralytics) |
| **Base Weights** | Pretrained on COCO |
| **Training Epochs** | 50 |
| **Batch Size** | 16 |
| **Optimizer** | AdamW |
| **Augmentations** | Mosaic, Flip, HSV, Scaling |
| **Environment** | Google Colab (T4 GPU) |
| **Output File** | `best.pt` |

---

## 🧪 Dataset

**Public Datasets Used:**
- [Cavity Computer Vision Dataset (Roboflow)]
- [2Classes Real with Augmentation Dataset (Roboflow)]

**Clinical Dataset (Ongoing Collection):**
- Real intraoral photographs from dental clinics  
- Diverse cases across age groups and cavity severity  
- Expert-labeled bounding boxes  

**Purpose:**  
Combining public and clinical datasets enhances **generalization** and **real-world robustness**.

---

## 📊 Performance


---

## 🧩 Impact and SDG Alignment

SDG 3: Good Health and Well-being – promotes early oral disease detection

Accessibility: Provides screening for remote and underserved areas

Scalability: Easily adaptable for mobile or telehealth environments
---
##🧩 Future Enhancements

📱 Mobile app integration for remote uploads

🔍 Grad-CAM heatmaps for explainability

🧮 Multi-class pathology detection (plaque, fracture, etc.)

🧾 Clinical validation with dentist feedback
