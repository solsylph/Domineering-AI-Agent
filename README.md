# Domineering-AI-Agent-
Domineering AI Agent for AI: REASONING &amp; PROBLEM SOLVING Group Assignment. 

Collaborated with 11acc (https://github.com/11acc) for the elaboration of this agent. 

_____

In Domineering, there are two players, each with an unlimited supply of dominoes (rectangular tiles consisting of two square ends). One player has vertical dominoes, and the other has horizontal dominoes.

______

![Domineering-Comments-on-a-Game-of-No-Chance-figure-5](https://github.com/solsylph/Domineering-AI-Agent-/assets/126614634/f68e0b32-a004-4308-b086-6003fbbdc054)

______

The goal of the game is to place your dominoes on the board in such a way that your opponent cannot make a legal move. As you can see in the board above, players take turns placing a tile on the board and each domino must cover exactly two adjacent empty squares on the grid. A player can only place the tiles either horizontally or vertically and a tile cannot overlap with another tile. The game ends when one player is unable to place a domino on their turn. This player loses, and the other player is declared the winner. A key aspect of the game involves anticipating future moves and trying to control the board. 

In this code you will find that Alejandro and myself collaborated to create an intelligent agent that can complete with the agent found in our professor's server. On average, it won around 80% of the games it played against the server. Explanatory comments for the agent's behavior and reasoning can be found within the python notebook, and our general implementation involved using a minimax algorithm to help the agent predict which tile placement would be optimal. 


