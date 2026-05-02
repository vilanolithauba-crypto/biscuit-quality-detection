# 🍪 Biscuit Quality Detection using OpenCV

A computer vision project that detects and classifies biscuits as **Intact** or **Broken** using image processing techniques.

---

## 📌 Overview

This system analyzes images of biscuits and identifies whether each biscuit is:

* ✅ Intact (no damage)
* ❌ Broken (missing parts or cracks)

It works with:

* Square biscuits
* Circular biscuits
* Rotated biscuits

---

## 🛠️ Technologies Used

* Python 3
* OpenCV
* NumPy

---

## 📂 Project Structure

```
biscuit-quality-detection/
│
├── input_images/        # Input images
├── output_images/       # Output results
├── main.py              # Detection code
└── README.md
```

---

## ⚙️ Installation

Install required libraries:

```
pip install opencv-python numpy
```

---

## ▶️ How to Run

1. Place your images inside:

```
input_images/
```

2. Run the program:

```
python main.py
```

3. Output images will be saved in:

```
output_images/
```

---

## 🧠 Methodology

The system uses classical computer vision techniques:

### 1. Color Segmentation

* Converts image to HSV
* Extracts biscuit regions

### 2. Contour Detection

* Identifies individual biscuits

### 3. Feature Extraction

* Area
* Perimeter
* Circularity
* Aspect Ratio
* Convex Hull

### 4. Classification

* Intact biscuits → smooth and complete
* Broken biscuits → missing parts / irregular shape

---

## 📸 Output

* 🟢 Green → Intact Biscuit
* 🔴 Red → Broken Biscuit

---

## 🚀 Future Improvements

* Deep learning (YOLO model)
* Real-time detection using webcam
* Improved accuracy under different lighting

---

## ⚠️ Limitations

* Sensitive to lighting conditions
* May misclassify in extreme cases
* Classical CV has accuracy limits

---

## 👨‍💻 Author

**Your Name**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

