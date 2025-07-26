## Overview
Capture the Scene is a video processing application that allows users to upload a video file, extract frames from it, and create a panorama image using OpenCV. This project is implemented in a Jupyter Notebook and provides a simple interface for users to generate panoramic images from their videos.

## Features
- Upload a video file (e.g., .mp4).
- Extract frames from the video at specified intervals.
- Create a panorama image by stitching the extracted frames together.
- Visualize the generated panorama image.
- Save and download the panorama image.

## Requirements
To run this project, you need the following:
- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Google Colab (for file upload functionality)

## Usage
1. Open the `capture_the_scene.ipynb` file in Jupyter Notebook or Google Colab.
2. Run the first cell to upload a video file.
3. The notebook will extract frames from the video and create a panorama image.
4. The generated panorama will be displayed, and you will have the option to download it.

Meme Search Notebook
Overview
This notebook enables semantic search of memes using OCR and sentence embeddings. It extracts text from meme images, encodes the text, and allows users to search for memes by query.

Features
Text Extraction: Uses Tesseract OCR to extract text from meme images.
Semantic Embedding: Encodes extracted text using Sentence Transformers (all-MiniLM-L6-v2).
Search: Finds memes most relevant to a user query using cosine similarity.

Timestamp_IT Notebook
Overview
This notebook extracts audio from a video, transcribes it using OpenAI Whisper, and finds the timestamp for a given text query using fuzzy matching.

Features
Audio Extraction: Uses moviepy to extract audio from video files.
Speech Transcription: Uses Whisper to transcribe audio into text segments with timestamps.
Fuzzy Search: Uses RapidFuzz to find transcript segments matching a query, returning the timestamp.


Waiter Calling Notebook
Overview
This notebook detects raised hands in a video using MediaPipe and OpenCV, and outputs timestamps where a hand-raise gesture occurs. Useful for automating waiter-calling or hand-raise detection in meetings/events.

Features
Hand Detection: Uses MediaPipe to detect hands in each video frame.
Gesture Recognition: Identifies raised hand gestures by comparing wrist and index finger positions.
Timestamp Extraction: Records the exact time (in seconds) when a raised hand is detected.
Visualization: Optionally displays frames with detected hands.
