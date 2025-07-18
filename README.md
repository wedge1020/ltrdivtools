# ltrdivtools
Letter Division Solution Tools - a set of scripts to facilitate the solving experience of a letter division puzzle

Written in bash, designed to be used specifically with the pctX-style letter division puzzles.

To install, place in your ~/bin and make sure they are executable and that it is in your PATH.

Enjoy!

## scripts
The following scripts are available for use:

  * borrowtakes - formats puzzle for recording borrows and takes
  * equations - generates an "Equations" content section
  * rangetable - generates a range table for the puzzle
  * relationalchains - generates a "Relational Chains" content section
  * statetables - generates a "State Tables" content section

## usage
Use individually, or together in a command-line pipeline to generate content that assists with manual letter division puzzle solving.

### in action
For example:

```
$ cat puzzle | borrowtakes | rangetable
```

or:

```
$ borrowtakes puzzle
```

Tools support direct file access or STDIN redirection (a la pipeline) to use in the scenario that offers greatest productivity.

### getting help
Each tool accepts 'help' as a command-line argument, which will display its particular usage information and exit:

```
$ relationalchains help
```

