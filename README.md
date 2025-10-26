#PPE Detection System Using Machine Learning 🦺
Overview

This project implements a Personal Protective Equipment (PPE) detection system using Machine Learning to improve safety in steel plant operations. It automatically detects whether workers are wearing the required safety gear such as helmets, gloves, masks, and safety vests, helping prevent accidents and ensure compliance with safety standards.

Features ✨

Real-time PPE detection using webcam or uploaded images.

Detects multiple PPE items simultaneously: helmets, gloves, safety vests, and masks.

Alerts when PPE is missing for workplace safety compliance.

Can be integrated with industrial surveillance systems.

Supports both image and video input.

Motivation 💡

Steel plants involve high-risk operations like welding, molten metal handling, and heavy machinery use. Ensuring all workers wear proper PPE reduces injuries and fatalities. Manual supervision is error-prone, so an automated PPE detection system improves safety and efficiency.

Technology Stack 🛠️

Python

OpenCV

TensorFlow / PyTorch

YOLO / SSD / Faster R-CNN (Object detection models)

NumPy & Pandas

Flask / Streamlit (Optional for web interface)

Dataset 📦

Contains images of workers with and without PPE.

Labeled with bounding boxes for each PPE item.

Public datasets or custom-collected steel plant images used.

Usage 🚀

Clone the repository:

git clone https://github.com/username/ppe-detection.git
cd ppe-detection


Install dependencies:

pip install -r requirements.txt


Run detection:

python detect_ppe.py --source path_to_image_or_video


Optional: Launch real-time webcam detection.

Results 📈

High accuracy in real-time PPE detection.

Detects multiple violations simultaneously.

Helps maintain safety compliance and reduces manual supervision.

Future Improvements 🔧

Integrate with IoT-enabled alert systems.

Detect additional safety equipment like goggles, ear protection, and safety shoes.

Deploy on edge devices for real-time monitoring.

License ⚖️

This project is licensed under the MIT License – see the LICENSE
 file for details.

Contact 📬

Developed by Rahul Achary

Email: your-email@example.com

LinkedIn: linkedin.com/in/rahul-achary

