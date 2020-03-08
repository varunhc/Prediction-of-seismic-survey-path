# GAN
<h2>Background:</h2>
ONGC carries out seismic survey before carrying out drilling activities in a new location.
The path used for this seismic survey is crucial since it will be used in the project’s further
activities.
My work was to predict this path based on the paths that were chosen in the previous
projects. If the model successfully predicts the paths, then it would be a huge aid to the
geophysicists working on the project.
<h2>Dataset:</h2>
Satellite images with seismic survey paths marked were used as input. They were cropped down to the dimension of 66x66 with 3 channels ie RGB.
[Input](images/WSHP16-04(1).jpg)
[Expected output](images/SHP16-04(1).jpg)
<h2>Approach:</h2>
Convolutional models and Generative Adversarial Networks(GANs) were implemented to check the prediction performance.
<h3>Convolution:</h3>
Convolutional models with different architectures were implemented.
Files: [satimgconv.py](Convolution/satimgconv.py), [SatImgConv.ipynb](Convolution/SatImgConv.ipynb)
<h3>GAN:</h3>
Generative Adversarial network was implemented which is available in the files: [satimggan.py](GAN/satimggan.py), [SatImgGAN.ipynb](GAN/SatImgGAN.ipynb)
<h2>Results:</h2>
Convolution: Training accuracy - 67.34%
GAN: Training accuracy - 67.34%
