# AI-Assisted Smart Video Editing System

This project presents an AI-based system that automates key video editing tasks such as silence trimming and subtitle generation using audio signal processing and speech recognition models.

---

## Problem Statement
Manual video editing is time-consuming and repetitive, particularly for tasks like removing silent segments and creating subtitles. This project aims to automate these processes using AI techniques to improve efficiency and consistency.

---

## Approach & Pipeline
1. Extract audio from input video using FFmpeg
2. Detect silent segments using RMS energy analysis
3. Trim silence while preserving meaningful speech
4. Generate subtitles using the Whisper speech-to-text model
5. Burn subtitles into the final video

---

## Technologies Used
- Python
- FFmpeg
- Librosa
- OpenAI Whisper
- OpenCV

---

## How to Run
1. Open the Jupyter Notebook (`AI in Video Editing.ipynb`)
2. Run all cells sequentially from top to bottom
3. Provide a valid input video file when prompted

---

## Outputs
- Silence-trimmed video
- Subtitle file (`.srt`)
- Final video with embedded subtitles

---

## Repository Note
📌 The Jupyter Notebook (`.ipynb`) is the **primary source of truth for evaluation**, as per IIT Ropar project submission guidelines.
