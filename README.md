# CS7GV1 Midterm Assignment

## A - PCA for Image Reconstruction

The code developed for this question along with the answers to the questions can be found in the notebook `PCA.ipynb`. The code was run on Google Colab with the image being read from a folder in my Google Drive, so the code cell containing
```
from google.colab import drive
drive.mount('/content/drive')
```
doesn't need to be run, and the line `img = cv2.imread('/content/drive/My Drive/CV midterm/building.jpg')` should be changed to the path of the input image (which can be found in `images/S.jpg`).

The principal components were calculated both with numpy and with sklearn for comparison.

## B - Creative Project

For this part of the assignment I decided to do some experiments comparing convolutions applied in the spatial domain vs the frequency domain. All the relevant code and descriptions are in the notebook `Convolutions.ipynb`. Again the line `img = cv2.imread('/content/drive/My Drive/CV midterm/building.jpg')` should be changed to read in `images/S.jpg`.
