schoolOfAI_EVA8
The repository would contain various assignments and tasks done as part of EVA8 course at the school of AI.

-----------------------------------------------------------------------------------------------------------
At EVA 2.5 assignment, we would be given an image from MNIST handwritten digits grayscale image set and a random number. 
We would have to predict the summation of the two numbers.
We have built two input neural network that takes an image and a random number generated between 0 and 9.
We have used gpu accelerated training to quickly train the model and provide results.

-----------------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------------------------------------------
Initially I have considered two input one output case, but later I re-checked and found, two outputs are to be required.
Hence uploaded a new file with two output case, and in additional, we are printing loss in every 20 epochs.

Training Log - 

epoch 0 loss: 8819.445842266083
epoch 20 loss: 8652.41888666153
epoch 40 loss: 8663.875659942627
epoch 60 loss: 8676.743039608002
epoch 80 loss: 8708.55082321167
epoch 100 loss: 8702.191983222961
epoch 120 loss: 8703.95646905899
epoch 140 loss: 8699.741447925568
epoch 160 loss: 8699.91216993332
epoch 180 loss: 8701.500436782837

We are printing after every 20 epochs.
Further optimizations I feel is to remove relu from middle layers, as otherwise its filtering out negative values.

-----------------------------------------------------------------------------------------------------------
