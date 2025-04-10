# Album Clustering

The goal of this project is to develop a model which is capable of generating and labeling albums from a set of photos provided by the user.
The BLIP model is used to processes the images and extract high level features.
An additional encoder layer is then trained to partition the space in a way conducive for HDBSCAN to cluster the given photos into clusters in a manner a human might.
The BLIP model is the used again to generate a title for the album to provide the user with an idea of the photos found in the ablum.

The [PETA](https://github.com/Alibaba-MIIL/PETA/tree/main) and [PEC](https://data.vision.ee.ethz.ch/cvl/datasets_extra/pec/) dataset were used for training the model.
