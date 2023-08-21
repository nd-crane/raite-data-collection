---
name: Blue team template
about: Template for gathering information related to the ML framework components,
  Datasets, and Models used by the Blue Team.
title: "[RAITE Data Collect] {team name}, {university}"
labels: blue team info
assignees: ''

---

### Team Information:

- Name: [Insert Your Team Name]
- University: [Insert Your University Name]
- Members: 
  - [Member 1 Name] ([Member 1 Email])
  - [Member 2 Name] ([Member 2 Email])
- GitHub repository:  [Please provide the link to your GitHub repository where your code is located, if applicable]

#### Datasets:

- Dataset Name: [Insert Dataset Name]
- Originated By: [Insert Originating Entity, e.g., Roboflow 100]
- Download Location: [Insert Download Location, e.g., https://huggingface.co/datasets/Francesco/road-traffic/resolve/main/dataset.tar.gz]
- Primary Purpose: [Insert Primary Purpose, e.g., Object Detection]
- Release Time: [Insert Release Time, e.g., 09-14-2022]
- Dataset Type: [Insert Dataset Type(s), e.g., image]
- Creation Info: [Insert Creation Information, e.g., None]
- Description: [Insert Description]
- Comment: [Insert Comment]
- Extension: [Insert Extension, e.g., JPEG]
- Supplied By: [Insert Supplier, e.g., Roboflow]
- Declared License: [Insert Declared License, e.g., CC BY 4.0]
- Homepage: [Insert Homepage, e.g., https://universe.roboflow.com/object-detection/road-traffic]
- Source Info: [Insert Source Info, e.g., https://huggingface.co/datasets/Francesco/road-traffic]
- Data Collection Process: [Insert Data Collection Process, e.g., Annotators are Roboflow users]
- Dataset Size: [Insert Dataset Size, e.g., 75112339]
- Dataset Noise: [Insert Dataset Noise]
- Data Preprocessing: [Insert Data Preprocessing Methods]
- Sensor: [Insert Sensor]
- Known Bias: [Insert Known Bias]
- Sensitive Personal Information: [Insert Sensitive Personal Information]

#### Models:

- Model Name: [Insert Model Name]
- Supplied By: [Insert Supplier(s), e.g., CMU]
- Download Location: [Insert Download Location, e.g., https://github.com/CMU-Perceptual-Computing-Lab/openpose]
- Package Version: [Insert Package Version, e.g., v1.7.0]
- Primary Purpose: [Insert Primary Purpose(s), e.g., Human pose estimation]
- Release Time: [Insert Release Time, e.g., Nov 17, 2020]
- Creation Info:
  - Authors: [Insert Authors, e.g., Ginés Hidalgo, Zhe Cao]
  - Maintainers: [Insert Maintainers, e.g., Ginés Hidalgo, Yaadhav Raaj]
- Summary: [Insert Summary, e.g., OpenPose is a real-time multi-person system...]
- Description: [Insert Description, e.g., OpenPose is a state-of-the-art computer vision system...]
- Comment: [Insert Comment, e.g., OpenPose would not be possible without the CMU Panoptic Studio dataset.]
- Verified Using: [Insert Verification Methods, e.g., Unit tests, Integration tests]
- External Reference: [Insert External References, e.g., https://github.com/CMU-Perceptual-Computing-Lab/openpose]
- External Identifier: [Insert External Identifiers, e.g., DOI: 10.1109/CVPR.2017.745]
- Extension: [Insert Extension, e.g., tar.gz]
- Originated By: [Insert Originating Entity, e.g., CMU-Perceptual-Computing-Lab]
- Built Time: [Insert Built Time, e.g., Nov 17, 2020]
- Additional Purpose: [Insert Additional Purpose(s), e.g., Motion capture, Gesture recognition]
- Declared License: [Insert Declared License, e.g., Apache License 2.0]
- Copyright Text: [Insert Copyright Text, e.g., Copyright (c) 2018-2021, CMU-Perceptual-Computing-Lab]
- Attribution Text: [Insert Attribution Text, e.g., OpenPose by CMU-Perceptual-Computing-Lab]
- Package URL: [Insert Package URL, e.g., https://github.com/CMU-Perceptual-Computing-Lab/openpose]
- Homepage: [Insert Homepage, e.g., https://github.com/CMU-Perceptual-Computing-Lab/openpose]
- Source Info: [Insert Source Info, e.g., Source code available on GitHub]
- Energy Consumption: [Insert Energy Consumption, e.g., Low energy consumption]
- Standard Compliance: [Insert Standard Compliance, e.g., IEEE 802.3]
- Limitation: [Insert Limitation, e.g., OpenPose is designed to work on single images and may not be suitable for real-time video processing.]
- Type of Model: [Insert Type of Model(s), e.g., Computer Vision, Deep Learning]
- Information About Training: [Insert Information About Training, e.g., OpenPose was trained on the CMU Panoptic Studio dataset.]
- Information About Application: [Insert Information About Application, e.g., OpenPose can be used for a variety of applications, including human pose estimation, motion capture, and gesture recognition.]
- Hyperparameters:
  - Learning Rate: [Insert Learning Rate, e.g., 0.001]
  - Batch Size: [Insert Batch Size, e.g., 32]
  - Number of Epochs: [Insert Number of Epochs, e.g., 50]
- Model Data Preprocessing: [Insert Data Preprocessing Methods, e.g., Image normalization, Data augmentation]
- Model Explainability: [Insert Explainability Methods, e.g., Heatmaps, Part affinity fields]
- Sensitive Personal Information: [Insert Sensitive Personal Information, e.g., false]
- Metric Decision Threshold:
  - Accuracy: [Insert Accuracy Threshold, e.g., 0.95]
- Metrics:
  - Accuracy: [Insert Accuracy, e.g., 0.98]
  - Precision: [Insert Precision, e.g., 0.96]
  - Recall: [Insert Recall, e.g., 0.97]
- Domain: [Insert Domain(s), e.g., Computer Vision, Artificial Intelligence]
- Autonomy Type: [Insert Autonomy Type, e.g., false]
- Safety Risk Assessment: [Insert Safety Risk Assessment, e.g., {}]


#### Components of TAI Framework:

Can you provide more information on which specific components of the [TAI framework](https://la3d.github.io/nuggets/posts/frameworks-reflection/) were used during your ML process? 
At what stage within the machine learning pipeline were these components implemented/used?

[Here](https://la3d.github.io/nuggets/posts/frameworks-reflection/graphic_tai-framework-1-new.png) is a diagram of the TAI Core Framework that you can use for reference.
Find more information about the TAI Framework at [https://la3d.github.io/nuggets/posts/frameworks-reflection/](https://la3d.github.io/nuggets/posts/frameworks-reflection/) 

**AI IDEs:**

- [Insert AI IDE Name]
  - ML Pipeline Steps: [Insert ML Pipeline Steps]

Example:
- [VS Code]
  - MLPipelineSteps: Data Collection, Data Preparation, Feature Extraction, Training, Testing, Inference
- [Jupyter]
  - MLPipelineSteps: Data Collection, Data Preparation, Feature Extraction

**Pre-trained Libs/Tools:**

- [Insert Pre-trained Lib/Tool Name]
  - ML Pipeline Steps: [Insert ML Pipeline Steps]

Example:
- [Hugging Face]
  - MLPipelineSteps: Data Collection, Data Preparation
- [AWS]
  - MLPipelineSteps: Data Collection, Data Preparation, Feature Extraction, Training, Testing


**ML Tools:**

- [Insert ML Tool Name]
  - ML Pipeline Steps: [Insert ML Pipeline Steps]

**Development Tools & Techniques:**

- [Insert Development Tool/Technique Name]
  - ML Pipeline Steps: [Insert ML Pipeline Steps]

**Platforms:**

- [Insert Platform Name]
  - ML Pipeline Steps: [Insert ML Pipeline Steps]
