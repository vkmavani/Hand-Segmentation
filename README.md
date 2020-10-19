# Hand-Segmentation

* In this repository, hand segmentation model is created using pre-trained weights.

* For this project, segmentation_models(https://github.com/qubvel/segmentation_models) package is used to create **U-net** with **efficientnetb3** backbone and then applied pre-trained weights.

* I also provided Keras **.H5** model with U-net architecture which takes input as (320,320) image and gives Segmentaed image with same height and width.

* Here is one example of Hand-Segmenation using this model,

<img src='https://github.com/vkmavani/Hand-Segmentation/blob/main/1.png'  />

<img src='https://github.com/vkmavani/Hand-Segmentation/blob/main/output_1.png'  />


## Pre-trained Model
Google Drive : <a href='https://drive.google.com/file/d/1elFVF0DZSdkecbXKW0KLObiDQ6bvV-VF/view?usp=sharing'>Hand-Segmentation Model</a>
