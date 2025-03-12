# Survival Console Game
(Survive or Perish)

This is a text-based survival game written in **C#** for console play, utilizing object-oriented programming principles.

## Game Theme
You play as a character who finds themselves lost in the wilderness. To survive, you must make decisions that influence key stats: **Health, Hunger, Thirst, Energy, and Motivation**. Choices can impact these stats **positively, negatively, or neutrally**. 

- If any stat reaches **0 or turns negative**, you lose the game.
- Every **4 choices** represent a full in-game day (since each choice takes 6 hours).

## Features
- **Main Menu Options:**
  - Start a new game
  - Save or load a previous game
  - View a gameplay guide
  - Exit the game

- **In-game Display:**
  - Current stats and the number of days survived are shown on the screen.
  - The game presents different scenarios with **decision-based outcomes**.
  - Players can **save and load progress**.

- **Controls:**
  - `N` → Restart the game from scratch.
  - `S` → Save stats and progress to a file.
  - `U` → Load previous game data.
  - `G` → Display the guide.
  - `E` → Exit the game.
  - `0` / `1` → Make in-game choices affecting stats.

## Example Scenario

Survive or Perish! Day: 0
New: N | Save: S | Upload: U | Guide: G | Exit: E
Health: 100 Hunger: 100 Thirst: 100 Energy: 100 Motivation: 100

You found a well on your way. You can drink the water or continue walking. (0/1)

- Choosing `0` (drink water) may **reduce thirst** but might **lower health** if the water is unsafe.
- Choosing `1` (continue walking) keeps your stats unchanged but increases hunger/thirst.

## How to Play
1. **Start the game** and make choices that help you survive.
2. **Manage your stats** wisely, balancing risks and rewards.
3. **Save/load progress** to continue your adventure later.
4. **Survive as many days as possible** before your stats drop to zero.

Have fun and good luck surviving!
