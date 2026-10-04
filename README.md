# AI-Podcast-Analyzer
# 🎙️ AI Podcast Analyzer

## 📌 Overview

The **AI Podcast Analyzer** is an artificial intelligence application that analyzes podcast audio and automatically extracts useful information from it. The system uses **Whisper** for speech-to-text conversion and a **Transformer-based summarization model** to generate a short summary.

The application also extracts important keywords from the podcast transcript and presents the results through an easy-to-use **Gradio web interface**.

## 🎯 Objectives

* To convert podcast speech into text automatically.
* To generate a short summary of podcast content.
* To identify important keywords from the transcript.
* To understand the use of AI in audio and text analysis.
* To create an interactive podcast analysis application.
* To run the complete application in Google Colab.

## 🛠️ Technologies Used

* **Python**
* **OpenAI Whisper**
* **Hugging Face Transformers**
* **BART**
* **Natural Language Processing (NLP)**
* **Gradio**
* **Google Colab**

## ⚙️ How It Works

1. The user uploads a podcast or audio file.
2. Whisper processes the audio.
3. The speech is converted into a text transcript.
4. The transcript is provided to a summarization model.
5. The AI generates a short summary.
6. Important keywords are extracted from the transcript.
7. The application displays the transcript, summary, and keywords.

## ✨ Features

* 🎤 Podcast audio upload
* 📝 Automatic speech transcription
* 📌 AI-generated podcast summary
* 🔑 Keyword extraction
* 🤖 AI-powered analysis
* 🌐 Interactive Gradio interface
* ☁️ Google Colab support
* 🚀 Beginner-friendly application

## 🧪 Example

### Input

```text
🎙️ Podcast Audio

A podcast discussing artificial intelligence,
machine learning, and the future of technology.
```

### Output

```text
📝 TRANSCRIPT

Today we are discussing artificial intelligence,
machine learning, and the future of technology.

📌 SUMMARY

The podcast discusses artificial intelligence,
machine learning, and their impact on future
technology.

🔑 KEYWORDS

artificial, intelligence, machine, learning,
technology, future
```

*The actual output depends on the uploaded audio.*

## ▶️ How to Run

### Step 1: Open Google Colab

Create a new notebook in Google Colab.

### Step 2: Add the Code

Copy the complete AI Podcast Analyzer code into **one cell**.

### Step 3: Run the Cell

Click the **Run ▶** button and wait for the required libraries and AI models to load.

### Step 4: Open the Application

After execution, Gradio will provide a web link.

### Step 5: Analyze a Podcast

Upload a podcast audio file or record audio and click:

**🔍 Analyze Podcast**

The application will display the transcript, summary, and keywords.

## 📂 Project Structure

```text
AI-Podcast-Analyzer/
│
├── ai_podcast_analyzer.ipynb
└── README.md
```

