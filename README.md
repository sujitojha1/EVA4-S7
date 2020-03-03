# S7
EVA4 Assignment S7, TSAI


## Step 1

1.   Setup the code and define the baseline architecture.
2.   Set the device to GPU instead of CPU.
3.   Exploratory data to understand the data normalization and data augmentation.


### Results    

1.   Total parameters = 2,435,744
2.   For 2 epochs, Train Accuracy 63%
3.   For 2 epochs, Test Accuracy 62%

### Analysis   

1.  Not able to achieve target accuracy of 80% and parameters less than 1M.


## Step 2

1.   Set the image normalization and image augmentation

### Results .  

1.   Total parameters = 2,435,744
2.   For 2 epochs, Train Accuracy 60%
3.   For 2 epochs, Test Accuracy 62%

### Analysis   

1.  Accuracy didn't improve as we tried only for two epochs.


## Step 3

1.  Refining the architecture to meet parameter target < 1M

### Results  

1.   Total parameters = 1,092,768
2.   For 20 epochs, Train Accuracy 84%
3.   For 20 epochs, Test Accuracy 81%

### Analysis   

1.  Accuracy meets the target >80% but slightly over the parameter targets 1M.



## Steps 4

Implemented depth wise convolution and dilated layer. Even optimized parameter to meet target of 1M

### Results  

1.   Total parameters = 943,552
2.   For 20 epochs, Train Accuracy 82%
3.   For 20 epochs, Test Accuracy 81%


### Analysis   

1.  Results of accuracy is more than 80% and parameters target < 1M.
2.  Models is performing well also as gap between train and test accuracy is small.




