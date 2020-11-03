# Self Driving-Tensorflow 2.3
Thanks to Sully Chen for the autopilot dataset. https://github.com/SullyChen/driving-datasets
The approach to predict steering angle using CNN is based on paper "End to End Learning for Self-Driving Cars" from Nvidia in 2016 https://arxiv.org/pdf/1604.07316.pdf

### What makes this Selfdriving project better then others.

- [x] Interactive Colab Notebook which any one can try.
- [x] Based on latest Tensorflow 2. 
- [x] Dataset augmentation to balance the labels.
- [x] Loading Dataset of around 20k images into memory to perform quick training.
- [x] With whole dataset into memory enhance performance using caching or pre-loading (prefetch)

- [ ] Plot Histogrom with converting tensorflow dataset into numpy to save time.
- [ ] Use Large dataset with tfrecord format and shards (distribute shards among multiple workers).
- [ ] Use the image preprocessing functions from tensorflow instead of tf.py_function() which is slow and doesn't use GPU.


