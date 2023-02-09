# Simple Diffusion

This repository is a small compilation of Diffusion Model tutorials and examples, while focussing more on implementation concerns 
and less on theory or foundations. 

**Note**: This is a work in progress, and will be updated as I learn more about the subject.

# Notebooks

- [Denoising Diffusion Probabilistic Models (DDPM)](https://colab.research.google.com/github/titu1994/simple_diffusion/blob/master/notebooks/01_simple_ddpm.ipynb) - A simple implementation of DDPM, with a focus on the training loop and the 
  sampling pipeline.
- [Classifier-Free Diffusion Guidance](https://openreview.net/pdf?id=qw8AKxfYbI)

# Requirements

Most of the notebooks should be compatible with Google Colab and are linked above . 
However, if you want to run them locally, you will need the following -

- Python 3.6+
- PyTorch 1.13+
- diffusers
- einops
- tqdm
- matplotlib