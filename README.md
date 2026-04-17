# Neonatal-Care
This project focuses on evaluating a YOLOv11 computer vision model designed to detect physical markers of jaundice in newborn infants. By automating the detection process, we aim to provide a non-invasive screening tool for use in Neonatal Intensive Care Units (NICU).
Project Overview
This project focuses on evaluating a YOLOv11 computer vision model designed to detect physical markers of jaundice in newborn infants. By automating the detection process, we aim to provide a non-invasive screening tool for use in Neonatal Intensive Care Units (NICU).

Dataset & Training
Model: YOLOv11 (Classification/Detection)

Epochs: 50

Target: Real-time identification of skin discoloration associated with high bilirubin levels.

Key Performance Metrics
The model was audited using a custom AI analysis tool to identify the peak efficiency epoch.

Peak Precision: 94.4% (Epoch 49)

mAP50: 0.966

Training Stability: The model demonstrated a stable loss gap of 0.629, indicating strong generalization without significant overfitting.

Files in this Repository
results.csv: Raw training logs and performance data.

detect.py: Inference script for model execution.

data.yaml: Dataset configuration and class labeling.

Analysis_Report.pdf: The technical audit generated during the project.

2. Finalize the Udacity Free Responses
Go to the Udacity page for Project 2 (shown in your images e8c1ca.png and e8c209.png) and use these technical answers:

Box: "List 3 to 5 insights you discovered from the data."

The model reached its optimal performance at Epoch 49, where it achieved a 94.4% Precision rate.

The mAP50 score of 0.966 indicates extremely high confidence in the model's ability to distinguish jaundice markers from normal skin tones.

Training logs showed that Validation Loss stabilized around 1.305, suggesting the model is ready for real-world testing on a larger clinical dataset.
