# PLP Python Week 6 - Safe Functions

## Files

* `safe_tools.py` - Contains three safe functions that handle division by zero, invalid number conversion, and missing dictionary keys.
* `README.md` - Provides information about the assignment and the files in the repository.

## Why can't an if check catch "abc" on its own?

An `if` check cannot automatically catch `"abc"` when converting it to an integer because `int("abc")` raises a `ValueError`. The `try` and `except` blocks allow the program to catch this specific error and continue running instead of crashing.
