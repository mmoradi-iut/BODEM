# BODEM
Black-box Object Detection Explanation by Masking

In this repository, you can find information, results, and source codes of the BODEM explanatation method. The method and experiments are described and discussed in this paper: "Model-agnostic explainable artificial intelligence for object detection in image data", [https://www.sciencedirect.com/science/article/pii/S0952197624013411](https://www.sciencedirect.com/science/article/pii/S0952197624013411).

<h2>The black-box explanation method</h2>
<p>The following image illustrates the overal architecture of our BODEM explanation method:</p>
<br>
<img width="1000" src="https://github.com/mmoradi-iut/BODEM/blob/main/Figure-1.jpg">

<h2>Object detection models</h2>
<p>We trained three object detection models on three different datasets.</p>
<p>The object detection moddels are as follows:
<br>

- You Only Look Once (YOLO). [Link to the paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Redmon_You_Only_Look_CVPR_2016_paper.html)
- Regions with CNN (R-CNN). [Link to the paper](http://openaccess.thecvf.com/content_cvpr_2014/html/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.html)
- Single-Shot Detector (SSD). [Link to the paper](https://link.springer.com/chapter/10.1007/978-3-319-46448-0_2)</p>

<h2>Object detection datasets</h2>
<p>We trained the object detection models on three different datasets.</p>
<p>Link to the datasets:
<br>

- The YOLO model was trained on a user interface control detection dataset.
- The R-CNN model was trained on a airplane detection: [Link to the dataset](https://www.kaggle.com/datasets/airbusgeo/airbus-aircrafts-sample-dataset)
- The SSD model was trained on a vehicle detection, which is a subset of COCO, containing four object classes, i.e. CAR, BUS, TRUCK, and MOTORCYCLE: [Link to the dataset](https://link.springer.com/chapter/10.1007/978-3-319-10602-1_48)</p>

<h2>Explanation methods</h2>
<p>We evaluated the effectiveness of our explanation method against D-RISE using various objective metrics.</p>
<br>

- Detector Randomized Input Sampling for Explanation (D-RISE). [Link to the paper](http://openaccess.thecvf.com/content/CVPR2021/html/Petsiuk_Black-Box_Explanation_of_Object_Detectors_via_Saliency_Maps_CVPR_2021_paper.html)</p>
- Local Interpretable Model-agnostic Explanations (LIME). [Link to the paper](https://dl.acm.org/doi/abs/10.1145/2939672.2939778)</p>
