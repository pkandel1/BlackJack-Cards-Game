# BlackJack-Cards-Game


Blackjack Game README

Overview:

This JavaScript code implements a simplified version of the classic card game Blackjack. In this game, the player competes against a computerized dealer. The objective is to achieve a hand value closer to 21 than the dealer without exceeding it.

Rules Implemented:

Deck Creation and Shuffling:
A standard deck of 52 playing cards is created, consisting of four suits (hearts, diamonds, clubs, and spades) and thirteen values (A, 2-10, J, Q, K).
The deck is shuffled before each round to ensure randomness.

Dealing Hands:
At the beginning of each round, two cards are dealt to both the player and the dealer.
Cards are drawn randomly from the shuffled deck without replacement.

Card Values:
Number cards (2-10) are worth their face value.
Face cards (Jack, Queen, King) are each worth 10 points.
Aces can be worth either 1 or 11 points, whichever is more favorable to the player's hand without exceeding 21.

Player Actions:
The player has two main actions: "hit" and "pass".
"Hit" allows the player to draw an additional card to their hand.
"Pass" indicates the player's decision to end their turn and let the dealer play.

Dealer Actions:
The dealer follows a predefined strategy: they must hit if their hand value is 16 or lower and stand if it's 17 or higher.
The dealer's hidden card is revealed after the player's turn ends.

Winning Conditions:
If the player's hand value exceeds 21 ("busts"), they lose the round.
If the dealer busts, the player wins the round.
The player wins if their hand value is closer to 21 than the dealer's without exceeding 21.
If the player and dealer have the same hand value, it results in a tie (push).

How to Run the Game:
Ensure you have a compatible environment to run JavaScript, such as a web browser or Node.js.
Open the provided HTML file containing the game code in a browser or execute the JavaScript file using Node.js.
The game interface will be displayed, allowing the player to interact with buttons for hitting, passing, and starting the next hand.



This code is developed by : Pratik Kandel


Disclaimer:
This code serves as a basic implementation of Blackjack and may not cover all rules and variations found in real-world gameplay. 




