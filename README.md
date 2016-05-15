# Raptor

Raptor is a set of utilities for managing Racket projects.

## Usage

    $ raptor [command]

Available commands:

 - `help` prints help.
 - `run <binary>` runs a Racket script in the `bin` directory of your project.
   For example, if you have a Racket script `bin/hello`, `raptor run hello` will
   execute that script. Collections in your project will be made available to
   this script.
 - `test` runs tests with `raco test` in all directories in your project.
 - `doc` renders Scribble files in the `doc` directory of your project.
