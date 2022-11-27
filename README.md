# Google-Man-City

Research Paper: https://ieeexplore.ieee.org/abstract/document/9708400

Google Research Football: https://arxiv.org/pdf/1907.11180.pdf

## Results

### Acadmey Scenarios

0 - Empty Goal close</br>
1 - Empty Goal</br>
2 - Run to Score</br>
3 - Run to Score with Keeper</br>
4 - Pass and Shoot with Keeper</br>
5 - Run, Pass and Shoot with Keeper</br>
6 - 3 versus 1 with Keeper</br>
7 - Corner</br>
8 - Counterattack Easy</br>
9 - Counterattack Hard 

#### PPO with Depthwise Convolutions (ours) v PPO (Benchmark)

![Screenshot_20221127_185803](https://user-images.githubusercontent.com/77017479/204137894-77527ab2-d9af-4f7f-8c8e-4fe418ac6414.png)
<p align='center'>(a)</p>

#### QRDQN with Depthwise Convolutions (ours) v IMPALA (Benchmark)

![Screenshot_20221127_185911](https://user-images.githubusercontent.com/77017479/204137944-8e611765-0aa3-4747-81de-ac454453ddf6.png)
<p align='center'>(b)</p>

<p align='center'>Fig 1. Episodic mean reward with checkpoint for Academy
scenarios.</br>(a)PPO with depthwise convolution compared with PPO
benchmarks</br>(b) QRDQN with depthwise convolutions compared to
IMPALA benchmarks.</br>
(Figure 6 in our paper)</p>

### 11 v 11

| Agents | Easy | Medium | Hard |
| ------ | ---- | ------ | ---- |
| QRDQN@3M | 1.29+/-0.94 | 0.68+/-0.86 | -0.35+/-0.90 |
| PPO @3M | 2.49+/-1.87 | -1.3+/-1.18 | -1.01+/-1.04 |
| QRDQN@6M | 1.36+/-0.85 | 1.32+/-0.89 | 0.40+/-0.79 |
| PPO @6M | 2.78+/-1.85 | -0.32+/-0.56 | -0.94+/-1.91 |

<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Mean And Standard Deviations Of Rewards</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With Checkpoints Rewards On Evaluation For All 11-V-11</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Scenarios</span>
