# Brain Tumor Detection using YOLOv11

## 🧠 Brain Tumor Detection using YOLOv11n

This project leverages `YOLOv11n.pt` (**You Only Look Once**) to detect and classify brain tumors in medical images. Using deep learning and computer vision techniques, the model identifies and localizes tumors to support early detection and diagnosis efforts.

The project was deployed as an interactive **Streamlit web app**, allowing users to upload brain scan images and get instant detection results.

---

### 🚀 How It Works

- **Model:** YOLOv11n (a lightweight and fast object detection model)
- **Dataset:** Brain tumor image dataset
- **Training:** Fine-tuned pre-trained weights (`YOLOv11n.pt`) on tumor data
- **Deployment:** Hosted via **Streamlit** for an interactive, browser-based UI

---

### 🔑 Key Features

- 🧠 **Real-time object detection** optimized for brain MRI images  
- 📍 **Localization & classification** of brain tumors  
- 🔁 **Preprocessing pipeline:** resizing, normalization, and augmentation  
- 📊 **Evaluation metrics:** Accuracy, IoU (Intersection over Union), Precision, Recall  
- 🎯 **Transfer learning:** Pre-trained weights fine-tuned for higher accuracy

---

### ⚙️ Prerequisites

- 🖥️ High-performance GPU (NVIDIA RTX 3080 or better recommended)  
- 💾 Minimum: 16 GB RAM, 500 GB storage  
- 🐍 Python 3.9+  
- 🔧 Required Libraries:
  - `PyTorch`
  - `Ultralytics` (for YOLO)
  - `Streamlit` (for deployment)

---

### 📈 Results

- ✅ Achieved **98% accuracy** after **20 epochs** of training  
- 🧪 Consistent performance across validation sets  
- 🌐 Deployed successfully as a **Streamlit app** for real-time usage

---

> _Note: This is a coursework-based project meant for academic exploration and learning. It's not intended for clinical deployment._

