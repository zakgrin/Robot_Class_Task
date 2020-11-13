In this project, object-oriented programming in C++ was used to create a class for a Robot. The Robot has a fixed path and can only move either forward or backward in this path.

An initial state of the Robot include:
- initial battery
- initial position
- cost per move (fixed) = -1% from the battery.

The Robot is able to move as long as the battery is larger than 0%.
The Robot waits for the input from the user to decide the next movement. The Robot can't move backward at the first position in the path due to boundary. The Robot can't move foreward at the last position in the path due to the boundary. The Robot consumes a fixed amount of energy for each movement regardless of the distance.

Further Developments:
- Calculate the distance for each move.
- Calculate the cost to be function of the distance (e.g. 1% for each meter)
- Build an environment class with 4 direction (up, down, left, rifht).
- User reinforecment learning to find the shortest path to the final goal in a 2D.
