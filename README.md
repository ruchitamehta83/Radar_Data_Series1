Deep Learning Techniques for Radar-Based Continuous Human Activity Recognition

Abstract: 
Human capability to perform routine tasks declines with age and age-related problems. Remote human activity recognition (HAR) is beneficial for regular monitoring of the elderly population. This paper addresses the problem of the continuous detection of daily human activities using a mm-wave Doppler radar. In this study, two strategies have been employed: the first method uses un-equalized series of activities, whereas the second method utilizes a gradient-based strategy for equalization of the series of activities. The dynamic time warping (DTW) algorithm and Long Short-term Memory (LSTM) techniques have been implemented for the classification of un-equalized and equalized series of activities, respectively. The input for DTW was provided using three strategies. The first approach uses the pixel-level data of frames (UnSup-PLevel). In the other two strategies, a convolutional variational autoencoder (CVAE) is used to extract Un-Supervised Encoded features (UnSup-EnLevel) and Supervised Encoded features (Sup-EnLevel) from the series of Doppler frames. The second approach for equalized data series involves the application of four distinct feature extraction methods: i.e., convolutional neural networks (CNN), supervised and unsupervised CVAE, and principal component Analysis (PCA). The extracted features were considered as an input to the LSTM. This paper presents a comparative analysis of a novel supervised feature extraction pipeline, employing Sup-ENLevel-DTW and Sup-EnLevel-LSTM, against several state-of-the-art unsupervised methods, including UnSUp-EnLevel-DTW, UnSup-EnLevel-LSTM, CNN-LSTM, and PCA-LSTM. The results demonstrate the superiority of the Sup-EnLevel-LSTM strategy. However, the UnSup-PLevel strategy worked surprisingly well without using annotations and frame equalization.

To use the dataset, please cite our following work.


@article{mehta2023deep,
  title={Deep Learning Techniques for Radar-Based Continuous Human Activity Recognition},
  author={Mehta, Ruchita and Sharifzadeh, Sara and Palade, Vasile and Tan, Bo and Daneshkhah, Alireza and Karayaneva, Yordanka},
  journal={Machine Learning and Knowledge Extraction},
  volume={5},
  number={4},
  pages={1493--1518},
  year={2023},
  publisher={Multidisciplinary Digital Publishing Institute}
}
