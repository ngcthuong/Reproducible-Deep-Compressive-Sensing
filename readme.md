# Reproducible Deep Compressive Sensing 
Collection of source code for deep learning-based compressive sensing (DCS). Links for source code, pdf, doi are available. 
Related works are classified based on the sampling matrix type (frame-based/block-based), sampling scale (single scale, multi-scale), and deep learning platform. 


## Block-based DCS
### Single-Scale Sensing
* ISTA-Net [[Code]](https://github.com/jianzhangcs/ISTA-Net) [[PDF]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_ISTA-Net_Interpretable_Optimization-Inspired_CVPR_2018_paper.pdf) [Tensorflow]
  * Z. Jian and G. Bernard, "ISTA-Net: Interpretable Optimization-Inspired Deep Network for Image Compressive Sensing", IEEE International Conference on Computer Vision and Pattern Recognition, 2018. 

* CSNet [[Code]](https://github.com/wzhshi/CSNet) [[Code-Train]](https://github.com/AtenaKid/CSNet) [[PDF]](https://arxiv.org/abs/1707.07119) [[DOI]](https://doi.org/10.1109/ICME.2017.8019428) [Matconvnet]
  * W. Shi, F. Jaing, S. Zhang, and D. Zhao, "Deep networks for compressed image sensing", IEEE International Conference on Multimedia and Expo (ICME), 2017.   
  
* DBCS [[Code]](http://www.cs.technion.ac.il/~adleram/BCS_DNN_2016.zip) [[PDF]](https://arxiv.org/pdf/1606.01519.pdf) [[DOI]](https://doi.org/10.1109/MMSP.2017.8122281) [Matlab]
  * A. Adler, D.Boublil, and M. Zibulevsky, "Block-based compressed sensing of images via deep learning,", IEEE International Workshop on Multimedia Signal Processing (MMSP), 2017.

* DR2Net [[Code]](https://github.com/coldrainyht/caffe_dr2) [[Code]](https://github.com/AtenaKid/Caffe-DCS) [[PDF]](https://arxiv.org/abs/1702.05743) [Caffe]
  * H. Yao, F. Dai, D. Zhang, Y. Ma, S. Zhang, Y. Zhang, and Q. Tian, "DR2-net: Deep residual reconstruction network for image compressive sensing", arXiv:1702.05743, 2017. 

* CS-CAE [[Code]](https://github.com/stes/compressed_sensing/tree/master/code) [[PDF]](https://github.com/stes/compressed_sensing/blob/master/report/report.pdf) [Theanos]
  * S. Schneider, "A deep learning approach to compressive sensing with convolutional autoencoders," tech. report, 2016. 

* ReconNet [[Code]](https://github.com/KuldeepKulkarni/ReconNet) [[Code]](https://github.com/AtenaKid/Caffe-DCS) [[PDF]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Kulkarni_ReconNet_Non-Iterative_Reconstruction_CVPR_2016_paper.pdf) [[DOI]](https://doi.org/10.1109/CVPR.2016.55) [Caffe]
  * K. Kulkarni, S. Lohi, P. Turaga, R. Kerviche, A. Ashok, "ReconNet: Non-Iterative Reconstruction of Images from Compressively Sensed
Measurements," IEEE International Conference on Computer Vision and Pattern Recognition (CVPR), 2016. 

### Multi-Scale Sensing
* DCSNet [[Code]](https://github.com/AtenaKid/MS-DCSNet-Release) [[PDF]](https://arxiv.org/abs/1809.05717) [MatcovnNet]
  * T. N. Canh and B. Jeon, "Multi-Scale Deep Compressive Sensing Network," IEEE International Conference on Visual Communication and Imave Processing (VCIP), 2018.
  
* MS-CSNet [[Code]](https://github.com/wzhshi/MS-CSNet) [[DOI]](https://doi.org/10.1109/ICIP.2018.8451352) [MatconvNet]
  * W. Shi, F. Jiang, S. Liu, D. Zhao, "Multi-Scale Deep Networks for Image Compressed Sensing," IEEE International Conference on Image Processing (ICIP), 2018. 

## Frame-based DCS

* KCS-Net [[Code]](https://github.com/AtenaKid/KCS-Net) [[PDF]](https://www.researchgate.net/publication/324969818_Deep_Learning-Based_Kronecker_Compressive_Imaging) [MatconvNet]
  * T. N. Canh and B. Jeon, "Deep Learning-Based Kronecker Compressive Imaging", IEEE International Conference on Consumer Electronic Asia, 2018

* DAGAN [[Code]](https://github.com/nebulaV/DAGAN) [[PDF]](http://discovery.ucl.ac.uk/10048154/1/08233175.pdf) [[DOI]](https://doi.org/10.1109/TMI.2017.2785879) [Tensorflow]
  * G. Yang et al., "DAGAN: Deep De-Aliasing Generative Adversarial Networks for Fast Compressed Sensing MRI Reconstruction," IEEE Transaction on Medical Imaging, vol. 37, no. 6, 2018. 

* DeepVideoCS [[Web]](http://users.eecs.northwestern.edu/~mif365/deep_cs_project.html) [[Code]](https://github.com/miliadis/DeepVideoCS) [[PDF]](http://users.eecs.northwestern.edu/~mif365/papers/Deep_Video_CS.pdf) [[DOI]](https://doi.org/10.1016/j.dsp.2017.09.010) [PyTorch]
  * M. Illiasdis, L. Spinoulas, A. K. Katsaggelos, "Deep fully-connected networks for video compressive sensing," Elsevier Digital Signal Processing, vol. 72, 2018.  

* Deep-Ternary [[Code]](https://github.com/nmduc/deep-ternary) [[PDF]](https://arxiv.org/abs/1708.08311) [Tensorflow] 
  * D. M. Nguyen, E. Tsiligianni and N. Deligiannis, "Deep learning sparse ternary projections for compressed sensing of images," IEEE Global Conference on Signal and Information Processing (GlobalSIP), 2017.

* GANCS [[Code]](https://github.com/gongenhao/GANCS) [[PDF]](htps://arxiv.org/abs/1706.00051) [Tensorflow]
  * M. Mardani et al., "Compressed Sensing MRI based on Deep Generative Adversarial Network", arXiv:1706.00051, 2017.

## Other 

* US-CS [[Code]](https://github.com/dperdios/us-rawdata-sda) [[PDF]](https://infoscience.epfl.ch/record/230991/files/ius2017_sda_preprint.pdf) [[DOI]](https://doi.org/10.1109/ULTSYM.2017.8092746) [Tensorflow]
  * D. Perdios, A. Besson, M. Arditi, and J. Thiran, "A Deep Learning Approach to Ultrasound Image Recovery", IEEE International Ultranosics Symposium, 2017. 
  
* LSTM_CS [[Code]](https://github.com/Palang2014/Distributed-Compressive-Sensing-A-Deep-Learning-Approach) [[PDF]](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/02/LSTM_CS_TSP.pdf) [[DOI]](https://doi.org/10.110910.1109/TSP.2016.2557301) [Matlab]
  * H. Palangi, R. Ward, and L. Deng, "Distributed Compressive Sensing: A Deep Learning Approach," IEEE Transaction on Signal Processing, vol. 64, no. 17, 2016.
  

  


