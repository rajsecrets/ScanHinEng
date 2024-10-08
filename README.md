# OCR & Keyword Search Web Application

This project is a **web-based prototype** that demonstrates Optical Character Recognition (OCR) on an uploaded image containing text in both **Hindi and English**. The application also provides a basic keyword search functionality to highlight the searched words from the extracted text. The web app is deployed and accessible via a live URL.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Deliverables](#deliverables)
- [Future Improvements](#future-improvements)
- [Contributors](#contributors)

## 📖 Overview
This application allows users to:
1. Upload an image containing Hindi and/or English text.
2. Perform **OCR** on the image to extract the text.
3. Search for specific keywords in the extracted text, with results highlighted.

## ✨ Features
- **Optical Character Recognition (OCR):** Extracts text from images containing both Hindi and English using the `easyocr` library.
- **Keyword Search:** Allows users to search for keywords in the extracted text and highlights them.
- **Language Detection:** Identifies if the text contains Hindi, English, or both.
- **Text Download:** Users can download the extracted text in a `.txt` file format.

## 🚀 Technologies Used
- **Streamlit:** Web framework to build the app UI.
- **EasyOCR:** OCR tool to extract Hindi and English text from images.
- **PIL (Pillow):** Image processing library.
- **Numpy:** Handling image arrays for OCR processing.
- **Regex:** Used for keyword matching and highlighting.
- **Lottie Animations:** For smooth UI loading animations.
  
## 💻 Installation

### Prerequisites
Make sure you have the following installed:
- **Python 3.7+**
- **pip** (Python package installer)

### Clone the repository
```bash
git clone https://github.com/yourusername/ocr-keyword-search-app.git
cd ocr-keyword-search-app
```

### Install dependencies
Use the provided `requirements.txt` file to install necessary libraries.
```bash
pip install -r requirements.txt
```

### List of Required Libraries
- streamlit
- easyocr
- numpy
- pillow
- requests
- streamlit-lottie

You can also install them manually:
```bash
pip install streamlit easyocr numpy pillow requests streamlit-lottie
```

## 🎮 Usage

1. **Run the application locally:**
   ```bash
   streamlit run app.py
   ```

2. **Upload an Image:** 
   Once the app is running, use the **Upload Image** section to upload an image in `jpg`, `jpeg`, or `png` format.

3. **Extract Text:** 
   Click on the **Extract Text** button to run the OCR process. The extracted text will be displayed in the **Extracted Text** section.

4. **Keyword Search:**
   Enter a keyword in the **Keyword Search** section to search for specific words in the extracted text. The app will highlight the results.

5. **Download Text:**
   You can download the extracted text using the **Download Extracted Text** button.

## 🌍 Deployment

The web application is deployed and accessible via the following live URL: [Live Application URL](https://your-live-url.com)

### Deploying on Streamlit Cloud:
1. Upload the code repository to GitHub.
2. Go to [Streamlit Cloud](https://streamlit.io/cloud) and create a new app by connecting it to your GitHub repository.
3. Choose the `app.py` file as the entry point.
4. Click **Deploy**.

### Deploying on Hugging Face Spaces:
1. Go to [Hugging Face Spaces](https://huggingface.co/spaces) and create a new space.
2. Upload your project files.
3. Choose **Streamlit** as the runtime.
4. Deploy your app.

## 📝 Deliverables
- **Code Submission:** The complete Python code is available in this repository.
- **Live Web Application:** The deployed version is accessible via the live URL.
- **Extracted Text Output:** The app extracts text from images and provides the option to download it as `.txt`.
- **Keyword Search Demonstration:** Users can search for keywords within the extracted text and see the highlighted results.

## 🔮 Future Improvements
- Support for more languages, beyond Hindi and English.
- Improved UI/UX with more styling options.
- Integration with a more advanced OCR model like HuggingFace Transformers for better accuracy.
- Option to handle scanned PDFs with multi-page OCR.

## 🤝 Contributors
- [Your Name](https://github.com/yourusername) - Project Developer
- Special thanks to the contributors of **EasyOCR** and **Streamlit**.

---

Created with ❤️ for your Hackathon project.
```

### How to Use:
- Replace `https://github.com/yourusername/ocr-keyword-search-app.git` with your actual GitHub repository link.
- Replace `https://your-live-url.com` with the URL of your deployed app.

This `README.md` is designed to be informative and user-friendly, covering installation, usage, and deployment instructions in detail.
