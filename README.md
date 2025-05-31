# Brain Tumor Detection and Segmentation using YOLOv11 and SAM2
A Deep Learning-based project for Brain Tumor Detection and Segmentation. MRI images are processed to identify and segment tumor regions accurately. It leverages the power of YOLOv11 (You Only Look Once - Version 11) for real-time object detection and SAM2 (Segment Anything Model v2) for precise tumor boundary segmentation. A Flask web app enables real-time image upload, detection visualization, and confidence-based results to assist clinical diagnosis.

# 🔍 Features
YOLOv11 for fast and accurate detection of tumor regions.

SAM2 for high-resolution and adaptive tumor segmentation.

Flask Web App interface for easy MRI image upload and instant diagnostic output.

Visualized results with overlaid annotations and tumor regions.

Model performance metrics such as confidence score, precision, and class-wise evaluation.

# 💡 Objective
To assist radiologists and clinicians by providing an automated and efficient tool for early diagnosis and analysis of brain tumors using advanced deep learning techniques.

# 🛠️ Technologies Used
Python

YOLOv11 (PyTorch-based)

SAM2

OpenCV, NumPy

Flask for Web Interface

Matplotlib / Seaborn for performance visualization

# 📊 Dataset
MRI images of Brain tumors including:
Glioma

Meningioma

Pituitary

No Tumor

(Dataset obtained from publicly available sources - Roboflow)

# 📈 Performance
Precision-Confidence score visualization

Class-wise model evaluation

High Detection accuracy on common tumor types

# 🚀 Demo
The Web Application allows users to upload MRI images and instantly receive:

Tumor detection results with bounding boxes

Confidence scores and class predictions

Tumor segmentation maps
