Demo codes for paper:                     
                         
# "Unsupervised Clustering of Seismic Signals Using Deep Convolutional Autoencoders"                    
                                                                               
--------------------------------------------------------            

    Mousavi, S. M., W. Zhu, W. Ellsworth, G. Beroza (2019). 
    Unsupervised Clustering of Seismic Signals Using Deep Convolutional Autoencoders, 
    IEEE Geoscience and Remote Sensing Letters, 1 - 5, doi:10.1109/LGRS.2019.2909218.                            
                             
(https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8704258)                 
                                                      
------------------------------------------------------       
BibTeX:      

    @article{mousavi2019unsupervised,
     title={Unsupervised Clustering of Seismic Signals Using Deep Convolutional Autoencoders},
     author={Mousavi, S Mostafa and Zhu, Weiqiang and Ellsworth, William and Beroza, Gregory},
     journal={IEEE Geoscience and Remote Sensing Letters},
     year={2019},
     publisher={IEEE}
    }        
                         
------------------------------------------------------
            
In this paper, we use deep neural networks for unsupervised
clustering of seismic data.We perform the clustering in a
feature space that is simultaneously optimized with the clustering
assignment, resulting in learned feature representations that
are effective for a specific clustering task. To demonstrate the
application of this method in seismic signal processing, we design
two different neural networks consisting primarily of full convolutional
and pooling layers and apply them to: (1) discriminate
waveforms recorded at different hypocentral distances and (2)
discriminate waveforms with different first-motion polarities. Our
method results in precisions that are comparable to those recently
achieved by supervised methods, but without the need for labeled
data, manual feature engineering, and large training sets. The
applications we present here can be used in standard singlesite
earthquake early warning systems to reduce the false alerts
on an individual station level. However, the presented technique
is general and suitable for a variety of applications including
quality control of the labeling and classification results of other     
supervised methods.

![network architecture](Fig_2.jpg)

Sampel data. a) and b) are two examples of the seismograms with different polarity of first motion.
c) and d) are examples of local and teleseismic waveforms respectively while e) and f) are the associated Short-Time Fourier transforms. 

![network architecture](Fig_1.jpg)

The architecture of fully convolutional autoencoder used in our study. 

![clustering results](Fig_3.jpg)

Clustering results. 

![embeded features](Fig_4.jpg)

Visualization of embeded features. 

![embeded features](FigSub_3.png)

![embeded features](FigSub_4.png)

