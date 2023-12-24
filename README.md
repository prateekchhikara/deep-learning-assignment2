# Task 1: Variational Auto-Encoder (VAE) Implementation and Analysis

### Introduction
This repository contains my solution to the assignment focused on the implementation and analysis of Variational Auto-Encoders (VAEs), a class of generative models that are fundamental in the field of machine learning. VAEs are known for their explicit likelihood maximization objective and are particularly adept at unsupervised representation learning. This assignment is designed to provide practical experience with VAEs, their architecture, and their applications in generative modeling and representation learning.

### Assignment Overview
The assignment is structured around several key objectives:
- **Data Loading Pipeline**: I set up a data loading pipeline using PyTorch, ensuring efficient and effective data handling.
- **Auto-Encoder Architecture**: I implemented, trained, and visualized an auto-encoder, understanding its role as the foundation of a VAE.
- **VAE Implementation**: I extended the auto-encoder into a variational auto-encoder, incorporating the variational aspect that defines a VAE.
- **Parameter Tuning**: I experimented with adjusting the critical beta parameter in the VAE to observe and understand its impact on the learning process.
- **Representation Analysis**: I inspected the low-dimensional representations learned by the VAE, gaining insights into its functionality and effectiveness.
- **Generative Capabilities**: I enhanced the VAE's generative capabilities by conditioning it on specific labels, enabling controlled generation of data.

### Dataset Utilized
The MNIST dataset, a classic collection of handwritten digits, was used for all experiments and implementations. This dataset is an excellent choice for initial experiments due to its manageable size and the simplicity of its modeling requirements.

### Technologies and Tools
The entire implementation was done using PyTorch, a leading deep learning framework that provides a robust, flexible platform for building and experimenting with deep learning models.

### Conclusion
By the end of this assignment:
- I have gained a comprehensive understanding of the architecture and applications of VAEs in generative modeling and representation learning.
- I have developed practical skills in PyTorch, enhancing my ability to implement and manipulate deep learning models.
- I have produced a set of experiments and visualizations that demonstrate the capabilities and characteristics of VAEs.


# Task 2: Generative Adversarial Networks (GAN)

#### Overview

This repository contains my solution to the "Generative Adversarial Networks (GAN)" assignment, part of an advanced course in deep learning. The primary focus of this project was to implement a GAN, as described in the paper "Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks", and to learn the activation maximization visualization technique.

#### Implementation Details

1. **GAN Architecture:**
   - **Discriminator and Generator:** Following the guidelines provided in the assignment, I implemented the discriminator and generator components of the GAN. The architecture was designed in line with the structure proposed in the referenced research paper.
   - **Dataset:** The CIFAR-10 dataset was used for training the GAN, providing a diverse range of images for effective learning.

2. **Training Process:**
   - **Training Loop:** I developed a robust training loop that iterates through the dataset, training the discriminator and generator in tandem.
   - **Loss Computation and Parameter Updates:** I implemented the loss computation for both the discriminator and generator. The parameters of the model were updated using these computed losses, ensuring effective learning and convergence of the model.

3. **Optimization:**
   - **Defining Loss Objectives:** The loss objectives for both parts of the GAN were defined and implemented, ensuring that each component learns effectively.
   - **Optimizers:** Appropriate optimizers were selected and configured for both the discriminator and generator, optimizing the training process.

4. **Visualization:**
   - **Activation Maximization Technique:** I applied the activation maximization technique to visualize what the network layers have learned, providing insights into the inner workings of the GAN.

#### Theoretical Understanding

In addition to the coding implementation, the assignment included answering theoretical questions to demonstrate a deeper understanding of the concepts behind GANs. These answers are included in the repository and offer an in-depth analysis of the GAN architecture, training process, and its applications.

#### Conclusion

This project was a comprehensive exercise in understanding and implementing Generative Adversarial Networks. It not only enhanced my practical skills in coding advanced neural network architectures but also deepened my theoretical knowledge in the field of deep learning. The completed code along with detailed comments is available in this repository, serving as a reference for anyone interested in GANs and their implementation using the CIFAR-10 dataset.
