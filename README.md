# pneumonia-classification
A simple neural network to classify pneumonia on x-rays

X-ray images from http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5 <br>
Citation: Kermany, D. S., Goldbaum, M., Cai, W., Valentim, C. C. S., Liang, H., Baxter, S. L., McKeown, A., Yang, G., Wu, X., Yan, F., Dong, J., Prasadha, M. K., Pei, J., Ting, M. Y. L., Zhu, J., Li, C., Hewett, S., Dong, J., Ziyar, I., … Zhang, K. (2018). Identifying medical diagnoses and treatable diseases by image-based Deep Learning. Cell, 172(5). https://doi.org/10.1016/j.cell.2018.02.010 

### Summary of algorithm: <br>
This is a simple 4-layer NN that uses a linear forward prop step with ReLU activation functions for each hidden layer and a sigmoid activation function for the output layer. This allows for a highly accurate binary classification algorithm that allows the user to distinguish between pneumonia and normal X-rays

Accuracy on test set: 99.99999998% - Overfitting is a possibility 

- next step is to better tune the hyperparamters
