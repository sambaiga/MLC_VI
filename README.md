

# Convolutional Neural Network-based Multilabel Learning for  Appliance Recognition  Applying Frze-Current Decomposition and Euclidean distance similarity matrix.

This repository is the official implementation of [Convolutional Neural Network-based Multilabel Learning for  Appliance Recognition  Applying Frze-Current Decomposition and Euclidean distance similarity matrix](). 

<img src="block.png" width="80%" height="50%">


## Requirements

- python
- numpy
- scipy
- pandas
- matplotlib
- tqdm
- torch
- sklearn
- seaborn
- [iterstrat]
- [skmultilearn]()
- joblib
- [palettable]
  


## Training

To train the model(s) in the paper, run this command in src directory:

```train
python multilabel.py
```


## Evaluation

The script used to analyse results and produce visualisation presented in this paper can be found in notebook directory
 
 - Results and Error Analysis notebook provide scripts for results and error analysis.
 - Visualisation paper notebook provide scripts for reproducing most of the figure used in this paper.


## Results

Our model achieves the following performance on PLAID 2020 version dataset :

### [Image Classification on ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet)

| Model name         | V-I binary image  | Proposed approach |
| ------------------ |---------------- | -------------- |
| MLkNN  model |     85%         |      95%       |
| Proposed CNN model  |     85%         |      0.94±0.015       |



## Contributing
