# quantgans

Implementation of Quant GANs: Deep Generation of Financial Time Series (https://arxiv.org/pdf/1907.06673.pdf)

This repository includes code:
* https://github.com/jmnel/neuralsort
* https://github.com/ICascha/QuantGANs-replication
* https://github.com/locuslab/TCN

The model was trained on Google Colab (https://colab.research.google.com/) with the usage of GPU. In notebook you may find:
* Installations and settings part with list of imported libraries.
* Data preprocessing part with functions for data transformation. You may use the main one for all the transformations (gaussianize).
* TCN Model training part with description of the model with list of classes (TemporalBlock, TemporalConvNet, Generator, Discriminator, TCNDataset). The model was trained for 200 epochs.
* Samples generation part with representation of the results. After passing the training part you may use sample_generation() function to generate new samples. 

