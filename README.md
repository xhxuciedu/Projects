# Summer Research Projects - 2020


* ## Project 1:  Rib Fracture Detection and Classification

This is a part of [MICCAI 2020 RibFrac Challenge:](https://ribfrac.grand-challenge.org/overview)

Diagnosis of rib fractures serves as an important and common task in clinical practice, forensics and several business scenarios (e.g., insurance claims). However, few prior studies investigate automatic machine learning techniques on this labor-intensive task. This challenge establishes a large-scale benchmark dataset to automatically detect and classify around 5,000 rib fractures from 660 computed tomography (CT) scans, which consists of 420 training CTs (all with fractures), 80 validation CTs (20 without fractures) and 160 evaluation CTs. Each annotation consists of a pixel-level mask of rib fracture regions (for serving detection), plus a 4-type classification. Both detection and classification tasks are involved in this challenge. An algorithmic challenge for rib fracture detection and classification is the elongated object shape. We hope this challenge could facilitate the research and application of automatic rib fracture detection and diagnoses.  

Project lead: [Hao Tang](mailto:htang6@uci.edu)

* ## Project 2: Green Space Classification

The aims of this project is to 1) develop a machine learning model that can reliably and efficiently classify the type of vegetation (e.g. grass, shrub/bush, tree) based on high resolution image data; and 2) apply the model to estimate vegetation types in two different study areas (i.e. southern California and Beijing, China) and examine exposure to green space in relation to sociodemographic factors (e.g. age, education, socioeconomic status, race/ethnicity) at small integrated spatial units (e.g. Census block in the U.S. and Jiedao or Zhen in China).  In the near future, the model will also be applied to estimate green space exposure of subjects in two epidemiological studies, one in southern California and one in China.  We will examine the associations of pregnant women's exposure to green space with their physical activity levels and pregnancy outcomes, e.g. pregnancy complication, preterm birth, and low birth weight.  Previously most such epidemiological studies relied on satellite-derived green space measure, such as Normalized difference vegetation index.  However, such measures did not specify the type of vegetation, which would affect people's physical activity, the effectiveness of stress reduction/cognitive restoration, the reduction of air pollution/noise/heat etc.  In addition, green space seen from the satellite is well above the top of the space, which is different from the angel what human eyes see.  Thus, we think it is important to develop a model that can differentiate the type of vegetation based on ground-level image data.

We have annotated Google Street View and Baidu Street View images of about 1300 scenes that cover both Beijing and southern California.   These annotated images will be used in model training and validation.  Previously an undergraduate student trained an efficient neural network (ENet) model with about 150 images.  The results are reasonably good although no extensive validation has been conducted.  In the summer of 2020, we would like to compare a few other machine learning models and pick a model with the best performance and is reasonably efficient.  We will also train the model with many more images.  We plan to draft paper focusing on the two aims  by the end of this summer.

Project lead: [Yi Sun](mailto:suny16@uci.edu) and [Daniel Chen](mailto:liangjc2@uci.edu)

* ## Project 3: Car Damage Inspection

In industries like car rental, both owners and renters, are at-risk of being a victim of fraud. To help aid in the claims process for insurance carriers, there needs to be a way to detect car damages from photos pre/post rental trip. This project aims to develop an accurate, reliable, and efficient algorithm for detecting all new damages by comparing both pre-trip and post-trip images, as well as evaluating the severity of them. 
We have >1000 images taken from Google Image search result and labeled with bounding boxes of different types of damages, such as scratches and dents. An easy solution is to develop a standard object detection model to find all damages from both pre-trip and post-trip images, then use traditional algorithm to find perspective transformation between both images, which will be used to find correspondences of all the detected bounding boxes. This algorithm will be the baseline for this project and we are trying to find better performed algorithms.

Project lead: [Xingwei Liu (Mart)](mailto:xingweil@uci.edu)

* ## Project 4: Hand Pose Estimation For Movement Disorders

The aim of the project is to develop state-of-the-art deep learning models to detect hand keypoints from 2D images. Once we have an accurate hand keypoint detection model, we will then develop an automatic, robust and objective system for MDS-UPDRS (for Parkinson and movement disorder) hand movement examination, which roughly consists of three major modules: 1) hand detection and pose estimation, 2) movement pattern extraction and signal analysis, and 3) MDS-UPDRS prediction. 

Project lead: [Haoyu Ma](mailto:haoyum3@uci.edu)

* ## Project 5: Mapping Human Dwellings with Remote Sensing and Machine Learning Method in Rural Africa Counties

House location represents one of the most important variables in the assessment of exposure to vector-
borne pathogens. Accurate information on house location can improve modeling disease transmission
risk and help planning interventions. However, obtaining accurate house location in vast rural areas of
Africa where there was no prior detailed mapping effort is labor-intensive, expensive, and time-
consuming. High-resolution remote sensing images are useful, but the traditional method to manually
identify house structure needs skilled technicians and also prone to errors due to morphological
resemblance of ground objects to human dwellings.
We conducted a pilot study by combining remote sensing images and machine learning methods to
detect human dwelling in a rural area of western Ethiopia. Using high resolution, pan-sharpened
Pléiades satellite images, and labeled data from the ground survey, a deep convolutional neural network
for object detection following by the Faster-RCNN method was used to generate low-level features and
high-level features. Bounded box regression and classification were conducted. The model was trained
on a 10 x 10 km area of images with 1471 labeled houses and tested on another three 10 x 10 km area
of satellite images in the nearby area. The model yielded an overall accuracy of 75% in the area and
88.2% accuracy on the corrugated iron sheet roof type houses.
We are going to expand the project sites in two dense population areas in Kenya to validate these
machine learning algorithms and also compare the results between sites to improve model prediction
accuracy. We expect the combination of remote sensing and machine learning methods can be used to
detect human dwellings, estimate human density, and the population under risk in rural Africa.

Project lead: [Alexander Lee](mailto:mingchil@uci.edu)


