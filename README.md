# 🖼️ **Image Classification by Machine Learning Using Python (AICTE Internship Project)**

This project is a **Streamlit application** designed to perform image classification using two advanced machine learning models: **MobileNetV2** and a custom **CIFAR-10 model**. The app allows users to upload images and get predictions along with confidence scores. It offers a seamless user experience with an intuitive navigation bar for easy switching between models, making it ideal for educational purposes and practical image classification tasks.

---

## **✨ Key Features**

### 1. **Dual Model Support**

- **📱 MobileNetV2 (ImageNet)**:
  - Recognizes 1,000 classes from the ImageNet dataset.
  - Includes diverse objects such as animals, vehicles, everyday items, and more.
  - Optimized for mobile and web applications due to its lightweight architecture.

- **🖼️ Custom CIFAR-10 Model**:
  - Classifies images into 10 categories:
    - ✈️ Airplane, 🚗 Automobile, 🐦 Bird, 🐱 Cat, 🦌 Deer, 🐶 Dog, 🐸 Frog, 🐴 Horse, 🚢 Ship, and 🚚 Truck.
  - Designed for small-scale image classification tasks like object detection in everyday images.

### 2. **User-Friendly Interface**

- **🔀 Seamless Navigation**:
  - Effortlessly switch between the MobileNetV2 and CIFAR-10 models using the sidebar menu.

- **⏱️ Instant Results**:
  - Upload JPG or PNG images to receive immediate classification results.
  - Displays predictions along with confidence scores for a detailed understanding.

### 3. **Educational & Practical Benefits**

- **📘 Learning Opportunity**:
  - Explore deep learning models and their architecture.
  - Compare performance across different models for educational insights.

- **💡 Practical Use**:
  - Use the app to quickly classify images in real-time with state-of-the-art models.

---

## **🚀 Getting Started**

### **🛠️ Prerequisites**
- Python 3.7 or higher.
- A modern web browser to access the app.

### **⚙️ Installation Guide**

Follow these steps to set up and run the application locally:

## **📥 Clone the Repository**:
   ```bash
   git clone https://github.com/mohit8383/Image-Classification-By-Machine-Learning-Using-Python-AICTE-Internship-Project.git
   cd Image-Classification-By-Machine-Learning-Using-Python-AICTE-Internship-Project
### 🔧 Set Up Virtual Environment

#### For Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

#### For macOS/Linux:
```bash
python -m venv venv
source venv/bin/activate
```

### 📦 Install Dependencies
```bash
pip install -r requirements.txt
```

### ▶️ Run the Application
```bash
streamlit run app.py
```

### 🌐 Open the App
The app will open automatically in your default browser. If not, visit [http://localhost:8501](http://localhost:8501).

---

## 📖 Usage Instructions

### 🔘 Choose the Model
- Select either **MobileNetV2** or **CIFAR-10** model from the navigation bar.

### 📤 Upload an Image
- Choose an image file (**JPG/PNG** format) using the upload button.

### 📊 View Classification Results
- See the predicted class and the confidence score of the prediction.

### 🔄 Switch Models
- Easily toggle between the two models to compare predictions on the same image.

---

## 📂 File Structure
```bash
Image-Classification-By-Machine-Learning-Using-Python-AICTE-Internship-Project/
├── app.py               # Streamlit app for running the classification models.
├── models/              # Directory containing model files and utilities.
├── requirements.txt     # List of dependencies required to run the app.
├── README.md            # Project documentation.
└── assets/              # Resources like images, icons, etc.
```

---

## 🔧 Technologies Used
- **Streamlit**: For creating an interactive and dynamic web app.
- **TensorFlow/Keras**: For building and loading machine learning models.
- **Python**: Core programming language used for implementation.

---

## 🤝 Support This Project
⭐ **Star the Repository**: If you find this project useful, please star it on GitHub.

🔗 **Share with Others**: Spread the word among students and developers.

👨‍💻 **Follow Me on GitHub**: Stay updated with my latest projects: [mohit8383](https://github.com/mohit8383)

---

## 🌟 Contributing
We welcome contributions to enhance this project! To contribute, follow these steps:

1. **Fork the repository**.
2. **Create a new branch** for your feature or fix:
   ```bash
   git checkout -b feature-name
   ```
3. **Commit your changes**:
   ```bash
   git commit -m "Add feature-name"
   ```
4. **Push your branch**:
   ```bash
   git push origin feature-name
   ```
5. **Open a pull request** to merge your changes.

---

## 🙏 Acknowledgements
- **Streamlit**: For enabling rapid web app development.
- **TensorFlow**: For facilitating deep learning model development.
- **AICTE Internship Program**: For providing inspiration and framework for this project.

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 📧 Contact
For inquiries or feedback, feel free to reach out:

- **GitHub**: [mohit8383](https://github.com/mohit8383)
- **Email**: mohitkasat83@gmail.com

   

