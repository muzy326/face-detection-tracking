# Face Detection & Tracking

Real-time face detection and tracking using OpenCV's Haar Cascade classifier, with a
face recognition component for identifying detected faces.

## Files

- `Facedetection1.py` — captures webcam video and detects faces in real time using
  `haarcascade_frontalface_default.xml`.
- `facerecognition.py` — extends detection to recognize/identify faces.
- `haarcascade_frontalface_default.xml` — pre-trained Haar Cascade classifier from
  OpenCV, used as the detection model.

## How to run

```bash
pip install opencv-python
python Facedetection1.py
```

Press `q` to quit the webcam window.

## How it works

Haar Cascade classifiers detect objects (faces, in this case) by scanning the image
for patterns of light/dark regions that match trained facial features, using a sliding
window across multiple scales to handle faces of different sizes and distances from
the camera.
