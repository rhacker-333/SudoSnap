# 🧠 SudoSnap 🧩
🔍 *Scan. Solve. Overlay. All in the blink of an eye.*

---

## 📸 Project Overview

This project combines the magic of **OpenCV**, the power of **Convolutional Neural Networks (CNN)**, and the elegance of **Python** to scan a real-world Sudoku puzzle via webcam, solve it using backtracking, and overlay the solution *live* on the original board — all in a flash ⚡

---

## ✨ Features

- 🔎 **Real-Time Frame Capture** via webcam  
- 🧹 **Advanced Image Preprocessing**: Grayscale, thresholding, noise removal, warping  
- 🧠 **Digit Recognition** using a pre-trained CNN  
- 🧮 **Sudoku Solving** via optimized backtracking with constraint pruning  
- 📐 **Precise Overlay** of solution digits on the original board using coordinate mapping  
- 💡 **Bitwise Rendering Techniques** for intelligent overlay logic  
- 🚀 **Virtually Instant Execution** with optimized performance

---

## 🛠️ Tech Stack & Tools

| Area                        | Tools / Technologies      |
|-----------------------------|---------------------------|
| 👁️ Computer Vision          | OpenCV                    |
| 🤖 Machine Learning         | CNN (Keras/TensorFlow)    |
| 🧪 Image Preprocessing      | NumPy, OpenCV filters     |
| 📊 Data Extraction and Restructuring         | NumPy Arrays              |
| 🧩 Sudoku Solving           | Backtracking Algorithm    |
| 🧠 AI Enhancement Logic     | Constraint Propagation    |
| 🎨 Overlay & UX             | Bitwise Operations (AND, OR) |

---

## 🔄 Workflow Summary

```mermaid
graph TD
A[📷 Webcam Frame Capture] --> B[🖼️ Image Preprocessing]
B --> C[📐 Board Detection & Warping]
C --> D[🔲 Grid Segmentation]
D --> E[🔢 Digit Extraction with CNN]
E --> F[🧮 Backtracking Solver]
F --> G[🌈 Coordinate Mapping]
G --> H[📍 Overlay Solution on Frame]
H --> I[🎯 Display Solved Puzzle in Real-Time]