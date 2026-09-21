# Deep Learning-Based Intelligent Vehicle Surveillance System with Automatic Number Plate Recognition, 
An AI-powered vehicle surveillance and Automatic Number Plate Recognition (ANPR) system that detects and tracks vehicles, recognizes license plates using OCR, validates results across multiple frames, and supports database verification. The system aims to improve recognition reliability, reduce false alerts, and enable efficient vehicle monitoring through automated processing.


# Features

- Vehicle detection using YOLO
- Multi-object tracking using ByteTrack
- License plate detection
- OCR using EasyOCR
- Multi-frame OCR validation
- Confidence-based verification
- Indian license plate format validation
- Database matching
- Vehicle status identification
- ANPR result logging
- Processing-time measurement

# System Pipeline

      CCTV / Video
           ↓
     Vehicle Detection
           ↓
     Vehicle Tracking
         ↓
     License Plate Detection
          ↓
      Plate Cropping
            ↓
       Image Preprocessing
           ↓
           OCR
             ↓
      Confidence Validation
             ↓
      Multi-Frame Validation
             ↓
      Database Verification
              ↓
         Alert / Result

## Technologies

- Python
- YOLO
- OpenCV
- EasyOCR
- ByteTrack
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Installation

```bash
      pip install -r requirements.txt
