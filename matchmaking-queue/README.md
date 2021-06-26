# Matchmaking Queue

## Description
In order to make game more engaging and satisfying only players with similar skill level should play against each other.  
This can be achieved by utilizing ELO system similar to the one used in chess.
The system used in the game should pair up players without performing any additional matching logic.

## Requirements
* Player needs to join matchmaking queue in order to play,
* Only matchmaking queue can create games,
* If there are two players in queue, game should be created, and those players should be notified and put into it,
* `JOIN` and `LEAVE` operations should be transactional.

## Sequence diagrams

### Join matchmaking queue

![alt text][logo]

[logo]: ./join.png "Join Sequence Diagram"
