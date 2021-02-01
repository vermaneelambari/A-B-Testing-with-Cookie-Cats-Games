## A/B-Testing with Cookie Cats Games
#### Project Description: 
##### Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three" style puzzle game where the player must connect tiles of the same color in order to clear the board and win the level. 

### - About game: 
As players progress through the game they will encounter gates that force them to wait some time before they can progress or make an in-app purchase. In this project, I am analyzing the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. In particular, we will analyze the impact on player retention.

### - Video of the game : 
[![Cookie cats]![image](https://user-images.githubusercontent.com/34072722/106522790-0fa04b00-6495-11eb-8227-491132531e95.png)](https://www.youtube.com/watch?v=GaP5f0jVTWE&feature=youtu.be)

### - The brief: 
Initially the first gate was placed at level 30, but in this notebook we're going to analyze an AB-test where we moved the first gate in Cookie Cats from level 30 to level 40. In particular, we will look at the impact on player retention. But before we get to that, a key step before undertaking any analysis is understanding the data.

![image](https://user-images.githubusercontent.com/34072722/106526095-dc13ef80-6499-11eb-8d0f-b8a8ef6f15c7.png)

### - About Dataset: 

The data we have is from 90,189 players that installed the game while the AB-test was running. The variables are:

 - userid - a unique number that identifies each player.
- version - whether the player was put in the control group (gate_30 - a gate at level 30) or the group with the moved gate (gate_40 - a gate at level 40).
- sum_gamerounds - the number of game rounds played by the player during the first 14 days after install.
- retention_1 - did the player come back and play 1 day after installing?
- retention_7 - did the player come back and play 7 days after installing?










