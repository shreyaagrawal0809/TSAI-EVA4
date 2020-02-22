# TSAI-EVA4

## Assignment 5:

### Code 1- BASIC SKELETON
* Link -> [https://github.com/shreyaagrawal0809/TSAI-EVA4/blob/master/s5/Model_S501.ipynb]

#### Target:
* Get the basic skeleton right

#### Results:
* Parameters: 194k
* Best Train Accuracy: 99.52
* Best Test Accuracy: 99.00 

#### Analysis:
* The model is still large, but working
* We see some over-fitting


### Code 2- LIGHTER MODEL
* Link -> [https://github.com/shreyaagrawal0809/TSAI-EVA4/blob/master/s5/Model_S502.ipynb]

#### Target:
* Make the model Lighter by reducing the number of parameter. 

#### Results:
* Parameters: 13.7k
* Best Train Accuracy: 99.06
* Best Test Accuracy: 98.63

#### Analysis:
* The model is still large, but working
* We see some over-fitting


### Code 3- BatchNorm and DropOut MODEL
* Link -> [https://github.com/shreyaagrawal0809/TSAI-EVA4/blob/master/s5/Model_S503.ipynb]

#### Target:
* Use BatchNorm to increase the efficiency
* Use Regularization(DrpOut) to remove over-fitting 

#### Results:
* Parameters: 13.8k
* Best Train Accuracy: 99.29
* Best Test Accuracy: 99.38 

#### Analysis:
* Good model!
* No over-fitting, model is capable if pushed further


### Code 4- GAP MODEL
* Link -> [https://github.com/shreyaagrawal0809/TSAI-EVA4/blob/master/s5/Model_S504.ipynb]

#### Target:
* Add GAP and remove the last BIG kernel.

#### Results:
* Parameters: 8.9k
* Best Train Accuracy: 98.78
* Best Test Accuracy: 99.01

#### Analysis:
* Good model!
* Since we have reduced model capacity, reduction in performance is expected

### #Code 5- Image Augmentation and LR Schedular MODEL
* Link -> [https://github.com/shreyaagrawal0809/TSAI-EVA4/blob/master/s5/Model_S505.ipynb]

#### Target:
* Apply Image augmentation (transforms.RandomRotation())
* Add LR Schedular

#### Results:
* Parameters: 9.7k
* Best Train Accuracy: 99.41
* Best Test Accuracy: 99.49

#### Analysis:
* Good model!
* No over-fitting

