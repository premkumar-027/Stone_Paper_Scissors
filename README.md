# 🪨🧻✂️ Rock Paper Scissors Game (Python Console Version)

This is a simple **Stone Paper Scissors** game built in Python for the command line. The player competes against the computer, and the game includes **ASCII visuals** to enhance the experience.

---

## 🎮 How to Play

- You choose:
  - `0` for **Rock**
  - `1` for **Paper**
  - `2` for **Scissors**
- The computer randomly chooses its move.
- The game will then:
  - Display both moves as ASCII art
  - Announce the winner or a draw

---

## 🛠 Technologies Used

- **Python 3**
- `random` module for computer choice
- ASCII Art for visual representation
- Console input/output

---

## 🚀 How to Run the Game

1. Make sure Python is installed (`python --version`)
2. Download or clone this repo.
3. Run the game:

---

## 📂 Project Structure

rock-paper-scissors/

│

├── rock_paper_scissors.py # 🎮 Game source code

├── README.md # 📄 Project documentation

├── .gitignore # ⚙️ Files to ignore in Git

└── screenshot.png # 🖼 Optional game screenshot



---


## 📄 Full Game Code Preview

```python
import random

# ASCII Art for the choices
rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''

game_images = [rock, paper, scissors]

# User input
user_choice = int(input("Type 0 for Rock, 1 for Paper, or 2 for Scissors:\n"))

if user_choice < 0 or user_choice > 2:
    print("Invalid input. You lose!")
else:
    print("You chose:")
    print(game_images[user_choice])

   ........
