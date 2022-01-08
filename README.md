# Tensorflow 2 Captcha Reader
Download dataset [here](https://drive.google.com/file/d/1mHfyM6idetIO0SO-7Aph1opWbveSeDD-/view?usp=sharing)

## Data preprocessing
- Training set: 100000 labeled captchas.
- Validation set: 20000 labeled captchas.
- Testing set: 20000 unlabeled captchas.
- All captchas are resized to 50 x 100.

## Encoder
Convolutional Neural Network encodes captcha images into simpler representation.

## Decoder
Output from attention layer is fed into GRU cells followed by FC layers to convert encoded captchas into strings.
