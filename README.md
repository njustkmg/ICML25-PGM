## Probabilistic Group Mask Guided Discrete Optimization for Incremental Learning-ICML2025
-----------------------------------------------------------
This is the official implementation of PGM in the paper in Pytorch.


## Dependency
- [PyTorch](https://pytorch.org/) > 1.5

## Dataset

- CIFAR-100 Split (available current version)
- CIFAR-100 Superclass (available current version)
- TinyImageNet (available current version)

## Installation
To execute the codes for running experiments, run the following.
```python
pip install -r requirements.txt
```

## Training
We provide several training examples with this repositories:


- To train PGM on Cifar100 on GPU [GPU_ID] with seed number [SEED] , simply run the following
```bash
>> ./scripts/pgm_cifar100.sh [GPU_ID] [SEED]
```

