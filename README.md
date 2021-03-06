# CIFAR-10 via TensorFlow

## Install
```
sh install.sh
```

## Usage
```
python train.py
```

## Performance

| Name                    | Precision       |
|-------------------------|-----------------|
|Cifar10Classifier_01     | 83.11%          |
|Cifar10Classifier_02     | 87.00%          |
|Cifar10Classifier_03     | 87.25%          |
|Cifar10Classifier_04     | 87.67%          |
|Cifar10Classifier_05     | 87.17%          |
|Cifar10Classifier_06     | 86.74%          |
|Cifar10Classifier_07     | 86.17%          |

## Environment

| Name     | Description           |
|----------|-----------------------|
|GPU       | GeForce GTX TITAN X   |
|OS        | Ubuntu 16.04 LTS      |
|Library   | TensorFlow 0.8.0      |

## Network Architecture

### Cifar10Classifier_01
|Layer Type   | Parameters                          |
|-------------|-------------------------------------|
|input        | size:28x28, channels:1              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:128, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:256, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|linear       | channels: 1024                      |
|relu         |                                     |
|linear       | channels: 10                        |
|relu         |                                     |
|softmax      |                                     |

### Cifar10Classifier_02
|Layer Type   | Parameters                          |
|-------------|-------------------------------------|
|input        | size:28x28, channels:1              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:128, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:256, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|linear       | channels: 1024                      |
|relu         |                                     |
|dropout      | rate: 0.5                           |
|linear       | channels: 10                        |
|relu         |                                     |
|softmax      |                                     |

### Cifar10Classifier_03
|Layer Type   | Parameters                          |
|-------------|-------------------------------------|
|input        | size:28x28, channels:1              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|convolution  | kernel:3x3, channels:128, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:256, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|linear       | channels: 1024                      |
|relu         |                                     |
|dropout      | rate: 0.5                           |
|linear       | channels: 10                        |
|relu         |                                     |
|softmax      |                                     |

### Cifar10Classifier_04
|Layer Type   | Parameters                          |
|-------------|-------------------------------------|
|input        | size:28x28, channels:1              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|convolution  | kernel:3x3, channels:128, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:256, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|linear       | channels: 1024                      |
|relu         |                                     |
|dropout      | rate: 0.5                           |
|linear       | channels: 10                        |
|relu         |                                     |
|softmax      |                                     |

### Cifar10Classifier_05
|Layer Type   | Parameters                          |
|-------------|-------------------------------------|
|input        | size:28x28, channels:1              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|convolution  | kernel:3x3, channels:128, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:128, padding:1 |
|relu         |                                     |
|convolution  | kernel:3x3, channels:256, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|linear       | channels: 1024                      |
|relu         |                                     |
|dropout      | rate: 0.5                           |
|linear       | channels: 10                        |
|relu         |                                     |
|softmax      |                                     |

### Cifar10Classifier_06
|Layer Type   | Parameters                          |
|-------------|-------------------------------------|
|input        | size:28x28, channels:1              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|convolution  | kernel:3x3, channels:128, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:128, padding:1 |
|relu         |                                     |
|convolution  | kernel:3x3, channels:256, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|linear       | channels: 1024                      |
|relu         |                                     |
|dropout      | rate: 0.5                           |
|linear       | channels: 256                       |
|relu         |                                     |
|dropout      | rate: 0.5                           |
|linear       | channels: 10                        |
|relu         |                                     |
|softmax      |                                     |

### Cifar10Classifier_06
|Layer Type   | Parameters                          |
|-------------|-------------------------------------|
|input        | size:28x28, channels:1              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|normalizing  |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:64, padding:1  |
|relu         |                                     |
|convolution  | kernel:3x3, channels:128, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|convolution  | kernel:3x3, channels:128, padding:1 |
|relu         |                                     |
|normalizing  |                                     |
|convolution  | kernel:3x3, channels:256, padding:1 |
|relu         |                                     |
|max pooling  | kernel:2x2, strides: 2              |
|linear       | channels: 1024                      |
|relu         |                                     |
|normalizing  |                                     |
|dropout      | rate: 0.5                           |
|linear       | channels: 256                       |
|relu         |                                     |
|dropout      | rate: 0.5                           |
|linear       | channels: 10                        |
|relu         |                                     |
|softmax      |                                     |

## References
- [1]. He, Kaiming, et al. "Deep Residual Learning for Image Recognition." arXiv preprint arXiv:1512.03385 (2015).
