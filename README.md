# Face Detection using OpenCV and MediaPipe

A real-time face detection project built using Python, OpenCV, and MediaPipe. The application detects faces through a webcam and displays bounding boxes, confidence scores, and FPS.

## Features

- Real-time face detection using a webcam
- Custom corner-style bounding boxes around detected faces
- Face detection confidence percentages
- Bounding-box coordinates and confidence scores
- FPS display

## Technologies Used

- Python
- OpenCV
- MediaPipe

## Installation

Install the required libraries:

```bash
pip install opencv-python mediapipe
```

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

```bash
python FaceDetectionModule.py
```

4. Allow access to your webcam.
5. Press `q` to close the application.

## Main Components

- `FaceDetector` — Initializes the face detector.
- `findFaces()` — Detects faces and returns bounding-box information.
- `fancyDraw()` — Draws decorative corner-style boxes around detected faces.

## Notes

A working webcam and compatible Python and MediaPipe versions are required. Detection performance may vary depending on lighting, camera quality, and face position.

## Author

Developed as a computer vision learning project.
