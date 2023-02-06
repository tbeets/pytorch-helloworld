# pytorch-helloworld

Demonstrate basic setup and validation of PyTorch tensors using Anaconda.

## Pre-Requisites

* Anaconda
* NVIDIA driver that meets minimum compatibility with `pytorch-cuda` version

> Conda PyTorch package helpfully bundles its own version of CUDA Toolkit and cudnn.

## Environment
```bash
# In a new/activated environment...
conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
```

## Execute
```bash
python3 main.py
```

Can validate system CUDA with:
```python
import torch
torch.cuda.is_available()
```

## See also

* [PyTorch getting started](https://pytorch.org/get-started/locally/#linux-verification)