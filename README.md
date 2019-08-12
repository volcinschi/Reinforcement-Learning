# Reinforcement-Learning
Reinforcement learning homework IBIO4615

Dependencies
- Python3.5+
- Pytorch 1.0.1.
- gym, matplotlib, numpy

```bash
conda install -c hcc gym 
conda install -c conda-forge tensorboardx 
```
## DQN
- Original paper: https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf

Tasks:
1. Play with the hyperparameters and show their corresponding graphs. Which parameter caused the most change? Which one didn’t affect that much? Discuss briefly your results
2. Anneal the 𝞮 hyperparameter to decay linearly instead of being fixed? Did it help at all? Why?
3. Play with the network architecture and report any results

# DDPG
- Original paper: https://arxiv.org/abs/1509.02971
- OPENAI Baselines post: https://blog.openai.com/better-exploration-with-parameter-noise/

**Note that DDPG is feasible about hyper-parameters. You should fine-tuning if you change to another environment.**

Episode reward in Pendulum-v0:  

![ep_r](https://github.com/sweetice/Deep-reinforcement-learning-with-pytorch/blob/master/Char05%20DDPG/DDPG_exp.jpg)  

