# dockershell

A shell for docker


## How to use

Add the file `dockershell` to your path. Check if it has running permissions:

    chmod +x dockershell

Then, run it:

    $ dockershell
    Type help for available commands and quit to exit the console
    
    docker>

You can navigate through dockershell history with arrows keys. It is stored in `~/.dockershell_history`

Autocomplete is also supported, just press TAB to get a list of options.


## Additional commands from dockershell

- `b` Shortcut for `bash`
- `bash` Run bash interactively in a new container
- `ll` List all containers and all images
- `h` Shortcut for `help`
- `hist` Shortcut for `history`
- `q` Shortcut for `quit`
- `quit` Exit this shell
