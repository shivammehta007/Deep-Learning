# Deep-Learning
#### Assignments for Deep Learning Course

Task Descriptions are added in the Files Itself. 
   
Summary of Tasks: 

1. 
    * Prepare DL env
        * Install conda(Miniconda)/virtualenv
        * Install pandas, numpy, sklearn, matplotlib, tensorflow, Keras, etc
    * Run example (google keras mnist mlp example)
    * Encapsulate building of MLP in function
        * You need encapsulate only BUILDING and COMPILATION (not training)
        * Parameters to encapsulate: amount of layers, amount of units at each layer, activation function, loss function, optimizer.
        * Bonus: regularization (l1,l2,dropout)
    * Train MLP(read this tutorial properly, example) with hyperparameters search on train data. Evaluate model on the test data
        * Use accuracy score as main evaluation metric
        * Test 2,3,4-layer MLPs with different activation functions and optimizers (simple docs can be found at keras.io)
        * For hyperparameters search you can use:
            * GridSearch/RandomSearch from sklearn with KerasClassifier wrapper from keras
            * ParameterGrid from sklearn
            * Just ‘for’ (:

    * Add random normal noise to train and test data. Then, repeat step #3 on noisy data
    * Train Simple (Non convolutional) Denoising Autoencoder (read this tutorial properly) and reconstruct data from data with noise. Repeat step #3 on reconstructed data
    * Compare all results using table and plot. Be creative


2. 
    * Load Fashion MNIST from keras.datasets
        * Train MLP and Random Forest on Fashion MNIST
    * For MLP use parameters search via grid search or random search
        * Train CNN on Fashion MNIST with parameters search
    * Try to reach better performance than MLP

    * Train CNN autoencoder on Fashion MNIST with short parameters search
        * You should train AE using Cross-validation (not simple train/test split) and predict all data in CV manner
    * Train MLP and Random Forest on the latent vector from TRAINED CNN autoencoder
    * Compare all results using plot/plots


