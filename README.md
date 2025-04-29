# YOLO11-Model
Lab Assignment NO.03: Object Detection and Multi Object Classification (4 HOURS)-YOLO11 Model

## 1. Objective
The objective of this assignment is to implement object detection using a pre-trained model. YOLOv5 (You Only Look Once) is used for detecting objects in images or video streams with high speed and accuracy.

## 2. Problem Definition
- **Dataset**: A custom dataset for object detection (e.g., vehicles, persons, or other labeled classes).
- **Task**: Use a pre-trained YOLOv5 model to detect and localize objects in the images.
- **Approach**: Use YOLOv5’s pretrained weights for inference or fine-tune on the custom dataset.

## 3. Methodology

### Pre-trained Model Used
- **Model**: YOLOv5 (v5s, v5m, or v5l depending on use-case)
- **Framework**: PyTorch

### Steps
1. **Install Dependencies**:
   - Clone YOLOv5 repository
   - Install requirements using pip

2. **Prepare Dataset**:
   - Annotated in YOLO format (TXT files with class and bounding box info)
   - Images and labels organized under `train`, `val`, and `test` folders

3. **Load Pre-trained Model**:
   - Load YOLOv5 model with pre-trained weights from COCO dataset

4. **Train (Optional)**:
   - Fine-tune the model on the custom dataset

5. **Inference**:
   - Use `detect.py` to run inference and visualize detected objects

6. **Evaluation**:
   - Analyze metrics such as mAP (mean Average Precision)

## 4. Libraries & Tools
- PyTorch
- OpenCV
- YOLOv5 (Ultralytics GitHub)
- Matplotlib
- Pandas

## 5. Results
- Object detection results visualized with bounding boxes
- Accuracy and inference time recorded
- Detected classes and confidence scores shown

---

## Declaration
I, **Rohit Nikat**, confirm that the work submitted in this assignment is my own and has been completed following academic integrity guidelines. The code is uploaded on my GitHub repository account, and the repository link is provided below:

