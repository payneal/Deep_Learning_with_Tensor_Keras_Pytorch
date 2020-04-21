# 1.1 Machine Learning, and AI Part 1

## Artifical Intelligence
* Goal: achieve General Intelligence

### 3 Categories of AI
* ANI: Artificial Narrow Intelligence
    * auto trading systems, driving cars, computer vision etc

* AGI: Artificial General Intelligence
    * recognize face, beat you at chess, all of above except just one algo that would preform well at all of abover.

* ASI: Artificial Super Intelligence
    * Algo that is more advance than a human. If AGI is possible then so is ASI.

## Machine Learning
* is a subset of ai, setting up software to recognize patterens. Cleveraly and manually processing raw inputs to extract features from data that jive well with data modeling algos. Linear regression, logistic regression, clustering algos, support vector machines, random forrect

* in traditional machine learning you feature engineer more than you model where as in Deep learning your Feature enginner less than you model

## Representation Learning
*  nothing more than a set of features that would describe concepts individually. We could even have representation of objects using their colours, shape and size and their feature. We could even represent images based on some values. Representation is what would help us differentiate between different concepts, and in turn would also help us find out similarities between them

## Artificial Neural Networks
* is a collection of artificial neurons arranged so that they can send and recieve information between each other
* data for ex ppl faces are feed in to one end of a atrifical neural network which processes data with the goal of processing the data in some way.

## Deep Learning
* is an artificial neural network with more than a few layers of artificial neurons 
* have a tolat of 5 or more layers of artificial neuros
* 1 input layers
* 3 or more hidden layers that learn representation
    * dense
    * convolutional
    * recurrent 
* output layer - reserved for predictions


# 1.2 Machine Learning, and Artificial Intelligence part 2

* Major task that deep learning is leverage for:
    * Machine vision: self driving cars, face taging, phone unlocking via face recognition via smart phone
        * revelant to any AI that is going to need to recognize objects by their apperance by a distance or navigate a real world enviroment

        * CNNs/ ConnNets/ Convolutional Netwroks = type of deelp learning arcitecture in machin vision applications
        * special type of machine vision that uses CNNS is GANs: Generative Adversarial Networks = capable of producing noval art , fake painnts of famous artis, etc


    * NLP: Vocie recognition, Machine translation, predictive character recognition. any ai that interactes with communication for example conplex response of questionss
        * LSTMs / Long shirt-term memory = has feedback connections. It can not only process single data points, but also entire sequences of data.

        * RNNs = A recurrent neural network (RNN) is a class of artificial neural networks where connections between nodes form a directed graph along a temporal sequence. This allows it to exhibit temporal dynamic behavior.

    * Reinforcement Learning 
        * supervised learning
            * have x and y , x = data, y = prediction
            * Goal: learn somfuntion that uses x to approximate y
            * Examples:
                * classifications _ predictiing categories
                    * handwritten digits
                    * movie-review sentiment
                * regression - predicting continious varible 
                    * sales of a product
                    * future price if an asset
        
        * unsupervised learning 
            * have x only -- no y labesl available
            * goal: learn hidden, underlying structure of data x
            * examples:
                * cluster by topic 
                * word vectors
                * GANS - Generative Adversarial networks

        * reinforcement learning are different supervised and unsupervised. They are problems in which we can have an agent take a sequence of actions in some environment. The agent could be a human or an algo. It could be playing a video game or driving a car 
        * primary difference between supervided and unsupervised is that the actions taken by the agent wheather playing a video game or driving a car that agents actions influcences the information provided back by the enviroment. The agent is constently recieveing feedback on the actions that it takes. 
    
    * Deep Reinforcement learning
        * the marriage of artificial neural network and reinformenet learning

# 1.3 A visual Introduction to Deep Learning -- part 1 
