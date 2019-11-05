# Detecting *P. falciparum* Using Deep Learning in Thick Blood Smear Samples

### Introduction

Deep learning methods have resulted in significant advancement in the field of computer vision, to the extent that the accuracy of deep learning programs have surpassed human capabilities in some object-recognition tasks. (He et al., 2015). The aim of this project is to evaluate the performance of convolutional neural networks in diagnosing malaria from thick blood smears. The algorithms/models being tested are, YOLOv2 and YOLOv3 trained using the Turicreate and ImageAI frameworks for the Python language.

### Information about the notebooks 

* **Turicreate - Object Detection - Malaria - 01.ipynb** - YOLOv2 Model Trained on an annotated malaria image dataset (118 MB): 1182 thick blood smear images with bounding boxes of 7245 parasites.

* **Turicreate - Object Detection - Malaria - 02.ipynb** - YOLOv2 Model Trained on an annotated image dataset of plasmodium (malaria parasite), including 2703 images with bounding boxes of 50,255 parasites

* **ImageAI - Object Detection - Malaria.ipynb** - YOLOv3 Model Trained on an annotated image dataset of plasmodium (malaria parasite), including 2703 images with bounding boxes of 50,255 parasites

### Using the notebooks 

You can run these notebooks by going to Google Colab and importing the notebooks using their direct URLs

**Change the runtime type to GPU for a faster training time**

### Acknowledgements

The dataset used is from the Makerere University, Uganda. Citation as written on their website:

* J.A. Quinn, R. Nakasi, P.K. Mugagga, P. Byanyima, W. Lubega, A. Andama. Deep Convolutional Neural Networks for Microscopy-Based Point of Care Diagnostics. Proceedings of the International Conference on Machine Learning for Health Care, Journal of Machine Learning Research W&C track, Volume 56, 2016.

* J.A. Quinn, A. Andama, I. Munabi, F.N. Kiwanuka. Automated Blood Smear Analysis for Mobile Malaria Diagnosis. Chapter in Mobile Point-of-Care Monitors and Diagnostic Device Design, eds. W. Karlen and K. Iniewski, CRC Press, 2014.

*No code was used from the above two papers*

