# Wide Residual Networks (WideResNets) in PyTorch
WideResNets for CIFAR10/100 implemented in PyTorch. This implementation requires less GPU memory than the Torch's one https://github.com/szagoruyko/wide-residual-networks.

Example:
```
python train.py --dataset cifar100 --depth 40 --width-factor 4
```

Tested on PyTorch of this [version](https://github.com/pytorch/pytorch/tree/7ad948ffa95af4b19394a182dab477f3de853205).

# Acknowledgement
- [densenet-pytorch](https://github.com/andreasveit/densenet-pytorch)
- Wide Residual Networks (BMVC 2016) http://arxiv.org/abs/1605.07146 by Sergey Zagoruyko and Nikos Komodakis.
