Machine Learning Research Lab
University of Koblenz-Landau
Finding Required Change in Input to Alter Classification Decision by Interpreting ANN

Contributors: Usama Mazhar, Daniyal Saleem, Syed Saad Ahmed, Faizan Khan

Abstract
Machine learning techniques such as deep neural networks have now become a vital and important tool in vast varieties of application such as image classification, speech recognition, and natural language processing. Although these techniques achieve extremely high predictive accuracy, it is still difficult for human beings to understand and interpret the decisions made by Deep Neural Network models. Previous work focuses on understanding and interpreting the cause of a decision made by an ANN model by determining relevance score of individual inputs. In this research, we aim to use neuron-wise decomposition [6] on an already trained ANN model using Taylor Decomposition and find out which input values would need to be altered in a sample input image in order to alter the decision of the given ANN model. In simple words, the aim is to find out how close was the given trained model to give a different result? We used MNIST digits dataset which consists of images representing handwritten digits of size 28×28 in black and white color along with their labels (digits from 0 to 9). We used Taylor Decomposition to back propagate the target digit based on the percentage of contribution of the individual neurons. Our method achieved an average accuracy of 62.44%.

Keywords
Understanding Machine Learning Models, Taylor Decomposition, Artificial Neural Networks, Keras, Tensorflow
