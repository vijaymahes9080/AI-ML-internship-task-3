# AI/ML Internship Task 3: Traffic Sign Dataset & Recognition Studio

A complete machine learning dataset and interactive web studio designed for real-time traffic sign classification (STOP, LEFT TURN, and RIGHT TURN).

---

## 📌 Project Overview

This repository contains the dataset, web tools, trained model weights, and documentation for **AI/ML Internship Task 3**. The goal of this task is to collect, prepare, and validate a balanced multi-class computer vision dataset for traffic sign recognition.

### Supported Classes
| Sign | Class Label | Sample Count | Format |
| :---: | :--- | :---: | :--- |
| 🛑 | **STOP** | 35 images | JPG (`stop_01.jpg` – `stop_35.jpg`) |
| ⬅️ | **LEFT TURN** | 35 images | JPG (`left_turn_01.jpg` – `left_turn_35.jpg`) |
| ➡️ | **RIGHT TURN** | 35 images | JPG (`right_turn_01.jpg` – `right_turn_35.jpg`) |

**Total Dataset Size:** 105 curated images with diverse angles, distances, perspectives, and lighting conditions.

---

## 🚀 Key Features

1. **Traffic Sign Dataset Studio (`vj_traffic_studio.html`)**:
   - Interactive gallery to inspect and review all dataset samples.
   - Built-in webcam capture tool with burst mode (5x) and variation checklist (straight-on, tilted 45°, close-up, distance, rotation).
   - High-contrast digital sign display for testing models against screen inputs.
   - Printable sheet mode for cutting out physical signs for real-world webcam tests.

2. **Trained Keras Model (`converted_keras.zip`)**:
   - Pre-trained weights and Teachable Machine / Keras model export ready for inference or transfer learning.

3. **Detailed Report (`Task 3 VJ.docx`)**:
   - Complete project documentation covering methodology, data collection, preprocessing, and validation results.

---

## 📁 Repository Structure

```plaintext
├── left_turn/                # 35 images for Left Turn signs
│   ├── left_turn_01.jpg ... left_turn_35.jpg
├── right_turn/               # 35 images for Right Turn signs
│   ├── right_turn_01.jpg ... right_turn_35.jpg
├── stop/                     # 35 images for Stop signs
│   ├── stop_01.jpg ... stop_35.jpg
├── converted_keras.zip       # Exported Keras / Teachable Machine model
├── vj_traffic_studio.html    # Interactive web studio for dataset & testing
├── Task 3 VJ.docx            # Task report and documentation
├── composer.json             # Project metadata & author configuration
├── .gitignore                # Git ignore configuration
├── LICENSE                   # MIT License
└── README.md                 # Project documentation
```

---

## 🛠️ How to Use

### 1. Launching the Studio Web App
Simply open `vj_traffic_studio.html` in any modern web browser:
```bash
# On Windows PowerShell
Start-Process .\vj_traffic_studio.html
```
- Navigate between the **Dataset Gallery**, **Webcam Studio**, **Digital Display**, and **Printable Signs** tabs.

### 2. Using the Dataset
The image folders (`stop/`, `left_turn/`, `right_turn/`) can be directly loaded into PyTorch `ImageFolder`, TensorFlow `image_dataset_from_directory`, or Teachable Machine.

---

## 👤 Author & Developer Information

- **Developer:** Vijay Mahes
- **Email:** [Vijaypradhap2004@gmail.com](mailto:Vijaypradhap2004@gmail.com)
- **GitHub:** [@vijaymahes9080](https://github.com/vijaymahes9080)
- **Repository:** [AI-ML-internship-task-3](https://github.com/vijaymahes9080/AI-ML-internship-task-3)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.
