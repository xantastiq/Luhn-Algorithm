# Luhn-Algorithm

# 💳 Credit Card Validator

This is a simple Python script that validates credit card numbers using the **Luhn algorithm**, a widely-used method for checking the validity of identification numbers.

---

## 📌 Features

- ✅ Cleans input (removes hyphens and spaces)
- ✅ Implements the Luhn check
- ✅ Outputs whether a card number is valid or invalid
- ✅ Simple and easy to understand

---

## 📖 How It Works

The Luhn algorithm works as follows:

1. Reverse the card number.
2. From the reversed number:
   - Add every digit at an **odd index** to the total directly.
   - For every digit at an **even index**:
     - Multiply it by 2.
     - If the result is greater than 9, add the digits of the result.
3. Add all the processed digits together.
4. If the total is divisible by 10, the card is valid.

---

## 🚀 Getting Started

### 📋 Prerequisites

- Python 3.x

### ▶️ Running the Script

1. Clone the repository or download the code.
2. Run the script using Python:

```bash
python validator.py

Input: 4111-1111-1111-1111
Output: VALID!


---

Taswar Eshraq

