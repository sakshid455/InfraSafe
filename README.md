# InfraSafe

## Overview
This repository presents **InfraSafe**, a comprehensive solution for infrastructure damage detection. The system focuses on crack prediction and severity assessment using a YOLOv model. It also includes a risk assessment module that evaluates structural integrity and classifies risk levels. Additionally, the project features a surveillance car powered by an ESP32 camera for real-time monitoring.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Contributors](#contributors)

## Features
- **Crack Prediction**: Detect cracks in infrastructure using a YOLOv-based deep learning model.
- **Severity Assessment**: Analyze detected cracks to estimate their severity.
- **Risk Assessment**: Categorize structural risk into Low, Moderate, or High based on crack severity.
- **Surveillance Car**: Includes code for an ESP32-based surveillance car with real-time video monitoring capabilities.

## Technologies Used
- **Python**
- **TensorFlow / Keras** – for the YOLOv model
- **OpenCV** – for image preprocessing and visualization
- **ESP32** – for embedded camera functionality
- **React** – for frontend interface (ML integration pending)

## Usage
- **Crack Detection**: Run the YOLOv model on infrastructure images to detect cracks.
- **Severity Prediction**: Use the severity assessment module to evaluate the seriousness of detected cracks.
- **Risk Assessment**: Apply the risk analysis function to categorize risk levels based on crack severity.
- **Surveillance Car**: Upload the provided ESP32 camera code to your ESP32 device and follow instructions in the `surveillance_car/` directory.

> ⚠️ *Due to time constraints, ML model integration with the frontend was not completed.*

## Contributors
- **Durvank Gade**
- **Kanad Bhattacharya**
- **Vasundhra Sharma**
- **Sakshi Datir**
