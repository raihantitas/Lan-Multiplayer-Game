# LMG

No, it is not a light machine gun. It is LAN Multiplayer Games (LMG). 

This software will contain numerous games available in single player as well as in multiplayer mode. In single player mode users will play against the Artificial Intelligence (AI) 
of computer. Whereas, in multiplayer mode a user can play against another user connecting each other through Local Area Network (LAN). 

At this time, we have only one game available and that is **Reversi**.

## Reversi

It is also known as **Othello**. It is a strategy board game for two players. It is played in 8 x 8 uncheckered board.
Game pieces are called disk and the objective of the game is having maximum disks in own favor.

For more details visit:  https://en.wikipedia.org/wiki/Reversi 

### Features

The game has both single player mode and multiplayer mode as well as some basic instructions with rules of playing and option where users will be able to 
customize the game theme according to his/her taste.

In Single player mode user can choose difficulty level of the game. There are three layers of difficulty namely - easy, medium and hard. 
User can also see top five high scores with name and can reset the scores. While playing user can also be able to customize the theme.

In Multiplayer mode user can set his/her name that will be visible to opponent player. For establishing LAN connection one player has to create server and 
another player has to join to that server. While creating a server a default value of the server IP and port number will be provided. 
He can change the port number if that port is busy. On the contrary, the user who will join the server will have to give the same server IP and port number. 
After joining they can play with each other through Local Area Network (LAN). 

#### Notes

Java, Java Swing and Java Socket Programming are used to build this software.
In Reversi Minimax algorithm with alpha-beta pruning is used as AI. 
Higher difficulty can take more time to response. 
Some access permission may need for LAN connection and one must have jre to run this software.
