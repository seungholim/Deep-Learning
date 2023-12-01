## Pytorch를 사용한 딥러닝

### 1.  Numpy

- 1D Array
- 2D Array
- Broadcasting
- 평균
- 합
- 최댓값/ArgMax

### 2.  Tensor VS Numpy

- Reshape
- Squeeze/Unsqueeze
- Type Casting
- Stacking

### 3.  optimizer

- Autograd
- 정적 그래프
- nn모듈

### 4.  Gradient Descent

- MSE(Mean Square Error)
- 경사하강

### 5.  Multivariate Linear Regression

### 6.  Logistic Regression

### 7.  Softmax Classification

- 이산확률분포
- Softmax
- Cross Entropy

### 8.  MNIST

- `Epoch`
  - 전체 데이터가 Training을 한번 끝냈을때, 1epoch
- `batch size` 
  - 전체 데이터를 효율적으로 잘라 학습시키기 위함
- `Iterations` 
  - batch를 몇번 학습에 사용했는가?? 1000개의 데이터를 500batch로 돌리면 2iterations을 학습에 사용했다고 함

### 9.  Single Layer

- XOR

### 10.  MultiLayer Layer

- 역전파 알고리즘

### 11.  ReLU

- f(x) = max(0,x)
- `vanishing gradient`
  - Backpropagation 과정에서 gradient를 앞단으로 전파 시킬때 activation function에서는 gradient를 곱하게 됩니다. 이때 아주 작은 값이 곱해지게 되면 뒷단에서 loss로부터 전파되는 gradient가 소멸되는 현상

### 12.  Weight Initialization

- `RBM`
  - 입력 x가 있을때 Y를 만들수 있는 foward가 존재하고, 반대로 Y가 들어왔을때 backward를 통해 x를 복원하는 x'이 가능한 구조
- Deep Belief Network

### 13.  Dropout

- 학습을 진행하면서 레이어에 존재하는 노드(뉴런)들을 설정된 비율에 따라 on/off 를 진행하는 것

- Overfitting

### 14.  Batch Normalization1

- Internal Covariate Shift

### 15.  Batch Normalization2

- 배치정규화 알고리즘

### 16.  CNN1

- `Convolution`
  - 이미지 위에서 stride 값 만큼 filter(kernel)을 이동시키면서 겹쳐지는 부분의 각 원소의 값을 곱해서 모두더한 값을 출력으로 하는 연산
- `Stride`
  - filter를 한번에 얼마나 이동할 것인가?
- `Pooling`
  - 이미지 사이즈를 줄이기 위해 이용하거나 , fully connected 연산을 대체하기 위해 사용

### 17.  CNN2

- MNIST_CNN

### 18.  CNN3

- Visdom
  - Text
  - Image
  - Images
  - Line plot

### 19.  CNN4

- 개/고양이 구별 학습

### 20.  RNN1

- `Hidden State`
  - output으로 몇개의 차원을 가진 벡터를 출력할지 결정하는 부분
- `Sequence Length`
  - input_data의 dimension의 갯수
- `Batch Size`
  - 여러개의 data를 하나의 batch로 묶어 학습이 가능

### 21.  RNN2

- `Cross Entropy Loss`
  - 카테고리컬한 output을 예측하는데 많이 쓰는 loss

### 22.  RNN3

- Longseq Example

### 23.  RNN4

- Time Series Data
