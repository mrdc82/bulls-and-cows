# Code Guessing Game (Mastermind Variant)

## Overview
This is a classic two-player game, often played with paper and pen. The modern version is also known as **Mastermind**.

## How to Play
1. **Alice (Player 1)** chooses a secret 4-digit code (e.g., `1492`), ensuring all digits are different.
2. **Barbara (Player 2)** attempts to guess the code.
3. Barbara can make multiple guesses, using any 4-digit combination (without repeating digits).
4. After each guess, Alice provides a hint consisting of two values:
   - The number of digits that are correctly guessed and in the correct position.
   - The number of digits that are correctly guessed but in the wrong position.

### Example Hints
- **Secret Code:** `1492`
- **Barbara's Guess:** `2013`
  - **Hint:** `0-2` (Two correct digits, but in the wrong positions)
- **Barbara's Guess:** `1865`
  - **Hint:** `1-0` (One correct digit in the correct position, no other correct digits)

## Word-Based Variation
The game can also be played using 4-letter words instead of digits. However, this variation requires knowledge of a language.

## More Information
For further details, check out the [Wikipedia article on Mastermind](https://en.wikipedia.org/wiki/Mastermind_(board_game)).

---
Happy guessing! 🎯

