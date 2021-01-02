# ML-roots-you

> Like Root Me, but it’s a ML model that exploits a loophole in the dataset / environment

### Why

Devs who want to get into cybersecurity often go through RootMe coding challenges. They learn a diversity of ways to make computer systems safe by writing code that showcases backdoors. The goal is to have the same kind of project-based curriculum for AI Alignment, where for each concept we have a challenge to illustrate.

### In practice

First step is to have a github repository with a handful of challenges for reinforcement learning exploits. If the feedback on that repository is successful we could start creating environments for other concepts or just link to already existing examples in the literature, turning AI Alignment research into coding challenges.

### More precisely

There would be additional rules for different sub-challenges using the same environment. The sub-challenges could include one pure RL example showcasing a RL failure mode, one simple example to show what a safer solution could look like and one open problem. For each non-open sub-challenge there could be hints/relevant algorithms and a benchmark indicated in the description.

### Concrete examples

There’s a gym environment that demonstrates the concept of treacherous turn. Possible sub-challenges could include maximizing reward:
* without restriction (Q-learning)
* killing your supervisor once (DynaQ)
* using screen as input (DQN)
* killing supervisor once, no planning (meta-learning?)

The key-chest mesa misalignment env (code). AI Safety gridworlds has plenty of envs. Sub-challenges could be first to make a pure reward maximizer (that exploits the environment) then an open problem where the goal is to maximize a combination of reward & safety performance. Viktoria’s list has a lot more examples.

### What this would look like

Check the [challenges](./challenges) folder.

### TODO

* Decide on a few environments where it’s interesting to show a failure.
* Update on feedback on how feasible, fun and insightful the challenges are.
* Launch website with leaderboards + publish on Twitter/LW/github.
* Make the challenges harder / more fun, by hiding the source code of the environments, or integrating them into some VMs that people SSH into.
* Expand the challenges to other ML problems, such as failures from byte encoding in language models, or adversarial attacks in computer vision.
