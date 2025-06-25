Summary of Deep Learning Concepts Learned (Weeks 1–4)
As part of my deep learning project, I completed a structured four-week learning plan focusing on neural networks, convolutional neural networks (CNNs), recurrent neural networks (RNNs)/long short-term memory (LSTM) networks, and transformers. Below is a summary of the key concepts and skills I acquired, based on resources like Andrej Karpathy’s Neural Networks: Zero to Hero playlist, Practical Deep Learning using PyTorch, 3Blue1Brown’s neural network videos, and Colah’s LSTM blog.
Week 1: Neural Networks & PyTorch Basics

Core Concepts: Learned the fundamentals of neural networks, including neurons, layers, activation functions (e.g., ReLU, sigmoid), and backpropagation. Understood how gradient descent optimizes weights to minimize loss functions.
PyTorch Skills: Gained hands-on experience with PyTorch by coding a multilayer perceptron (MLP) from scratch. Learned to define models, compute gradients, and train networks using PyTorch’s autograd system.
Tasks: Implemented and trained a simple MLP (covered in Karpathy’s videos 1–7). Coded along, took notes, and experimented with different architectures to solidify understanding.
Key Takeaway: Neural networks are universal function approximators, and PyTorch provides a flexible framework for building and training them.

Week 2: CNNs for Image Classification

Core Concepts: Studied convolutional neural networks (CNNs), which are designed for image data. Learned about convolutional layers, filters, pooling (e.g., max pooling), and how these reduce spatial dimensions while preserving features.
Applications: Understood how CNNs excel in tasks like image classification by detecting patterns (edges, textures) hierarchically.
Tasks: Built and trained a CNN for image classification (Karpathy’s videos 8–11). Coded along to implement convolutional layers and experimented with architectures to improve accuracy.
Key Takeaway: CNNs efficiently process grid-like data (e.g., images) by leveraging local connectivity and parameter sharing.

Week 3: RNNs/LSTMs for Sequential Data

Core Concepts: Explored recurrent neural networks (RNNs) for sequential data, focusing on their ability to model time-dependent patterns. Learned about vanishing gradient problems and how LSTMs address them using gates (input, forget, output).
LSTM Details: Studied LSTM architecture through Colah’s blog, which clarified how memory cells maintain long-term dependencies in sequences like text or time series.
Tasks: Trained an LSTM model for sequential data (Karpathy’s videos 12–14). Coded along to process sequences and experimented with hyperparameters.
Key Takeaway: LSTMs are powerful for sequential tasks but can be computationally intensive and complex compared to newer architectures.

Week 4: Transformers & Self-Attention

Core Concepts: Learned about transformers, which rely on self-attention mechanisms to process sequences in parallel, outperforming RNNs in tasks like natural language processing. Understood the attention formula and how it captures relationships between tokens.
GPT Architecture: Studied the encoder-decoder architecture of transformers, focusing on the decoder-only design of GPT (from Karpathy’s Let’s Build GPT video). Learned how GPT generates text autoregressively.
Tasks: Implemented a basic self-attention layer and coded a simplified GPT model from scratch. Explored the Neural Networks: Zero to Hero playlist for deeper insights into transformers.
Key Takeaway: Transformers are highly scalable and effective for sequence modeling, making them the backbone of modern large language models like GPT.

Overall Reflections
This four-week journey provided a comprehensive introduction to deep learning, from basic neural networks to cutting-edge transformers. Coding along with Karpathy’s videos and experimenting with PyTorch deepened my understanding and practical skills. I now appreciate the progression of architectures (MLPs → CNNs → RNNs/LSTMs → Transformers) and their specialized applications. Moving forward, I plan to explore advanced transformer models and apply these concepts to real-world projects.
