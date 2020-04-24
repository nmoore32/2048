A clone of 2048

### Starting the game:

Download the [Pygame module](https://www.pygame.org/download.shtml)

To start the game you'd run `$ python twenty_fourty_eight.py` 

The two images should be in the same directly as the python file.

### Gameplay

Use the arrows on the keyboard to slide all the tiles in the selected direction.

Tiles with equal values will merge (each tile can only merge once per move, so if you have three 2s in a row after a merge you'll have a 4 and a 2).

The goal is to keep combining tiles until one tile has value 2048.

Click 'New Game' to start a new game

### Difference from the original

i) There are no sliding tile animations. When you make a move, it just displays the resulting board state (including a random new tile or value 2 or 4).

ii) The game ends once you have a tile with value 2048, whereas the original allows you to keep going. (I didn't create images for tiles beyond 2048).
