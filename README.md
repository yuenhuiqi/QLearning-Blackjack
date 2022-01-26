# QLearning-Blackjack

My take at building a Blackjack simulator and training Q-Learning player to be a pro @ blackjack :-)

Refer to ```QLearning-Blackjack/QLearning_Blackjack.ipynb``` for codes

(Got some help from: https://towardsdatascience.com/reinforcement-learning-solving-blackjack-5e31a7fb371f) 

# 1. Blackjack Game Simulator between Player and Dealer
- If player’s sum exceeds 21, or becomes less than 1, then she “goes bust” and loses the game (reward -1)
- If the player sticks, then the dealer starts taking turns. The dealer always sticks on any sum of 16 or greater, and hits otherwise. 
- If the dealer goes bust, then the player wins
- Outcomes: win (reward +1), lose (reward -1), or draw (reward 0)


# 2. Training Q-Learning player
- using ε-greedy function to determine actions to take, training for 100,000 episodes 
