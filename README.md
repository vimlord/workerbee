# Workerbee

Workerbee is a configurable Python script that allows a user to run background processes (daemons). The script provides an option to run in an interactive mode or by specifying a single command.

All of the information needed to run the command can be found by running it. To see the help, run

```
workerbee -h
```

The program must choose one of 'interactive' mode or 'command' mode. In interactive mode, the user can spawn an arbitrary number of worker bees. In command mode, bees can be hatched directly from the command line, or as part of a script.

This program was developed for the April codejam at the Stevens Computer Science Club.

