# Stable Diffusion - Image to Prompts Challenge
Part of [CPSC522: AI](https://www.cs.ubc.ca/~poole/cs522/2023/) course project.

### Script to Download Data
```bash
kaggle competitions download -c stable-diffusion-image-to-prompts
unzip stable-diffusion-image-to-prompts.zip
```

### Setup
```bash
conda create -n 522-project python=3.9
conda activate 522-project

# install torch 2.0 with cuda 11.8
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu118

# install other dependencies
pip install -r requirements.txt
```
