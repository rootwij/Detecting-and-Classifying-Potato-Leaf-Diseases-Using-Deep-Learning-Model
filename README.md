# 🍃 Detecting and Classifying Potato Leaf Diseases Using Deep Learning

![Accuracy](https://img.shields.io/badge/Accuracy-98.52%25-brightgreen?style=flat-square)
![Model](https://img.shields.io/badge/Model-CNN-blue?style=flat-square)
![Framework](https://img.shields.io/badge/Framework-TensorFlow%2FKeras-red?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)

🌿 A deep learning solution to automatically identify Early Blight, Late Blight, and Healthy potato leaves.  
📈 Achieved high precision and F1-score, enabling smart agricultural diagnostics.

---

## 1️⃣ Project Overview

This research uses deep learning—specifically **Convolutional Neural Networks (CNNs)**—to classify potato leaf diseases from image data.

- 🚀 **Accuracy Achieved:** 98.52%
- 🧪 **Average F1 Score:** ~0.978
- 📊 **Use Case:** Agricultural disease management and real-time detection

---

## 2️⃣ Project Folder Structure

```
potato-leaf-disease-detection/
├── 📁 data/                 → Sample leaf images
├── 📁 notebooks/            → Model training/testing notebooks
├── 📁 src/                  → Training scripts and utility code
├── 📁 report/
│   ├── research_paper.pdf   → Research-style formatted paper
│   └── project_report.pdf   → University-format final report
├── 📄 requirements.txt      → Dependencies
├── 📄 LICENSE               → MIT License
└── 📄 README.md             → Project documentation
```

---

## 3️⃣ Models Implemented & Compared

| 🔢 No. | 🧠 Model Name     | ⚙️ Notes |
|------:|------------------|---------|
| 1.    | **DenseNet**      | High accuracy, strong gradient flow |
| 2.    | **VGG19**         | Deep structure, reliable for transfer learning |
| 3.    | **MobileNetV2**   | Optimized for mobile deployment |
| 4.    | **SqueezeNet**    | Lightweight, low-memory footprint |
| 5.    | **XceptionNet**   | Balanced accuracy and parameter efficiency |

---

## 4️⃣ Methodology Steps

```
1. 📸 Image Acquisition:
   - Collected high-resolution potato leaf images under varying conditions.
2. 🧼 Preprocessing:
   - Resized, normalized, and augmented images for generalization.
3. 🧠 Model Training:
   - Used CNNs to learn disease classification from labeled images.
4. 🧪 Validation:
   - Evaluated using accuracy, precision, recall, and F1-score.
```

---

## 5️⃣ Results Summary

```
✔ Accuracy:        98.52%
✔ Precision:       ~0.978
✔ Recall:          ~0.978
✔ F1 Score:        ~0.978
✔ Dataset:         2,152 images (Healthy, Early Blight, Late Blight)
```

---

## 6️⃣ Training & Usage

```bash
# Step 1: Clone this repo
git clone https://github.com/yourusername/potato-leaf-disease-detection.git
cd potato-leaf-disease-detection

# Step 2: Install Python dependencies
pip install -r requirements.txt

# Step 3: Run training script
python src/train.py
```

---

## 7️⃣ Visual Output

![Accuracy Graph VGG19](report/vgg19_accuracy_graph.png)  
*Validation Accuracy vs Loss Graph using VGG19*

---

## 8️⃣ Authors & Contact

👨‍💻 **Project Contributors:**  
- Abhishek Pandey  
- Upadhyay Rutvij Hiteshkumar  
- Aman Chaudhary  
- Rupam Tiwary  
- Venkata Sai Ganesh Gangidesi  

🎓 **Supervisor:**  
Mr. Vipin Kumar Chaudhary, Lovely Professional University



---

## 9️⃣ License

📝 Licensed under the [MIT License](LICENSE).  
Feel free to use and modify for non-commercial purposes with proper credit.

---

## 🔟 Acknowledgements

Thanks to **Lovely Professional University** for academic support and to our supervisor **Mr. Vipin Kumar Chaudhary** for technical guidance.

**🌾 Let's make farming smarter with deep learning!**
