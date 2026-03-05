# Image Classification: Questions

Explore the code in file cnn-transferlearning-tutorial.ipynb and then try to answer the following questions:

## 1. What is the CNN architecture (model) used in the tutorial?

## 2. Why do you need to resize the input images to (224, 224)?

## 3. What is the batch size being used and what does this mean?

## 4. Where in the code can you find image augmentation and what does augmentation do?

## 5. Where in the code is the model trained from scratch and what line of code gives you this indication?

## 6. Name a convolutional layer, a batch normalization layer, and a pooling layer from the model?

## 7. What is dropout and where can you find it in the code?

## 8. Inside the function build_model how do you know if the model is used for transfer learning?

## 9. Inside the function build_model what is the top of the model replaced by?

## 10. What is the purpose of the function unfreeze_model?

## 11. Why is the learning rate for unfreeze_model lower than the one for build_model?

## 12. Why is the number of epochs for unfreeze_model lower than the one for build_model? 

## 13. Why do we set layer.trainable = True in unfreeze_model?

## 14. Why are the batch normalization layers not set to trainable?

## 15. What is the optimizer, the loss and performance metric used for all training phases?

