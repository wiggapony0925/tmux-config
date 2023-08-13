# tmux-config

# TMUX Commands

## Starting and Managing Sessions

- **Start a new session**: 
    ```bash
    tmux
    ```

- **Start a new session with a name**:
    ```bash
    tmux new-session -s session_name
    ```

- **Attach to a session**:
    ```bash
    tmux attach -t session_name
    ```

- **List all sessions**:
    ```bash
    tmux list-sessions
    ```

- **Detach from a session**: 
    - `Ctrl-a d`

## Windows and Panes

- **Create a new window**:
    - `Ctrl-a c`

- **Switch to the next window**:
    - `Ctrl-a n`

- **Switch to the previous window**:
    - `Ctrl-a p`

- **Rename the current window**:
    - `Ctrl-a ,`

- **Close the current window or pane**:
    - Window: `Ctrl-a &`
    - Pane: `Ctrl-a x`

- **Split pane vertically**:
    - `Ctrl-a %` (or `Ctrl-a -` based on your config)

- **Split pane horizontally**:
    - `Ctrl-a "` (or `Ctrl-a \` based on your config)

- **Switch to the next pane**:
    - `Ctrl-a o`

- **Resize pane**:
    - Hold `Ctrl-a` and press one of the arrow keys.

## Miscellaneous

- **Scrolling in tmux**:
    - Enter scroll mode: `Ctrl-a [`
    - Use arrow keys to scroll.
    - Exit scroll mode: `q`

- **Reload tmux configuration**:
    - `Ctrl-a :` then type `source-file ~/.tmux.conf`

- **Show all keybindings**:
    - `Ctrl-a ?`

> **Note**: In this configuration, the prefix key is set to `Ctrl-a` instead of the default `Ctrl-b`.
