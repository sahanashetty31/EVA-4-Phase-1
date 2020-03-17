
### Session 4 ###

1. Less than 20k Parameters
2. 20 Epochs


## Model Summary ##

----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1            [-1, 8, 26, 26]              72
           Dropout-2            [-1, 8, 26, 26]               0
       BatchNorm2d-3            [-1, 8, 26, 26]              16
            Conv2d-4            [-1, 8, 24, 24]             576
           Dropout-5            [-1, 8, 24, 24]               0
       BatchNorm2d-6            [-1, 8, 24, 24]              16
            Conv2d-7            [-1, 8, 22, 22]             576
           Dropout-8            [-1, 8, 22, 22]               0
       BatchNorm2d-9            [-1, 8, 22, 22]              16
           Conv2d-10            [-1, 8, 20, 20]             576
          Dropout-11            [-1, 8, 20, 20]               0
      BatchNorm2d-12            [-1, 8, 20, 20]              16
        MaxPool2d-13            [-1, 8, 10, 10]               0
           Conv2d-14             [-1, 16, 8, 8]           1,152
          Dropout-15             [-1, 16, 8, 8]               0
      BatchNorm2d-16             [-1, 16, 8, 8]              32
           Conv2d-17             [-1, 16, 6, 6]           2,304
          Dropout-18             [-1, 16, 6, 6]               0
      BatchNorm2d-19             [-1, 16, 6, 6]              32
           Conv2d-20             [-1, 16, 4, 4]           2,304
          Dropout-21             [-1, 16, 4, 4]               0
      BatchNorm2d-22             [-1, 16, 4, 4]              32
           Conv2d-23             [-1, 16, 2, 2]           2,304
          Dropout-24             [-1, 16, 2, 2]               0
      BatchNorm2d-25             [-1, 16, 2, 2]              32
           Conv2d-26             [-1, 10, 2, 2]             160
================================================================
Total params: 10,216
Trainable params: 10,216
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.00
Forward/backward pass size (MB): 0.44
Params size (MB): 0.04
Estimated Total Size (MB): 0.48
----------------------------------------------------------------





## Epoch Logs ##

Epoch: 0

loss=0.11730813980102539 batch_id=1874
100% 1875/1875 [01:33<00:00, 19.98it/s]

/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:62: UserWarning: Implicit dimension choice for log_softmax has been deprecated. Change the call to include dim=X as an argument.

Train set: Average loss: 0.2072, Accuracy: 56659/60000 (94.43%)
Test set: Average loss: 0.0602, Accuracy: 9802/10000 (98.02%)

Epoch: 1

loss=0.010974154807627201 batch_id=1874
100% 1875/1875 [01:35<00:00, 19.63it/s]

Train set: Average loss: 0.0681, Accuracy: 58792/60000 (97.99%)
Test set: Average loss: 0.0384, Accuracy: 9886/10000 (98.86%)

Epoch: 2

loss=0.008211956359446049 batch_id=1874
100% 1875/1875 [01:32<00:00, 20.85it/s]

Train set: Average loss: 0.0579, Accuracy: 58922/60000 (98.20%)
Test set: Average loss: 0.0341, Accuracy: 9886/10000 (98.86%)

Epoch: 3

loss=0.1703336238861084 batch_id=1874
100% 1875/1875 [01:31<00:00, 20.49it/s]

Train set: Average loss: 0.0465, Accuracy: 59140/60000 (98.57%)
Test set: Average loss: 0.0284, Accuracy: 9907/10000 (99.07%)

Epoch: 4

loss=0.01870514452457428 batch_id=1874
100% 1875/1875 [01:31<00:00, 19.48it/s]

Train set: Average loss: 0.0412, Accuracy: 59243/60000 (98.74%)
Test set: Average loss: 0.0253, Accuracy: 9917/10000 (99.17%)

Epoch: 5

loss=0.003956781234592199 batch_id=1874
100% 1875/1875 [01:33<00:00, 19.14it/s]

Train set: Average loss: 0.0414, Accuracy: 59257/60000 (98.76%)
Test set: Average loss: 0.0237, Accuracy: 9923/10000 (99.23%)

Epoch: 6

loss=0.009605525061488152 batch_id=1874
100% 1875/1875 [01:32<00:00, 20.21it/s]

Train set: Average loss: 0.0364, Accuracy: 59333/60000 (98.89%)
Test set: Average loss: 0.0244, Accuracy: 9916/10000 (99.16%)

Epoch: 7

loss=0.0019196199718862772 batch_id=1874
100% 1875/1875 [01:33<00:00, 20.12it/s]

Train set: Average loss: 0.0347, Accuracy: 59339/60000 (98.90%)
Test set: Average loss: 0.0220, Accuracy: 9930/10000 (99.30%)

Epoch: 8

loss=0.001221265411004424 batch_id=1874
100% 1875/1875 [01:32<00:00, 20.21it/s]

Train set: Average loss: 0.0311, Accuracy: 59435/60000 (99.06%)
Test set: Average loss: 0.0225, Accuracy: 9929/10000 (99.29%)

Epoch: 9

loss=0.004743689671158791 batch_id=1874
100% 1875/1875 [01:32<00:00, 20.31it/s]

Train set: Average loss: 0.0295, Accuracy: 59454/60000 (99.09%)
Test set: Average loss: 0.0216, Accuracy: 9934/10000 (99.34%)

Epoch: 10

loss=0.002096405951306224 batch_id=1874
100% 1875/1875 [01:31<00:00, 20.41it/s]

Train set: Average loss: 0.0297, Accuracy: 59437/60000 (99.06%)
Test set: Average loss: 0.0202, Accuracy: 9935/10000 (99.35%)

Epoch: 11

loss=0.015717243775725365 batch_id=1874
100% 1875/1875 [01:34<00:00, 19.82it/s]

Train set: Average loss: 0.0287, Accuracy: 59481/60000 (99.14%)
Test set: Average loss: 0.0208, Accuracy: 9930/10000 (99.30%)

Epoch: 12

loss=0.001748309121467173 batch_id=1874
100% 1875/1875 [01:34<00:00, 19.40it/s]

Train set: Average loss: 0.0264, Accuracy: 59516/60000 (99.19%)
Test set: Average loss: 0.0193, Accuracy: 9933/10000 (99.33%)

Epoch: 13

loss=0.0011130607454106212 batch_id=1874
100% 1875/1875 [01:32<00:00, 20.56it/s]

Train set: Average loss: 0.0257, Accuracy: 59505/60000 (99.17%)
Test set: Average loss: 0.0221, Accuracy: 9932/10000 (99.32%)

Epoch: 14

loss=0.008540109731256962 batch_id=1874
100% 1875/1875 [01:32<00:00, 20.18it/s]

Train set: Average loss: 0.0244, Accuracy: 59539/60000 (99.23%)
Test set: Average loss: 0.0227, Accuracy: 9931/10000 (99.31%)

Epoch: 15

loss=0.03517695888876915 batch_id=1874
100% 1875/1875 [01:32<00:00, 20.38it/s]

Train set: Average loss: 0.0245, Accuracy: 59537/60000 (99.23%)
Test set: Average loss: 0.0204, Accuracy: 9930/10000 (99.30%)

Epoch: 16

loss=0.016543760895729065 batch_id=1874
100% 1875/1875 [01:32<00:00, 20.21it/s]

Train set: Average loss: 0.0230, Accuracy: 59585/60000 (99.31%)
Test set: Average loss: 0.0234, Accuracy: 9933/10000 (99.33%)

Epoch: 17

loss=0.0019785913173109293 batch_id=1874
100% 1875/1875 [01:32<00:00, 20.32it/s]

Train set: Average loss: 0.0229, Accuracy: 59555/60000 (99.26%)
Test set: Average loss: 0.0230, Accuracy: 9927/10000 (99.27%)

Epoch: 18

loss=0.023985959589481354 batch_id=1874
100% 1875/1875 [01:30<00:00, 20.94it/s]

Train set: Average loss: 0.0216, Accuracy: 59579/60000 (99.30%)
Test set: Average loss: 0.0209, Accuracy: 9929/10000 (99.29%)

Epoch: 19

loss=0.0016448061214759946 batch_id=1874
100% 1875/1875 [01:30<00:00, 20.62it/s]

Train set: Average loss: 0.0210, Accuracy: 59602/60000 (99.34%)
Test set: Average loss: 0.0215, Accuracy: 9931/10000 (99.31%)
