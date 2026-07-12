# 📏 AI-Based Real-Time Object Measurement & Dimension Inspection Using Computer Vision

A real-time computer vision application that measures the dimensions (length and width) of physical objects using a standard webcam and OpenCV. The system uses an A4 sheet as a reference object to calibrate measurements, providing an accurate, low-cost, and contactless solution for object dimension inspection.

---

## 📌 Features

- 📷 Real-time webcam-based measurement
- 📄 Automatic A4 reference sheet detection
- 🔄 Perspective transformation for accurate measurements
- 📐 Measures object length and width in centimeters
- 🎯 High measurement accuracy with pixel calibration
- 💻 Low-cost solution using only a webcam
- ⚡ Fast and real-time processing
- 🏭 Suitable for quality inspection and industrial applications

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- imutils

---

## 📂 Project Structure

```
Object-Measurement/
│
├── images/                 # Sample images
├── output/                 # Output screenshots
├── utils.py                # Utility functions
├── main.py                 # Main application
├── requirements.txt
├── README.md
└── LICENSE
---

## ⚙️ Installation

### Install dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install opencv-python numpy imutils
```

---

## ▶️ Running the Project

```bash
python main.py
```

## 📋 How It Works

1. Start the webcam.
2. Place an **A4 sheet** under the camera.
3. Put the object on the sheet.
4. The system detects the A4 paper.
5. Perspective correction is applied.
6. Pixel-to-centimeter calibration is performed.
7. Object contours are detected.
8. Width and height are calculated.
9. Measurements are displayed in real time.

---

## 🔄 Workflow

```
Webcam
   │
   ▼
Image Capture
   │
   ▼
Image Preprocessing
(Gray → Blur → Canny)
   │
   ▼
Contour Detection
   │
   ▼
A4 Sheet Detection
   │
   ▼
Perspective Transformation
   │
   ▼
Pixel Calibration
   │
   ▼
Object Detection
   │
   ▼
Dimension Calculation
   │
   ▼
Display Measurements
```

---

## 📷 Sample Output

The application displays:

- Object Width
- Object Height
- Bounding Box
- Real-time Measurement

Example:

```
Width : 7.2 cm
Height: 14.8 cm
```

---

## 🎯 Applications

- Manufacturing Quality Inspection
- Packaging Industry
- Warehouse Automation
- Logistics
- Educational Demonstrations
- Laboratory Measurements
- Retail Product Dimension Verification

---

## 🚀 Future Enhancements

- YOLOv8-based automatic object recognition
- Measure multiple objects simultaneously
- ArUco marker-based calibration
- Area and volume estimation
- Save measurements to CSV/Excel
- Raspberry Pi deployment
- Cloud dashboard
- AI-powered defect detection

---

## 📚 References

- OpenCV Documentation
- NumPy Documentation

---

## 👥 Team

**Project:** AI-Based Real-Time Object Measurement & Dimension Inspection Using Computer Vision

Developed by:

- Shree Supriya S
- Anusha S
- Helena Vince J
---

## 📄 License

This project is developed for academic and educational purposes.
