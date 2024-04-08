# cultural-evo
A minimal implementation of simulation of "Reciprocal Construction of Mind and Environment". Torwards Neuro-Computational Cultural Evolution. 

We use RNN and VAE for the following reasons:

### Variational Autoencoder (VAE):
We can use a VAE to learn a latent representation of the cultural environment or the agent's experiences.
The VAE can encode the high-dimensional input data (e.g., cultural products, experiences) into a lower-dimensional latent space, capturing meaningful features and reducing dimensionality.
The latent space representation learned by the VAE can be used as input to the agent's decision-making process or as a basis for generating novel experiences.

### Recurrent Neural Network (RNN):
An RNN can be employed to model sequential dependencies in the agent's experiences over time.
By processing sequences of cultural products and rewards, the RNN can capture temporal dynamics and long-term dependencies in the agent's learning process.
The hidden states of the RNN can serve as a dynamic representation of the agent's cognitive state, influencing its decisions and actions in a context-dependent manner.
