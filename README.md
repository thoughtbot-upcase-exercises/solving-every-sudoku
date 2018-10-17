# Ruby Challenges / Solving Every Sudoku

Hey there! We're [thoughtbot](https://thoughtbot.com), a design and
development consultancy that brings your digital product ideas to life.
We also love to share what we learn.

This coding exercise comes from [Upcase](https://thoughtbot.com/upcase),
the online learning platform we run. It's part of the
[Ruby Challenges](https://thoughtbot.com/upcase/ruby-challenges) course and is just one small sample of all
the great material available on Upcase, so be sure to visit and check out the rest.

## Exercise Intro

Difficulty: **Hard.**

Your challenge is to write a program that can solve every Sudoku puzzle.

This challenge has some depth to it. It is possible to create a naive solution that can solve easy puzzles but fail to complete harder puzzles.

To help you, a valuable external resource is provided in the exercise instructions.

## Instructions

To start, you'll want to clone and run the setup script for the repo

    git clone git@github.com:thoughtbot-upcase-exercises/solving-every-sudoku.git
    cd solving-every-sudoku
    bin/setup

Use the `SudokuSolver` class (located in `lib/sudoku_solver.rb`) to solve a given Sudoku puzzle and output the results to the screen.

Make sure all tests are passing by running:

```
rake
```

## Fixture data

Two puzzles are provided for you for testing purposes. One is easy. The other is hard.

The puzzles are represented like this:

```
3 0 6 |0 1 5 |0 0 0
0 0 4 |0 0 0 |3 0 0
0 0 0 |0 6 8 |1 9 4
------+------+------
0 8 0 |0 0 6 |0 0 0
0 0 0 |2 4 9 |6 0 1
6 4 0 |0 0 0 |2 0 5
------+------+------
0 0 8 |0 0 3 |0 1 0
0 3 7 |8 9 1 |4 6 2
0 2 0 |6 0 0 |8 0 0
```
Important: zeros represent squares which do not have a value assigned yet. Having multiple zeroes in a row, column, or subgroup does not make the puzzle invalid.

## Resources

[Solving Every Sudoku Puzzle](http://norvig.com/sudoku.html) is an excellent article by Peter Norvig. He provides an in-depth discussion of his approach and a complete solution in Python. Don't underestimate the value of reading through this article carefully.

## Forum Discussion

If you find yourself stuck, be sure to check out the associated
[Upcase Forum discussion](https://forum.upcase.com/t/ruby-challenges-solving-every-sudoku/4607)
for this exercise to see what other folks have said.

## Next Steps

When you've finished the exercise, head on back to the
[Ruby Challenges](https://thoughtbot.com/upcase/ruby-challenges) course to find the next exercise,
or explore any of the other great content on
[Upcase](https://thoughtbot.com/upcase).

## License

solving-every-sudoku is Copyright © 2015-2018 thoughtbot, inc. It is free software,
and may be redistributed under the terms specified in the
[LICENSE](/LICENSE.md) file.

## Credits

![thoughtbot](https://presskit.thoughtbot.com/assets/images/logo.svg)

This exercise is maintained and funded by
[thoughtbot, inc](http://thoughtbot.com/community).

The names and logos for Upcase and thoughtbot are registered trademarks of
thoughtbot, inc.
