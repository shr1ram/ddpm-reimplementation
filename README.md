<div align="center">

# Implementing DDPM in PyTorch

### Denoising Diffusion Probabilistic Models

[Paper](https://arxiv.org/abs/2006.11239) • [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)

</div>

---

This project implements **Denoising Diffusion Probabilistic Models (DDPM)** from the ground up, based on the paper by [Ho et al. (2020)](https://arxiv.org/abs/2006.11239).

### Features

- Complete forward & reverse diffusion processes
- U-Net architecture with self-attention and sinusoidal time embeddings
- Iterative denoising from pure noise for image generation
- Training on CIFAR-10 (32×32 RGB images)

### Results

Only 50 epochs were used for training due to limited compute.

Early features can be seen, and significant improvements are expected with 10-100x the epochs.

<img width="1182" height="143" alt="image" src="https://github.com/user-attachments/assets/57adc069-eeee-43b1-8af5-583664cc166d" />



### Future Work

- Test the model on more powerful hardware
- Extend the model to be conditional on object IDs
- Extend the model to be conditional on a textual description via word embeddings
