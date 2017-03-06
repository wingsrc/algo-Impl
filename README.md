# Algorithm Implementations


 Done: 
 1. computational graph implementation inspired by Karpathy's blog post & cs231n: http://karpathy.github.io/neuralnets/
  * basic operations: *, +, sigmoid, max and softmaxCrossEntropyError
  * tological sort for the execution order
  * gradient descent (most basic, no learning)
  
TODO:
 1. Fix vector multiplication & run some tests 
 2. (optional improvement) 
    * Cost function parser (i.e. convert "W*x + b" -> <br/> g1 = multiplyGate(W, x) <br/> g2 = sumGate(g1, b))
 3. Different versions of SGD: 
    * SVRG (Johnson & Zhang, NIPS 2013)
    * Adaptive Learning Rate for Stochastic Variance Inference (Ranganath et al, JMLR 13)
    * Adam (Kingma & Lei Ba, ICLR 2015)
 4. RNN gate, GRU gate
