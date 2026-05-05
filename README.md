# Mini Projects

A collection of mini projects completed as part of a Python programming course.

## Projects

### 1. Phone Book
A Python program that simulates a phone book directory.
- Search by phone number or name
- Add new contacts
- Input validation

#### What I Used
- `dictionary` to store phone numbers and names
- `functions` to organize the code
- `for loop` with `dictionary.items()` to search through contacts
- `if statement` inside loops for validation and matching
- `isdigit()` and `len()` for input validation

### 2. Birthday Calculator
A Python program that calculates a person's age and the day they were born.
- Accepts unlimited number of people
- Calculates current age and birth day name
- Finds the oldest and youngest person
- Validates date input (format, range, symbols)
- Sorts people from oldest to youngest
- Prints inputs in reverse order
- Filters people born on Sunday

#### What I Used
- `datetime` module (`date`, `strftime`) for date operations
- `functions` with `return` values for age calculation and validation
- `list` of `dictionaries` to store people data
- `isdigit()` and `split()` for input validation
- `max()`, `min()`, `sorted()` with `lambda` functions
- `reversed()` to print inputs in reverse
- List comprehension to filter by day

### 3. Bike Description
A Python program that describes a bike in a factory, converted from procedural programming to Object Oriented Programming.
- Create a bike with description, cost, sale price, and condition
- Update the sale price
- Sell the bike
- Prevent price updates after selling

#### What I Used
- `class` to define the Bike blueprint
- `object` to create bike instances
- `__init__` constructor to initialize attributes
- `self` to access instance attributes and methods
- **Encapsulation**: private attributes using `__` (double underscore) with `getters` for controlled access
- `methods` like `update_sale_price()`, `sell()`, and `display()`

### 4. Bank Account
A Python program that simulates a bank account system.
- Create user accounts with zero balance
- Deposit and withdraw money
- Check current balance
- Displays date and time with each transaction
- Prevents invalid operations (negative amounts, insufficient balance)

#### What I Used
- `class` and `object` to represent bank accounts
- **Encapsulation**: private attributes (`__balance`, `__owner`) with controlled access through methods
- **Polymorphism**: `__add__` to combine balances with `+` operator, `__str__` for custom print output
- `datetime` module to display transaction timestamps
- `methods` for `deposit()`, `withdraw()`, and `check_balance()`
