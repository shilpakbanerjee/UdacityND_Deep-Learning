# UdacityND_Deep-Learning
Udacity Nanodegree Capstone Project: Multiple digit recognition from google street view housing number data 

There are three python codes. We explain how to use these.
1. First one needs to download the three files train.tar.gz, test.tar.gz and extra.tar.gz from the SVHN dataset.
2. Then one runs 0-image-processor.pynb which creates the raw image folders train, test and extra. Next it creates
the processed image folders train processed, test processed and extra processed. Next it pickles the info into six
files: train processed.pickle, train processed labels.pickle, test processed.pickle, test processed labels.pickle,
extra processed.pickle and extra processed labels.pickle. This files are provided in the git repository.
3. Then one runs 0-SV HN -multi-digit-train which uses the six .pickle files listed above. The output is the model
model1.ckpt. This is provided in the git repository.
4. One can play with image prediction using model1.ckpt using the code 0-random-test.ipynb
