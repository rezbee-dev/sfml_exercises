# C++ SFML Practice

Just a repo for me to store my C++ SFML exercises and solutions

## Exercises

Based on various online sources, books, etc.

### Module A

**A1: Fishys**
- Program where fishes spawn offscreen randomly and move horizontally to come into game view and move offscreen again
- Features/ Todos
  - Create multiple sprites from `fish.png`s
  - Set their positions left or right of the screen (offscreen) at different heights 
  - Have clouds move horizontally so it reaches the opposite end
  - Repeat (don't recreate the sprites, just reset their postions randomly and have them move again)
	
**A2: Timer**
- Program that displays a progress bar set to a short amount of time (ex: 10 secs), that decreases in size as time runs out
- Program also displays timer in text that decreases as time runs out (ex: 0:10, 0:09, etc)
- Features/ Todos
  - Create rectangle shape to represent timebar
    - Position timebar in the middle of the screen
    - Timebar should decrease in size to 0
  - Create timer that countdowns
    - Poistion top center of screen
    - Should be displayed in time format, like this: `00:00`