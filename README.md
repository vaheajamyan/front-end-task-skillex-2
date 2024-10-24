# front-end-task-skillex-2
## System Bet Calculator Task Overview

[example](http://images.lsbet.com/calculator/calculate.html)

Design and implement a **system bet calculator** that computes potential winnings based on various betting systems (e.g., 2/3, 3/4, etc.). The calculator should allow users to input odds for different events, specify the type of system bet, and calculate the potential return for different combinations.

---

## Steps to Complete the Task

### 1. Define the Requirements

**User Input:**
- A list of odds for individual events.
- The type of system bet (e.g., 2/3, 3/4, etc.).
- Total stake or bet amount.

**Expected Output:**
- Possible combinations of winning bets.
- Potential payout for each combination.
- Total return based on the specified system bet.

---

### 2. Mathematical Background

#### System Bet Structure:
- **Explanation of a system bet:**  
  For example, in a 2/3 system bet, 3 selections are made, and any combination of 2 out of the 3 bets needs to win for a return.
  
- **Combination Calculation:**  
  Use combinatorics to calculate all possible combinations of bets for the system bet type. For instance, in a 2/3 system bet, list all combinations of 2 events out of 3.
  
- **Return Formula:**  
  Apply the formula to calculate the potential returns based on odds and stake for each combination.

---

### 3. Implementation Breakdown

#### Input Parsing:
- Implement a function to receive and validate the user input:
  - Odds
  - System type
  - Total stake

#### Combination Logic:
- Use combinatorics to generate all possible bet combinations based on the selected system bet type.  
  For example, in a **2/3 system bet**, list all combinations of 2 events out of 3.

#### Payout Calculation:
- Calculate potential winnings for each combination of events that win using the given odds.
- Compute the total return by summing up the results from each successful combination.

#### Edge Cases:
- Handle cases where no bet wins, all bets win, or only some combinations win.

### 4. Testing

To ensure the calculator functions correctly, implement a series of automated tests that validate its key features. These tests should cover:

- **Correct input handling:** Test for valid and invalid inputs (e.g., missing odds, invalid system types, negative stake).
- **Combination accuracy:** Verify that the system bet calculator generates the correct combinations for different system types (e.g., 2/3, 3/4).
- **Payout calculation:** Test that the potential payouts are correctly computed for different combinations of winning events, including edge cases (no wins, all wins, partial wins).
- **Edge case handling:** Confirm that the system behaves as expected in edge cases (e.g., when no combination wins or when all bets win).

[example](http://images.lsbet.com/calculator/calculate.html)
