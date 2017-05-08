# __LeNet-MNIS__
## __Issue__
Reprinting the original LeNet proposed in [1998_Gradient-Based Learning Applied to Document Recognition](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf) for understanding and practicing LeNet mechanism.
## __LeNet-5 Mechanism__
![LeNet mechanism](https://github.com/nightheronry/LeNet5-MNIS/blob/master/asset/LeNet.png)
## __Project File Structure__
![MyLeNet](https://github.com/nightheronry/LeNet5-MNIS/blob/master/asset/mylenet.png)

|LeNet-5 Mechanism|Layer Types|Project File|
|---|---|---|
|Input: 32x32<br />C1: 6@28x28|Convolution Layer<br />ReLU layer|MNIS-Convolution.ipynb<br />ActFunc.ipynb|
|C1: 6@28x28<br />S2: 6@14x14|Pooling layer|Pooling.ipynb|
|C3: 16@10x10|Convolution Layer<br />ReLU layer|MNIS-Convolution.ipynb<br />ActFunc.ipynb|
|S4: 16@5x5|Pooling layer|Pooling.ipynb|
|C5: 120|Convolution Layer<br />ReLU layer|MNIS-Convolution.ipynb<br />ActFunc.ipynb|
|F6: 84|Fully connected layer||
|F7: 10|Loss layer||

## __References__
[1][A Beginner's Guide To Understanding Convolutional Neural Networks](https://adeshpande3.github.io/adeshpande3.github.io/A-Beginner's-Guide-To-Understanding-Convolutional-Neural-Networks/)

[2][1998_Gradient-Based Learning Applied to Document Recognition](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf)

[3][MNIST handwritten digit database, Yann LeCun, Corinna Cortes and Chris Burges](http://yann.lecun.com/exdb/mnist/)

[4][Tutorial on Convolutions](http://torch.ch/torch3/matos/convolutions.pdf)
