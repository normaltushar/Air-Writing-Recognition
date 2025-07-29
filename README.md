# Air-Writing-Recognition
Air Writing Recognition ✍️ - Real-time finger writing recognition using webcam, MediaPipe hand tracking, and CNN character recognition. Write in the air and see text appear on screen!

[![OpenCV](https://img.shields.io/badge/OpenCV-5.0-blue.svg)](https://opencv.org/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-0.10-red.svg)](https://mediapipe.dev/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.12-orange.svg)](https://tensorflow.org/)

A real-time system that recognizes characters written in the air using finger movements. Captures motion via webcam, processes hand landmarks with MediaPipe, and recognizes characters using a CNN model trained on EMNIST dataset.

![Demo](demo.gif) *(Replace with actual demo GIF)*

## Features ✨

- 👆 Real-time hand tracking with finger position visualization
- ✊ Pinch gesture control for start/stop writing
- 🎯 Character recognition for digits (0-9) and letters (A-Z, a-z)
- 📝 Real-time stroke visualization on virtual canvas
- ⚡ Optimized for performance (15-30 FPS)
- ⌨️ Keyboard fallback controls

## Installation ⚙️

1. **Clone repository**:
```bash
git clone https://github.com/yourusername/air-writing-recognition.git
cd air-writing-recognition
