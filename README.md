# Image Captioning

We reimplemented the complicated [Google' Image Captioning](https://github.com/tensorflow/models/tree/master/im2txt) model by simple TensorLayer code.

### 1. Prepare MSCOCO data and Inception model
Before you run TensorLayer scripts, you need to follow Google's [setup guide]((https://github.com/tensorflow/models/tree/master/im2txt)). Then setup the model, ckpt and data directories in *.py.

- Creat a ``data`` folder.
- Download and Preprocessing MSCOCO Data [click here](https://github.com/zsdonghao/models/tree/master/im2txt#prepare-the-training-data)
- Download the Inception_V3 CKPT [click here](https://github.com/zsdonghao/models/tree/master/im2txt#download-the-inception-v3-checkpoint)


### 2. Train the model
- via ``train.py``

### 3. Evaluate the model
- via ``evaluate.py``

### 4. Generate captions by given image and model
- via ``run_inference.py``