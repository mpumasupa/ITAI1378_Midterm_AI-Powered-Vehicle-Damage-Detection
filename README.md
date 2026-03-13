## AI-Powered Vehicle Damage Detection
- Student: Milagros Pumasupa Terán  
- Course: ITAI 1378 – Computer Vision & AI  
- Tier: Tier 2 – Object Detection

## Project Overview

This project develops an AI-powered system capable of detecting vehicle damage from images using deep learning and computer vision techniques. The system identifies damaged areas such as dents, broken lights, and cracked windshields.

The goal is to automate vehicle inspection processes for applications such as insurance claims, fleet management, and repair services.

---

## Problem Statement

Manual vehicle damage inspection is time-consuming and often subjective. Insurance companies and repair shops rely on human inspection, which can lead to inconsistencies and delays.

An automated system using computer vision can improve the efficiency and accuracy of vehicle damage assessment.

---

## Solution

This project uses a deep learning object detection model to automatically identify damaged areas in vehicle images.

The model detects different types of vehicle damage and highlights the damaged regions using bounding boxes.

---

## Technologies Used

- Python
- PyTorch
- YOLOv8
- OpenCV
- Streamlit

---

## Dataset

Dataset used:

Automobile Damage Detection Dataset

Source: Roboflow Universe

Images: ~6,900 annotated images

Link:
https://universe.roboflow.com/automobile-damage-detection

The dataset contains labeled images with bounding boxes indicating different types of vehicle damage.

---

## Model

Object detection model:

YOLOv8

The model is trained using transfer learning and fine-tuned on the vehicle damage dataset.

---

## Metrics

Primary metric

mAP@0.5

Secondary metrics

Precision  
Recall  
F1-score

---

## Project Structure

AI-Powered-Vehicle-Damage-Detection

data/ 
docs/
notebooks/


