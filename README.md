# Mad Lib Generator

The given code in this repository is the outline of a [Mad Lib](https://en.wikipedia.org/wiki/Mad_Libs) generator. A Mad Lib, if you don't know, is a word game whereby a player is asked for several words (nouns, verbs, adjectives, etc), and those words are then inserted into an existing text. In this case, that text is the first few stanzas of Lewis Carrol's [Jabberwocky](https://en.wikipedia.org/wiki/Jabberwocky).

## Clone this repository

First, clone this repository to your local computer, using Visual Studio Code's cloning feature.

Helpful video:

- [cloning a code repository from GitHub to your local machine](https://www.youtube.com/watch?v=axcny0o1NYo).

## Set up Visual Studio Code

Once cloned, set Visual Studio Code to be suitable for Python development using the "command palette":

- set the interpreter to a Python 3.x interpreter, such as that by [`Anaconda`](https://www.anaconda.com/).
- set the linter to by `pylint`.
- set the test framework to be `pytest`.

Helpful video:

- [Setting up Visual Studio Code for Python development](https://www.youtube.com/watch?v=xsXMzyK1M4I)

## Modify the code

The file named `solution.py` contains several functions that must be completed in order for the program to work. Each function contains a description of what it should do.

The only modifications you must make in order to complete this assignment are to these functions in this one file.

### Run the program

To run the program, run the file named `main.py`. The code in this file makes use those functions you have modified in `solution.py` to produce and output the Mad Lib text.

### Verify the output is correct

Running the program should ask for the user to input several words (adjectives, nouns, verbs, etc), and then generate and output the text of Lewis Carrol's Jabberwocky with those words inserted in Mad Lib style.

### Verify that the tests pass

Pytest-based tests are included in the `tests` directory that will help you determine whether each function is operating as expected. If the functions have been completed correctly, all tests should pass. You should not edit any files in the `test` directory.

If the tests do not appear, or seem to never stop loading, open up a Terminal window and run the command, `pytest --collect-only`, to see whether there are any errors in the code that prevent the tests from being discovered.

## Submit your work

Each student must submit this assignment individually. Use Visual Studio Code to perform git `stage`, `commit` and `push` actions to submit. These actions are all available as menu items in Visual Studio Code's Source Control panel.

1. Type a short note about what you have done to the files in the `Message` area, and then type `Command-Enter` (Mac) or `Control-Enter` (Windows) to perform git `stage` and `commit` actions.
1. Click the `...` icon next to the words, "Source Control" and select "Push" to perform the git `push` action. This will upload your work to your repository on GitHub.com.

![Pushing work in Visual Studio Code](./images/vscode_stage_commit_push.png)
