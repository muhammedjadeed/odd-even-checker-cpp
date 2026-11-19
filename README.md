# odd-even-checker-cpp

A simple C++ program that asks the user for an integer and reports whether it is even or odd.

## How it works

- Reads an integer from the user.
- If the input is not a valid integer, prints an error message and exits with a nonzero status.
- Uses the remainder operator (`%`) to check whether the number is divisible by 2. A remainder of `0` means the number is even; otherwise, it is odd.

## Build and run

```sh
g++ -std=c++17 -Wall -Wextra -pedantic main.cpp -o odd-even-checker
./odd-even-checker
```