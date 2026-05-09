# Rock Paper Scissors Game

A simple Java console game where the user plays **Rock, Paper, Scissors** against the computer.

## Features

* User selects:

  * `0` for Rock
  * `1` for Paper
  * `2` for Scissors
* Computer randomly generates its choice
* Determines:

  * Win
  * Lose
  * Tie
* Includes basic input validation

---

## How It Works

1. The program prompts the user to enter a choice:

   * `0` = Rock
   * `1` = Paper
   * `2` = Scissors
2. The computer randomly selects a number between `0` and `2`
3. The program compares the choices and displays the winner

---

## Game Rules

```text id="5es7xb"
Rock beats Scissors
Paper beats Rock
Scissors beats Paper
```

---

## Example Output

### Example 1 — User Wins

```text id="2j8sje"
Welcome to the Rock, Paper, Scissors game
Enter your choice
0: Rock, 1: Paper, 2: Scissors

0
0
2
You Win Congratulations
```

### Example 2 — Tie

```text id="89d3gu"
Welcome to the Rock, Paper, Scissors game
Enter your choice
0: Rock, 1: Paper, 2: Scissors

1
1
1
It's a tie
```

---

## Technologies Used

* Java
* `Scanner` for user input
* `Random` for computer-generated choices

---

## File Structure

```text id="2ueqya"
Day4/
└── RockPaperScissorsGame.java
```

---

## How to Run

### 1. Compile the Program

```bash id="g7k7mc"
javac Day4/RockPaperScissorsGame.java
```

### 2. Run the Program

```bash id="n73n5n"
java Day4.RockPaperScissorsGame
```

---

## Requirements

* Java JDK 8 or higher

---

## Input Validation

The program checks whether the user entered a valid number:

* Less than `0`
* Greater than `2`

If the input is invalid, the program exits with an error message.

---

## Possible Improvements

* Convert numbers into readable words (`Rock`, `Paper`, `Scissors`)
* Add multiple rounds and score tracking
* Allow replay without restarting the program
* Improve formatting and user interface
* Add exception handling for non-numeric input

---

## Author

Created as a beginner Java practice project.
