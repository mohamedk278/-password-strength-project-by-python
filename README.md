# Password Strength Checker 🔑

A small Python project I made to practice conditions and string methods. You type a password, and it checks a few basic things and tells you if it's weak, medium, or strong.

## What it checks

- Is it at least 8 characters long
- Does it have a number
- Does it have an uppercase letter

Each check that passes gives 1 point. 3 points is Strong, 2 is Medium, and anything lower is Weak.

## How to run

1. Install Python if you don't have it
2. Download or clone this repo
3. Open a terminal in the project folder and run:

```bash
python main.py
```

## Example

```text
Enter your password: Hello123
Password length: 8
Is long enough: True
Has digit: True
Has uppercase: True
Score: 3
Strength: Strong
```

## Limitations

It's very basic. It doesn't check for special characters or common passwords, so a weak password like `Hello123` can still get "Strong". Don't use it to judge real passwords.

## Why I made this

I wanted to practice Python and think about what actually makes a password strong.
