## Apple-Leaf-Health-Analyzer
Ai powered web app to automatically analyze the health of apple tree leaves.

Under Construction...


Live Web App: http://apple.test.woza.work/

<br>

<img src="http://apple.test.woza.work/assets/app_pic.png" width="350"></img>

<br>

This is a prototype for an online tool that can classify the health of apple tree leaves into one of four classes:
- healthy
- multiple_diseases
- rust
- scab


Model F1 score: <br>
Model Accuracy: 

<hr>

### Mobile-First

The app is mobile optimized. With a mobile phone, the apple leaves can be photograhed at different angles, depths and under different lighting conditions. This makes it easy to field test this model.

- On your phone navigate to http://apple.test.woza.work/
- Click the Submit button and then select "Camera". (This works on Android.)
- Take a photo of a leaf. The photo will be sent directly to the app for classification.

<hr>


The process that I followed to build and train the model is described in this Kaggle kernel:<br>



The dataset used to train the model consists of 1821 training images. It is part of the Kaggle Plant Pathology 2020 - FGVC7 research competition:<br>
https://www.kaggle.com/c/plant-pathology-2020-fgvc7/overview

All javascript, html and css files used to create the web app are available in this repo.

