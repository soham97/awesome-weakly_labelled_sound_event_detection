# Reading List for topics in Weakly Labelled Sound Event Detection
By [Soham Deshmukh](https://soham97.github.io), master's candidate at Carnegie Mellon University in Electrical and Computer Engineering department.

Papers covering multiple sub-areas are listed in both the sections. If there are any areas, papers, and datasets I missed, please let me know!

## Table of Contents

* [Survey Papers](#survey-papers)
* [Core Areas](#core-areas)
  * [Learning formulation](#learning-formulation)
  * [Network architecture](#network-architecture)
  * [Pooling fuctions](#pooling-functions)
  * [Multimodal Translation](#multimodal-translation)
  * [Missing or noisy audio](#missing-or-noisy-audio)
  * [Intepretable Learning](#intepretable-learning)
  * [Generative Learning](#generative-learning)
  * [Representation Learning](#representation-learning)
  * [Multi-Task Learning](#multitask-learning)
  * [Adversarial Attacks](#adversarial-attacks)
  * [Few-Shot Learning](#few-shot-learning)
  * [Knowledge-transfer](#knowledge-transfer)
  * [Polyphonic SED](#polyphonic)
  * [Joint learning](#joint-task)
* [Extension](#applications-and-datasets)
  * [Multimodal Audio and Visual](#multimodal-audio-visual)
  * [Strongly and Weakly labelled audio data](#strong-weak)
  * [Healthcare](#healthcare)
  * [Robotics](#robotics)
* [Workshops](#workshops)
* [Tutorials](#tutorials)
* [Courses](#courses)



# Research Papers

## Core Areas

### Learning formulation
[Weakly supervised scalable audio content analysis](https://ieeexplore.ieee.org/abstract/document/7552989), ICME 2016

[Audio Event Detection using Weakly Labeled Data](https://dl.acm.org/doi/abs/10.1145/2964284.2964310), 24th ACM Multimedia Conference 2016

[An approach for self-training audio event detectors using web data](https://ieeexplore.ieee.org/abstract/document/8081532), 25th EUSIPCO 2017

[A joint detection-classification model for audio tagging of weakly labelled data](https://ieeexplore.ieee.org/abstract/document/7952234), ICASSP 2017

[Multi-Task Learning for Interpretable Weakly Labelled Sound Event Detection](https://arxiv.org/abs/2008.07085), ArXiv 2019

[A Sequential Self Teaching Approach for Improving Generalization in Sound Event Recognition](https://arxiv.org/abs/2007.00144), ICML 2020

[SeCoST:: Sequential Co-Supervision for Large Scale Weakly Labeled Audio Event Detection](https://ieeexplore.ieee.org/abstract/document/9053613), ICASSP 2020

[Guided Learning for Weakly-Labeled Semi-Supervised Sound Event Detection](https://ieeexplore.ieee.org/abstract/document/9053584), ICASSP 2020

### Network Architecture
[Weakly-supervised audio event detection using event-specific Gaussian filters and fully convolutional networks](https://ieeexplore.ieee.org/abstract/document/7952264), ICASSP 2017

[Deep CNN Framework for Audio Event Recognition using Weakly Labeled Web Data](https://arxiv.org/abs/1707.02530), NIPS Workshop on Machine Learning for Audio 2017
[https://arxiv.org/abs/1803.02353](https://arxiv.org/abs/1803.02353), DCASE 2018

[Large-Scale Weakly Supervised Audio Classification Using Gated Convolutional Neural Network](https://ieeexplore.ieee.org/abstract/document/8461975), ICASSP 2018

[Sound event detection and time–frequency segmentation from weakly labelled data](https://ieeexplore.ieee.org/abstract/document/8632940), TASLP 2019

[Attention-based Atrous Convolutional Neural Networks: Visualisation and Understanding Perspectives of Acoustic Scenes](https://ieeexplore.ieee.org/abstract/document/8683434), ICASSP 2019

[Sound Event Detection of Weakly Labelled Data With CNN-Transformer and Automatic Threshold Optimization](https://ieeexplore.ieee.org/abstract/document/9165887), TASLP 2020

[DD-CNN: Depthwise Disout Convolutional Neural Network for Low-complexity Acoustic Scene Classification](https://arxiv.org/abs/2007.12864), ArXiv 2020

[Weakly-Supervised Sound Event Detection with Self-Attention](https://ieeexplore.ieee.org/abstract/document/9053609), ICASSP 2020

### Pooling function
[Adaptive Pooling Operators for Weakly Labeled Sound Event Detection](https://dl.acm.org/doi/10.1109/TASLP.2018.2858559), TASLP 2018

[Comparing the Max and Noisy-Or Pooling Functions in Multiple Instance Learning for Weakly Supervised Sequence Learning Tasks](https://www.isca-speech.org/archive/Interspeech_2018/pdfs/0990.pdf), Interspeech 2018

[Weakly labelled audioset tagging with attention neural networks](https://ieeexplore.ieee.org/abstract/document/8777125), TASLP 2019

[Sound event detection and time–frequency segmentation from weakly labelled data](https://ieeexplore.ieee.org/abstract/document/8632940), TASLP 2019

[Multi-Task Learning for Interpretable Weakly Labelled Sound Event Detection](https://arxiv.org/abs/2008.07085), ArXiv 2019

### Multi-task learning
[Multi-Task Learning for Interpretable Weakly Labelled Sound Event Detection](https://arxiv.org/abs/2008.07085), ArXiv 2019

[Multi-Task Learning and post processing optimisation for sound event detection](http://dcase.community/documents/challenge2019/technical_reports/DCASE2019_Cances_69.pdf), DCASE 2019

### Knowledge Transfer
[Transfer learning of weakly labelled audio](https://ieeexplore.ieee.org/abstract/document/8169984), WASSPAA 2017

[Knowledge Transfer from Weakly Labeled Audio Using Convolutional Neural Network for Sound Events and Scenes](https://ieeexplore.ieee.org/abstract/document/8462200), ICASSP 2018

[PANNs: Large-Scale Pretrained Audio Neural Networks for Audio Pattern Recognition](https://ieeexplore.ieee.org/abstract/document/9229505), TASLP 2020

### Polyphonic SED
[Polyphonic Sound Event Detection and Localization using a Two-Stage Strategy](https://arxiv.org/abs/1905.00268), DCASE 2019

[Evaluation of Post-Processing Algorithms for Polyphonic Sound Event Detection](https://ieeexplore.ieee.org/abstract/document/8937143), WASPAA 2019

[An Improved Event-Independent Network for Polyphonic Sound Event Localization and Detection](https://arxiv.org/abs/2010.13092), ArXiv 2020

### Joint task
[A Joint Separation-Classification Model for Sound Event Detection of Weakly Labelled Data](https://ieeexplore.ieee.org/abstract/document/8462448), ICASSP 2018

[A Joint Framework for Audio Tagging and Weakly Supervised Acoustic Event Detection Using DenseNet with Global Average Pooling](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-8-7.pdf), INTERSPEECH 2020

## Extension

### Multimodal Audio and Visual
[Large Scale Audiovisual Learning of Sounds with Weakly Labeled Data](https://arxiv.org/abs/2006.01595), IJCAI 2020

### Strongly and Weakly Labelled data
[Audio event and scene recognition: A unified approach using strongly and weakly labeled data](https://ieeexplore.ieee.org/abstract/document/7966293), IJCNN 2017
