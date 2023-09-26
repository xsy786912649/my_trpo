# my_trpo

This is a PyTorch implementation of ["Trust Region Policy Optimization (TRPO)"](https://arxiv.org/abs/1502.05477).

This repo is based on https://github.com/ikostrikov/pytorch-trpo, and we fix an issue in terms of the value function evaluation and adavatage computation in the repo.

We provide the codes for gym with env-v4 (folder trpo) and env-v2 (folder trpo-old-gym).

## Usage

```
python main.py --env-name "Reacher-v4"
```

