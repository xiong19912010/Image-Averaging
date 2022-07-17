# Image-Averaging
Dealing with Cryo-EM image is much more complicated than traditional one, because usually the SNR (signal to noise ratio) is below 0.1. Image averaging is a good way to increase the SNR. This code is designed for this purpose. Here, we consider the 3D orientation of particles (among each image). First we calcuate the roation matrix between two 3D vectors and do image roation in 3D and finally average the particles of interest. 
Example command:
```
Average.py image_average [particle_star_file] [image_folder]
``` 
<img width="283" alt="image" src="https://user-images.githubusercontent.com/94659159/179382234-b4ce7152-baed-4dba-b75b-c047efdfcc72.png">
