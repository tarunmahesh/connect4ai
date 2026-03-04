# Connect 4 AI

A Python implementation of Connect 4 with two game modes: Human vs AI and AI vs AI. The AI uses a Negamax algorithm with alpha-beta pruning to make competitive moves.

## Features

- Text-based board display
- Human vs AI mode
- AI vs AI mode
- Simple AI using Negamax with alpha-beta pruning
- Runs directly in Python, no GUI required

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/connect4ai.git
cd connect4-ai
```

2. Run the game:

```bash
python connect4.py
```

## How to Play

1. Choose a game mode:
- 1: Human vs AI
- 2: AI vs AI

2. If Human vs AI, choose whether to play first (y) or second (n).

3. Input your move by typing a column number (1-7).

4. The board prints after each move.

## The AI uses a lookahead Negamax algorithm, but a human can win with careful moves. Example sequence as player O (going second):

```sql
AI plays column 4
Human plays column 3
AI plays column 4
Human plays column 4
AI plays column 4
Human plays column 3
AI plays column 4
Human plays column 2
AI plays column 4
Human plays column 3
AI plays column 5
Human plays column 1
AI plays column 1
Human plays column 1
AI plays column 3
Human plays column 1
AI plays column 1
Human plays column 7
AI plays column 7
Human plays column 7
AI plays column 7
Human plays column 5
AI plays column 5
Human plays column 6
AI plays column 6
Human plays column 6 → Wins!
```

## AI vs AI mode
Choose option 2 to watch two AI agents play against each other, useful for testing and observing AI strategy.

## License
MIT License
