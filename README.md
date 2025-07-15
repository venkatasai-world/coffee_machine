# ☕ Coffee Machine Simulation

This is a simple Python program that simulates a coffee machine. Users can select drinks, insert coins, and get coffee if the machine has enough resources.

---

## 📋 Features

- Choose from: `espresso`, `latte`, `cappuccino`
- Check if enough ingredients are available
- Accept coins (quarters, dimes, nickels, pennies)
- Return change if overpaid
- Show current resources using the `report` command
- Turn off the machine using `off`

---

## 💻 How to Run

Make sure Python is installed, then run:

```bash
python coffee_machine.py
```

---

## 🧪 Example

```
What would you like? (espresso/latte/cappuccino): latte
Please insert coins.
how many quarters?: 10
how many dimes?: 0
how many nickles?: 0
how many pennies?: 0
Here is $0.0 in change.
Here is your latte ☕️. Enjoy!
```

---

## 🛠️ Initial Resources

```python
resources = {
    "water": 300,
    "milk": 200,
    "coffee": 100
}
```

---

## 📦 Menu Items

```python
MENU = {
    "espresso": {
        "ingredients": {"water": 50, "coffee": 18},
        "cost": 1.5,
    },
    "latte": {
        "ingredients": {"water": 200, "milk": 150, "coffee": 24},
        "cost": 2.5,
    },
    "cappuccino": {
        "ingredients": {"water": 250, "milk": 100, "coffee": 24},
        "cost": 3.0,
    }
}
```

---

## 🧠 Notes

- All amounts are in ml for liquids and g for coffee.
- Coin values:
  - Quarter = $0.25
  - Dime = $0.10
  - Nickel = $0.05
  - Penny = $0.01

---

## ✅ Commands

| Command | Description                     |
|---------|---------------------------------|
| espresso/latte/cappuccino | Make a drink           |
| report  | Show remaining resources & profit |
| off     | Turn off the coffee machine       |

---

Enjoy your ☕ Python-powered coffee!
