# big-quiz

A simple, fast-paced Minecraft-themed multiple-choice quiz built with Pygame Zero. It's designed to be easy for Minecraft experts and challenging for newcomers — click answers before the timer runs out!

## Features
- 4-answer multiple-choice questions
- Per-question countdown timer
- Score tracking and simple end screen
- Small, single-file codebase (Pygame Zero)

## Requirements
- Python 3.8+
- Pygame Zero (install with pip)

Install dependencies:

```bash
pip install pgzero
```

## Run the quiz
1. Clone the repository and change into the quiz directory:

```bash
git clone https://github.com/pg-141-mc/big-quiz.git
cd "big quiz"
```

2. Start the game with Pygame Zero:

```bash
pgzrun quiz.py
```

Notes:
- If you have issues running `pgzrun`, make sure Python's `Scripts` (Windows) or your PATH contains the location where `pgzrun` was installed, or run it with the full path to the command.

## Controls
- Click an answer box with the mouse to choose an answer.
- Each question has a 10-second timer; letting it reach 0 ends the game.

## Code overview
- big quiz/quiz.py — the entire game (Pygame Zero). The script defines the layout, questions, timer, mouse handling, and simple scoring.

## History
- Initial commit: [ffa75f54](https://github.com/pg-141-mc/big-quiz/commit/ffa75f54aa03af8a52ee36d4693196cf5f998352) — "Initial commit" by Prayaag Ghimire on 2026-09-02.

## Contributing
Small fixes and question additions are welcome. If you add many questions or change the format, please open a pull request describing your changes.

## License
This repository has no license file. If you want to make this project reusable, consider adding an open-source license such as the MIT license.
