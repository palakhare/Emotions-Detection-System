EMOTION DETECTION SYSTEM

A real-time AI web application that detects human emotions from text or video (facial expressions) using Machine Learning and Deep Learning.
🌟 Overview

The Emotion Detection System identifies emotions from:

Facial Expressions (Real-Time Video) – Captures live webcam feed to detect emotions such as Happy, Sad, Angry, Surprise, Neutral, Fear, Disgust.

Text Messages – Analyzes the emotional tone (positive, negative, neutral) of a given text input.

This system can be integrated into mental health apps, customer support platforms, e-learning tools, and entertainment applications to enhance user experience.

✨ Features

✅ Dual Mode: Detect emotions from live video or text input
✅ Real-time face detection & emotion classification using CNN
✅ Pre-trained NLP model for sentiment analysis on text
✅ Lightweight web interface for easy use
✅ Visual emotion probability graph for each detection
✅ Option to save analysis reports for research or review

🛠️ Tech Stack
Component	Technology
Programming Language	Python 3.9+
Frontend	React.js / Streamlit / HTML-CSS-JS
Backend	Flask / Django
Machine Learning	TensorFlow / Keras (CNN for face emotions)
Computer Vision	OpenCV (Haar Cascades / DNN Face Detector)
NLP (Text Emotions)	Scikit-learn / Hugging Face Transformers
Database (Optional)	MongoDB / SQLite (to store results)
Deployment	AWS / Azure / Streamlit / Docker
🏗️ System Architecture
+-----------------------------+
|        User Interface       |
| (Web App / Streamlit Front) |
+--------------+--------------+
               |
        API Requests (Flask/Django)
               |
+--------------v--------------+
|        Backend Engine       |
| - OpenCV Face Detection     |
| - CNN Emotion Classifier    |
| - NLP Sentiment Analysis    |
+--------------+--------------+
               |
+--------------v--------------+
|   Output & Visualization    |
| (Emotion Labels & Graphs)   |
+-----------------------------+

💻 Installation
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/emotion-detection-system.git
cd emotion-detection-system

2️⃣ Create a Virtual Environment & Install Requirements
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt

3️⃣ Download Pre-trained Models

FER-2013 Dataset Model
 for facial emotion recognition.

(Optional) Pre-trained NLP model from Hugging Face
 for text emotion detection.

4️⃣ Run the App
python app.py


OR if using Streamlit:

streamlit run app.py

🚀 Usage

For Video Emotion Detection

Allow webcam access.

Click Start Camera to detect emotions in real time.

For Text Emotion Detection

Enter a sentence, e.g.:

"I am feeling great today!"

Get instant sentiment and emotion classification.

🖼️ Screenshots
Feature	Screenshot
Live Video Emotion Detection	(Add image link here)
Text Emotion Analysis	(Add image link here)
Probability Graph	(Add image link here)
📂 Dataset

Facial Emotion Recognition: FER-2013

Text Sentiment Analysis: IMDB, Twitter Sentiment datasets, or custom collected text data.

🔮 Future Enhancements

✅ Multi-Language Support for text sentiment (Hindi, Marathi, etc.)

✅ Add Voice Tone Emotion Detection using audio analysis.

✅ Improve accuracy using Transfer Learning (e.g., ResNet, VGGFace).

✅ Deploy as a Mobile App using Flutter or React Native.

📜 License

This project is licensed under the MIT License
.
Feel free to use, modify, and distribute with proper credit.
