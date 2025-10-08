# COMPUTER_VISION-
**Face_recognigation**:
with btk akademi computer vision  course
if you get course files you can download this link https://files.btkakademi.gov.tr/128_BILGISAYARLI_GORU_UYGULAMA_ALANLARI/Bolum_1_2_3_4_Yuz_Tanima.zip ı use GOOGLE COLAB because ı havent screen cart hardware on my computer .


"""
SOTA Ç The state of the art 

1. MS1M download full dataset(CASIA)
2. conf.mode = "ir"
3. conf.depth = "100"
4. conf.total_epoch = 20
5. conf.milestones = [12,16,18]


lfw =99.83%
#2 v100(32gb)5 days


MobileFaceNet if you want  run this train model on any device  you can use MobileFaceNet 

# 

**fish_detection**
This project uses YOLOv8 to detect fish in images with bounding boxes. Built on a ready-to-use dataset from Roboflow Universe, it was trained and tested in Google Colab with fast, accurate results. Whether you're building a marine monitoring tool or just love aquatic creatures, this model is a playful and effective solution

 Dataset
- Source: Fish Detection – Roboflow Universe
- Format: YOLOv8
- Classes: 1 (fish)
- Annotations: Bounding boxes included, no manual labeling required

 Features
- Fast and accurate object detection with YOLOv8
- Roboflow API integration for seamless dataset access
- Google Colab compatible training and inference
- Visual output with bounding boxes
- Simple, elegant, and aquatic


**object_detection_retinanet**: is a RetinaNet-powered object detection project that identifies and locates airborne objects such as airplanes, helicopters, drones, and birds in diverse sky conditions. Built with a narrative-driven approach, this project transforms technical modeling into a visual performance.

This project implements RetinaNet without relying on external libraries like Fizyr. All components are built directly using PyTorch and torchvision.


Rather than importing pre-built RetinaNet from Fizyr, this project builds the model layer by layer, treating each component as a scene in a technical performance

# 📦 Dataset

- **Source**: AOD-4 Dataset (Mendeley Data)
- **Classes**: Airplane, Helicopter, Drone, Bird
- **Conditions**: Day, night, cloudy, rainy, snowy
- **Annotations**: COCO format with bounding boxes


 Model Architecture

- **Backbone**: ResNet-50 with Feature Pyramid Network (FPN)
- **Detection Head**: RetinaNet with Focal Loss for class imbalance
- **Framework**: PyTorch + torchvision




