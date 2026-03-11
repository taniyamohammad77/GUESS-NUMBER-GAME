# Guess the Number

So this is my FY sem 1 C++ project. Pretty simple idea — the computer secretly picks a number between 1 and 100, and you just keep guessing until you figure it out.

## What's the game about

You type a number, and the program tells you if the answer is higher or lower. You keep going until you nail it. Once you do, it tells you how many guesses it took. Nothing fancy, but it works.

## How to run it

```bash
g++ game.cpp -o game
./game
```

On Windows:
```bash
g++ game.cpp -o game.exe
game.exe
```

## Stuff I picked up making this

Honestly learned a lot from this small project — things like how `do-while` loops actually behave, writing if-else chains properly, and using `srand(time(0))` so the number is different every time you play. Wrote the whole thing myself.

## What you need

Just g++ installed. That's it.
