# CTScan

This repository is created for the project of Medical Imaging Systems lecture in Karadeniz Technical University. 
- CTScan project is developed for realizing an example of ctscan algorithm. The effects of filters and normalizing were examined. 
- shepp_logan_phantom is used as a data image. Also another example image is used. 

#### The algorithm steps are as follows:
- Generate the data
- Create a sinogram image by transforming radon with 180 different angles
- Cartesian coordinate system image
- Conversion of synogram from time space to frequency space by Fourier Transform
- Image with Polar coordinate system
- Improve the image with filters
- Retrieval phase back into time space with inverse fouirer
- Reverse radon removal
- CTScan result image

#### Here is the result of shepp_logan_phantom image:

|   | Filter         | Normalization | Error |
|:-:|:--------------:|:-------------:|:------:|
|0  |None            |None           |0.000942|
|1  |Ramp            |None           |0.007812|
|2  |Cosine          |None           |0.017747|
|3  |Cutoff Frequency|None           |0.000942|
|4  |None            |Normalizing    |0.002619|
|5  |Ramp            |Normalizing    |0.002126|
|6  |Cosine          |Normalizing    |0.015000|
|7  |Cutoff Frequency|Normalizing    |0.002619|

## input shepp_logan_phantom image
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/inputimage.png?raw=true)
#### sinogram result
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/sinogram.png?raw=true)
#### fft result
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/fft2result.png?raw=true)

#### result of none filter
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/none.png?raw=true)
#### result of ramp filter
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/ramp.png?raw=true)
#### result of cosine filter
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/cosine.png?raw=true)
#### result of cutoff filter
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/cutoff.png?raw=true)

## Here is the result of example image:
|   | Filter         | Normalization | Error |
|:-:|:--------------:|:-------------:|:------:|
|0  |None            |None           |0.000469|
|1  |Ramp            |None           |0.008420|
|2  |Cosine          |None           |0.023362|
|3  |Cutoff Frequency|None           |0.000469|
|4  |None            |Normalizing    |0.001452|
|5  |Ramp            |Normalizing    |0.001282|
|6  |Cosine          |Normalizing    |0.005430|
|7  |Cutoff Frequency|Normalizing    |0.001452|

#### input example image
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/inputimage1.png?raw=true)
#### sinogram result
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/sinogram1.png?raw=true)
#### fft result
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/fft2result1.png?raw=true)

#### result of none filter
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/none1.png?raw=true)
#### result of ramp filter
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/ramp1.png?raw=true)
#### result of cosine filter
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/cosine1.png?raw=true)
#### result of cutoff filter
![alt text](https://github.com/rai-shi/CTScan/blob/main/image/cutoff1.png?raw=true)



#### Contact Information
For any inquiries or feedback, please contact: aysenurtak1@gmail.com
