# TensorFlow.js Example: Training on Open and Closed Eyes

This example shows you how to train Tensorflow on (eye_images)[http://parnec.nuaa.edu.cn/xtan/data/ClosedEyeDatabases.html].

This model will compute accuracy over 1000 random test set examples every 5
steps, plotting loss and accuracy as the model is training. Training time can
be reduced by computing accuracy over fewer examples less often.

Note: currently the entire dataset of MNIST images is stored in a PNG image we have
sprited, and the code in `data.js` is responsible for converting it into
`Tensor`s. This will become much simpler in the near future.

To run this on local server run 
`yarn`
`yarn watch`
