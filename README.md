# 🎙️ Audio-to-Text MCQ Generator

This project converts speech (from uploaded audio files or YouTube videos) into text and then generates multiple-choice questions (MCQs) based on the transcript. It uses:

- **Speech Recognition**: Google Speech API for converting audio to text.
- **Natural Language Processing**: NLTK for extracting keywords and generating MCQs.
- **Gradio**: For creating a user-friendly interface to upload audio or provide YouTube links.

## Features

- Upload audio files or provide YouTube video URLs.
- Convert speech to text using Google Speech API.
- Generate multiple-choice questions based on the transcript.
- Option to specify a topic to focus the MCQ generation.
- Flexible control over the number of questions generated.

## Installation

1. Install the required libraries:
   ```bash
   pip install --upgrade nltk gradio yt-dlp pydub SpeechRecognition
