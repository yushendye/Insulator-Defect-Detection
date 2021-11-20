# Training and evaluation of YOLO v4 model on Chinese Insulator Dataset
### Dataset downloaded from <a href = "https://github.com/InsulatorData/InsulatorDataSet"> here </a>

### As the dataset was in Pascal VOC format, I had to convert it into YOLO format. The tutorial was found <a href = "https://gist.github.com/Amir22010/a99f18ca19112bc7db0872a36a03a1ec"> here </a>

### I worked on this project during my research ineternship ar Aero2Astro
### Guidance from Mr. Hemanth Balaji Dandi

### To understand how I performed training, have a look at <a href = "https://github.com/yushendye/Insulator-Defect-Detection/blob/main/YOLO_v4_Insulator_Training.ipynb"> this </a> notebook

### Train mAP calculated on 648 training images <br>
<img src = "https://raw.githubusercontent.com/yushendye/Insulator-Defect-Detection/main/train_map.png" height = "500" width = "1000">

### Test mAP calculated on 204 test images<br>
<img src = "https://raw.githubusercontent.com/yushendye/Insulator-Defect-Detection/main/test_map.png" height = "500" width = "1000">

### Some of the predicted images are as follows:
### Insulator in good condition
<img src = "https://raw.githubusercontent.com/yushendye/Insulator-Defect-Detection/main/1.jpg">

### Insulators in good condition, having defect in some part
<img src = "https://raw.githubusercontent.com/yushendye/Insulator-Defect-Detection/main/2.jpg">
<img src = "https://raw.githubusercontent.com/yushendye/Insulator-Defect-Detection/main/3.jpg">
