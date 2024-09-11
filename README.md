# Salat-Postures-Dataset
Annotated dataset of salat (islamic prayer) postures for object detection 

We have built the Salat Postures Dataset from a set of images of students and laboratory members performing different Salat positions using mobile phones, from various view angles and with different brightness conditions, especially captured for the purpose, complemented with images (and video frames) of people in prayer collected from the Internet. 

The total number of collected images is 1904 (file extensions: jpeg, jpg, png, PNG, mpo), which we manually labeled into four classes using rectangular bounding boxes. Each image is associated with an XML file with the same name, containing the class annotations and bounding box coordinates, following the Pascal VOC format. The four classes correspond to the four main positions in Islamic prayer:

- 'qiyam' (standing position): 624 instances
- 'ruku' (bowing position): 581 instances
- 'sitting'/'julus': 480 instances
- 'sujud'/'Sujud': 471 instances

Total instances: 2156

## Warning
You may need a preprocessing step to rename some class names, since classes 'sitting'/'julus', and 'sujud'/'Sujud' appear with two different names/spellings.

## Download

<table>
  <tr>
    <td><img src="https://github.com/riotu-lab/Salat-Postures-Dataset/blob/main/Sample-images-with-annotations/SittingMO56.jpg" height=312></td>
    <td><img src="https://github.com/riotu-lab/Salat-Postures-Dataset/blob/main/Sample-images-with-annotations/IMG-20191019-WA0062.jpg" height=312></td>
  </tr>
  <tr>
    <td><img src="https://github.com/riotu-lab/Salat-Postures-Dataset/blob/main/Sample-images-with-annotations/ck35uvh7g7ebz07481zjpedss.jpeg" height=420</td>
    <td><img src="https://github.com/riotu-lab/Salat-Postures-Dataset/blob/main/Sample-images-with-annotations/ck2oqgwn04qu60757lizr6lif.jpeg" height=420</td>
    
<!--     <td><img src="https://github.com/riotu-lab/Salat-Postures-Dataset/blob/main/Sample-images-with-annotations/sujud163.jpg" height=480></td> -->
  </tr>
 </table>


The folder [Sample-images-with-annotations](https://github.com/riotu-lab/Salat-Postures-Dataset/tree/main/Sample-images-with-annotations) contains a small sample of the images and XML annotations.
You can download the whole dataset from [here.](https://www.kaggle.com/datasets/riotulab/salat-postures)

## Reference
If you use this dataset in your research, please cite:

Koubâa, A., Ammar, A., Benjdira, B., Al-Hadid, A., Kawaf, B., Al-Yahri, S.A., Babiker, A., Assaf, K. and Ras, M.B., 2020, March. Activity Monitoring of Islamic Prayer (Salat) Postures using Deep Learning. In 2020 6th Conference on Data Science and Machine Learning Applications (CDMA) (pp. 106-111). IEEE.

Available on [arxiv](https://arxiv.org/abs/1911.04102).



