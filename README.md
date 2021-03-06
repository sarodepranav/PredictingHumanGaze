# Predicting Human Gaze Fixations using LSTM
This is the project we did during Senior year of our Bachelor's Degree (Electronics and Telecommunication Engineering). This Github repository features the code for training the LSTM-based saliency model for predicting human gaze fixations. The dataset used was SALICON - which is a benchmark dataset for saliency prediction projects. 
For any queries regarding the execution you can contact me on - sarodepranav@gmail.com

Model - 
https://colab.research.google.com/drive/1pF0GTBB4D6j0pbaN8oZhE4-NvSBaqFeF?usp=sharing

Sample Inputs to the trained model -
![image](https://user-images.githubusercontent.com/39979059/141194768-9f719398-36c2-4568-ab40-2fc02e9553b5.png)

Generated Saliency Maps for the given inputs -
![image](https://user-images.githubusercontent.com/39979059/141194863-e1f2d024-744b-493f-8ebf-fd7472c58c82.png)

Comparison of our model with other popular models - 
![image](https://user-images.githubusercontent.com/39979059/141195694-b21d16a5-6a97-4ea2-b2c7-5f1a64a93081.png)

An important point to note here is that we did not train our model on the MIT1003 dataset that is used by other saliency models to train in order to train and fine tune their
models for the benchmarking. As we can see from the table, our model has a significantly different value for KL Divergence on this benchmark owing to the reason
stated above and its mechanism as well, which considers the outputs as probability functions and gives less output only when the outputs are very similar.
