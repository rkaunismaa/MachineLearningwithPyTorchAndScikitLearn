# MachineLearningwithPyTorchAndScikitLearn
This is my walk through of the book 'Machine Learning with PyTorch and Scikit-Learn' by Sebastian Raschka



## Friday, March 3, 2023

I am trying to run the Reinforcement Learning example ch19.ipynb, but am running into conflicts with the version of python current in this 'cool_noether' docker container. So what I am going to try is to spin up a newer source image such as pt1131:20230216. Hmm looks like the container 'sad_nightingale' could work. 

OK. sad_nightingale uses python 3.10.0. 

## Sunday, February 5, 2023

Grabbed all the current code from https://github.com/rasbt/machine-learning-book 
and then replicated the first 11 chapters code and figures into this repo.

Then ran them through the local docker environment pt1121:20230205 ... They all run fine and do not use the GPU.

docker container start cool_noether