# Age and Gender Detection using OpenCV Deep Learning

A computer vision project that detects human faces in an image and predicts approximate age range and gender using pretrained Deep Learning models with OpenCV DNN.

This project uses:
- OpenCV DNN Face Detector
- Pretrained Caffe Models
- Age Classification CNN
- Gender Classification CNN

The system processes an image, detects faces, predicts age and gender, and displays annotated results.

---

# Features

- Face Detection using OpenCV DNN
- Age Range Prediction
- Gender Prediction
- Image Annotation with Predictions
- Works in Google Colab and Local Python Environment
- Lightweight and beginner friendly implementation

---

# Project Workflow

1 Load Image  
2 Detect Face using OpenCV DNN  
3 Extract Face Region  
4 Convert Face to Blob Format  
5 Predict Gender  
6 Predict Age Range  
7 Display Final Annotated Image  

---

# Tech Stack

- Python
- OpenCV
- NumPy
- Deep Learning CNN Models
- Google Colab

```

---

# Dataset and Models

This project uses pretrained models trained on large scale face datasets.

Models Used:
- OpenCV Face Detector
- Age Detection CNN
- Gender Detection CNN

Age Categories:
- 0 to 2
- 4 to 6
- 8 to 12
- 15 to 20
- 25 to 32
- 38 to 43
- 48 to 53
- 60 to 100

Gender Categories:
- Male
- Female

Important:
The model predicts approximate appearance based categories and not exact biological age or identity.

---

# Installation

Clone Repository

```bash
git clone https://github.com/yourusername/Age-Gender-Detection.git
```

Move to Project Directory

```bash
cd Age-Gender-Detection
```

Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Requirements

```text
opencv-python
numpy
```

---

# Run the Project

Using Python Script

```bash
python src/main.py
```

Using Google Colab:
- Upload project files
- Upload image
- Run notebook cells

---

# Sample Code

```python
faceNet=cv2.dnn.readNet(faceModel,faceProto)
ageNet=cv2.dnn.readNet(ageModel,ageProto)
genderNet=cv2.dnn.readNet(genderModel,genderProto)
```

---

# Output

The system displays:
- Face Bounding Box
- Predicted Gender
- Predicted Age Range

Example:

```text
Gender: Male
Age: 25-32 years
```

---

# Example Result

Input:
- Human face image

Output:
- Annotated image with predictions

Example:

```text
Male, 25-32
```

---

# Limitations

- Predicts age ranges not exact age
- Gender classification is binary
- Accuracy depends on:
  - lighting
  - image quality
  - pose
  - facial visibility
- Older pretrained models may produce biased predictions
- Not suitable for real world biometric verification systems

---

# Future Improvements

- Real time webcam detection
- DeepFace integration
- Emotion detection
- Face recognition
- Streamlit web application
- Mobile deployment
- YOLO face detection
- Better pretrained transformer models

---

# Applications

- Computer Vision Learning
- AI Mini Projects
- Human Computer Interaction
- Smart Camera Systems
- Educational Deep Learning Projects

---

# Learning Outcomes

This project helps understand:
- OpenCV DNN module
- Face detection pipelines
- CNN inference
- Image preprocessing
- Blob creation
- Deep learning model deployment

---

# Conclusion

This project demonstrates a complete Deep Learning based age and gender prediction pipeline using OpenCV and pretrained CNN models. It is suitable for beginners learning computer vision and image based AI systems.

The project focuses on educational understanding of:
- face detection
- image preprocessing
- CNN inference
- real time AI concepts

rather than production grade biometric analysis.

---

# License

This project is licensed under the MIT License.
