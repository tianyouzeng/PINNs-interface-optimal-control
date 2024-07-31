# PINNs-Interface-Optimal-Control

This repository contains the source code for the paper "**The Hard-Constraint PINNs for Interface Optimal Control Problems**" by Ming-Chih Lai, Yongcun Song, Xiaoming Yuan, Hangrui Yue, and Tianyou Zeng. The paper can be found at [arXiv:2308.06709](https://arxiv.org/abs/2308.06709).

## Requirements

To run the code in this repository, you will need following software and packages:

- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [NumPy](https://numpy.org/)
- [SciPy](https://scipy.org/)
- [Matplotlib](https://matplotlib.org/)
- [PyTorch](https://pytorch.org/)
- [tqdm](https://tqdm.github.io/)

We recommend using [conda](https://docs.conda.io/en/latest) to manage the above packages.

## Files

Each ".ipynb" file corresponds to one numerical example in the paper, and the name of the file suggests its functionality. For example:

- [example_01/example_01_sPINN.ipynb](https://github.com/tianyouzeng/PINNs-interface-optimal-control/blob/main/example_01/example_01_sPINN.ipynb) is the source code for Example 1 with soft-constraint PINN method (Algorithm 1) in the [paper](https://arxiv.org/abs/2308.06709).
- [example_02/example_02_hPINN.ipynb](https://github.com/tianyouzeng/PINNs-interface-optimal-control/blob/main/example_02/example_02_hPINN.ipynb) is the source code for Example 2 with hard-constraint PINN method (Algorithm 2 Option I) in the [paper](https://arxiv.org/abs/2308.06709).
- [example_01/example_01_hPINN_nn.ipynb](https://github.com/tianyouzeng/PINNs-interface-optimal-control/blob/main/example_01/example_01_hPINN_nn.ipynb) is the source code for Example 2 with hard-constraint PINN method and neural network-approximated auxiliary functions (Algorithm 2 Option II) in the [paper](https://arxiv.org/abs/2308.06709).


Simply run all the cells in the corresponding file to obtain the numerical results.

The folder [env](https://github.com/tianyouzeng/PINNs-interface-optimal-control/tree/main/env) contains an example [conda](https://docs.conda.io/en/latest) environment for running the code.

## Citation

```
@misc{lai2023hardconstraint,
      title={The Hard-Constraint PINNs for Interface Optimal Control Problems}, 
      author={Ming-Chih Lai and Yongcun Song and Xiaoming Yuan and Hangrui Yue and Tianyou Zeng},
      year={2023},
      eprint={2308.06709},
      archivePrefix={arXiv},
      primaryClass={math.OC}
}
```

