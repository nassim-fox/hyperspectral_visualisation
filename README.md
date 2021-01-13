# hyperspectral_visualisation

## About

This notebook contains algorithms for hyperspectral data preprocessing and initialization before machine learning or deep learning classification of the image. 

## Data

The dataset used is [Indian Pines](http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes#Indian_Pines)

The image was gathered by AVIRIS sensor over the Indian Pines test site in North-western Indiana and consists of 145\times145 pixels and 224 spectral reflectance bands in the wavelength range 0.4–2.5 10^(-6) meters. the image used contains 200 spectral bands where bands covering the region of water absorption were removed. 

The data is downloaded directly through the code, thus you will need internet connectivity when running it. Or you can change it and download manually the dataset. 

 ```sh
   !wget http://www.ehu.eus/ccwintco/uploads/c/c4/Indian_pines_gt.mat
   !wget http://www.ehu.eus/ccwintco/uploads/6/67/Indian_pines_corrected.mat
   
   ```
   

