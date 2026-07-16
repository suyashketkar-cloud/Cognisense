Cognisense: A Multi-Modal Sentiment Analyzer
Cognisense is an AI-powered Multi-Modal Sentiment Analysis system that detects and analyzes human emotions using multiple input modalities including text, audio, image, and video. The system combines Natural Language Processing (NLP), Computer Vision, and Audio Signal Processing techniques to generate comprehensive sentiment insights.

Project Overview:
Traditional sentiment analysis focuses only on text. Cognisense goes beyond that by integrating:

Text Sentiment Analysis
Audio Emotion Detection
Image-Based Facial Emotion Recognition
Video Sentiment Analysis
Real-Time Video Emotion Analysis
By combining multiple modalities, Cognisense provides more accurate and context-aware sentiment predictions.

Features
Multi-modal emotion prediction
Real-time detection using webcam
Interactive user interface
Modular analyzer architecture
Visualization using charts
Project Structure
Cognisense/
│
├── analyzers/
│   ├── text_analyzer.py
│   ├── audio_analyzer.py
│   ├── image_analyzer.py
│   ├── video_analyzer.py
│   └── realtime_video_analyzer.py
│
├── static/
│   ├── css/styles.css
│   └── js/main.js
│
├── templates/
│
├── app.py
├── utils.py
├── requirements.txt
└── README.md
Technologies Used
Python
Flask
TensorFlow
OpenCV
Librosa
Scikit-learn
HTML, CSS, JavaScript
Installation
Clone Repository
git clone https://github.com/GazanfarAnsari10/Cognisense-A-Multi-Modal-Sentiment-Analyzer.git
Create Virtual Environment
python -m venv venv
Activate Environment (Windows)
venv\Scripts\activate
Install Dependencies
pip install -r requirements.txt
Run Application
python app.py
How It Works
Text processed using NLP models
Audio analyzed using MFCC and spectral features
Images and video processed using facial emotion recognition
Real-time webcam emotion detection
Use Cases
Social media sentiment monitoring
Customer feedback analysis
Mental health analysis
Human-computer interaction
Market research
Future Enhancements
Multimodal deep learning fusion model
Cloud deployment
API integration
Faster inference optimization
