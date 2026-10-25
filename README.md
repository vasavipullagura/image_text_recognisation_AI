
# 🖼️ Image or Text Recognition

## 📌 Project Overview

**Image or Text Recognition** is a simple AI-based web application that allows users to recognize objects in images and extract text from images.

The project uses pre-trained machine learning models and JavaScript libraries to perform image classification and Optical Character Recognition (OCR).

The application provides a user-friendly interface where users can upload an image, select a recognition mode, and view the results.

## 🎯 Objectives

- Develop a basic image and text recognition application.
- Use pre-trained AI models and available libraries.
- Identify objects present in uploaded images.
- Extract readable text from images.
- Display recognition results clearly.
- Understand the practical applications of Artificial Intelligence.

## ✨ Features

- **Image Recognition:** Identifies possible objects in an uploaded image.
- **Text Recognition:** Extracts readable text from images using OCR.
- **Image Upload:** Supports common image formats such as JPG, PNG, and WEBP.
- **Confidence Scores:** Displays prediction confidence percentages for image classification.
- **Copy Extracted Text:** Allows users to copy recognized text.
- **Responsive Design:** Works on desktops, tablets, and mobile browsers.
- **Simple Interface:** Provides an easy-to-use design.
- **Browser-Based:** Runs directly in a web browser without requiring a separate backend server.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Creates the website structure |
| CSS3 | Styles the application and makes it responsive |
| JavaScript | Implements the application functionality |
| TensorFlow.js | Runs machine learning models in the browser |
| MobileNet | Performs image classification |
| Tesseract.js | Extracts text using Optical Character Recognition |

## 📂 Project Structure

```text
Image-Text-Recognition/
│
├── index.html       # Complete website code
├── README.md        # Project documentation
└── screenshots/     # Optional project screenshots
```

The HTML, CSS, and JavaScript are combined in a single `index.html` file.

## ⚙️ Installation and Setup

### Step 1: Download the Project

Download or clone the project files to your computer.

### Step 2: Open the Project

Open the project folder in Visual Studio Code or another code editor.

### Step 3: Run the Application

Open `index.html` in a modern web browser.

For a more reliable development setup, use a local development server, such as the Live Server extension in Visual Studio Code.

### Step 4: Connect to the Internet

An internet connection is required to load the external JavaScript libraries and AI models from their CDNs.

No separate backend server or API key is required for the basic version.

## 🚀 How to Use

### Image Recognition

1. Open the application in your browser.
2. Select the **Image Recognition** tab.
3. Upload an image from your device.
4. Click **Analyze Image**.
5. Wait for the AI model to process the image.
6. View the predicted object labels and confidence percentages.

### Text Recognition

1. Open the application.
2. Select the **Text Recognition** tab.
3. Upload an image containing readable text.
4. Click **Extract Text**.
5. Wait for the OCR process to finish.
6. View the extracted text.
7. Click **Copy Extracted Text** to copy the result.

## 🧠 How It Works

### 1. Image Recognition

The application uses the pre-trained MobileNet model through TensorFlow.js.

The model analyzes the uploaded image and predicts likely image categories.

The application displays the predicted labels along with their confidence scores.

### 2. Text Recognition

The application uses Tesseract.js to perform Optical Character Recognition.

The OCR engine analyzes the uploaded image and attempts to identify readable characters and words.

The extracted text is displayed in the results section.

### 3. Result Display

JavaScript updates the interface to display predictions, confidence percentages, extracted text, and status messages.

## 📸 Example Applications

This project can be used to demonstrate:

- Identifying everyday objects in photographs.
- Recognizing animals, vehicles, and common objects.
- Extracting text from printed documents.
- Reading text from posters and signs.
- Converting text in images into copyable digital text.
- Exploring basic AI and machine learning concepts.

## 📋 Project Requirements

- A computer or mobile device.
- A modern web browser.
- An internet connection.
- An image file in a supported format.
- Basic knowledge of HTML, CSS, and JavaScript for further development.

## ⚠️ Limitations

- Image classification predictions may not always be accurate.
- MobileNet can only recognize categories supported by its trained model.
- OCR accuracy depends on image quality, lighting, font size, and text clarity.
- Handwritten text may be recognized less accurately than printed text.
- The first model download may take some time.
- External libraries and models require an internet connection in this version.
- The application is intended for educational and demonstration purposes.

## 🔮 Future Enhancements

- Add camera capture functionality.
- Support additional languages for text recognition.
- Add image history and saved results.
- Improve the interface with animations and themes.
- Add PDF text extraction.
- Package the application as an Android app.
- Explore offline model support.
- Add object detection with bounding boxes.

## 🎓 Learning Outcomes

Through this project, students can learn:

- How to integrate pre-trained AI models into a web application.
- How image classification works.
- How Optical Character Recognition works.
- How to process uploaded files using JavaScript.
- How to display model predictions and confidence scores.
- How to design a responsive web interface.
- How AI libraries can solve practical problems.

## 📚 Libraries and Resources

- TensorFlow.js: https://www.tensorflow.org/js
- MobileNet: https://github.com/tensorflow/tfjs-models/tree/master/mobilenet
- Tesseract.js: https://github.com/naptha/tesseract.js

## 👨‍💻 Author

**Project Name:** Image or Text Recognition  
**Project Number:** Project 4  
**Domain:** Artificial Intelligence and Machine Learning  
**Project Type:** Web Application

## 📄 License

This project is intended for educational and learning purposes. Review the licenses of the libraries and models used before redistributing the application.

---

**Thank you for checking out the Image or Text Recognition project!**
