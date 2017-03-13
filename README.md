# RobotReinforcementLearning
Reinforcement Learning for automatic Robot training using Machine Learning with Neural Networks

The world’s largest industrial robot maker is developing robots that use reinforcement learning to figure out how to do things. Reinforcement Learning is latest artificial intelligence technique for automatic training of robots and for playing games. Deep mind has used reinforcement learning with neural network machine learning to train networks for playing games.

Reinforcement learning problems involve learning how to map situations/states to actions so as to maximize a numerical reward. Training does not tell which actions to take (as in machine learning) but instead it tries to find which actions will result in best reward by exploring large state space in it's environment.

Reinforcement learning is not unsupervised learning. Reinforcement Learning does not use examples of correct behavior. Reinforcement Learning maximizes a reward signal instead of trying to find hidden structure/pattern. Uncovering structure/hidden in environment is useful but by itself it does not address the problem of maximizing a reward signal.

Example Application-1: An adaptive controller adjusts parameters of a petroleum refinery's operation in real time. The controller optimizes the yield/cost/quality trade-off on the basis of specified marginal costs without sticking strictly to the set points originally suggested by engineers.

Example Application-2: A mobile robot decides whether it should enter a new room in search of more trash to collect or start trying to find its way back to its battery recharging station. It makes its decision based on the current charge level of its battery and how quickly and easily it has been able to find the recharger in the past.

Four main subelements of a reinforcement learning system:

1) a policy, 2) a reward signal, 3) a value function, 4) a model of the environment
With Machine learning using neural networks we can use ConvNet neural network to train a value function (Q-values function), a policy network or an environment model.

DQN RL for Atari Games from Google Deep Mind:

The DQN used a deep convolutional neural network (CNN) [Krizhevsky et al., 2012] to approximate a Q-value function. It maps raw pixel images directly to actions. No pre-input feature extraction is needed. The only one thing is to let the algorithm improve policies through playing games over and over again. It learnt playing 49 different games, using the same network architecture with no modification.



https://www.technologyreview.com/s/601045/this-factory-robot-learns-a-new-job-overnight/

The world’s largest industrial robot maker, Fanuc, is developing robots that use reinforcement learning to figure out how to do things.

See for more details:
https://www.linkedin.com/pulse/reinforcement-learning-robot-machine-sarabjeet-singh
