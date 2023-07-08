# Cheatsheet

My handy cheatsheet for my NeoVim and tmux workflow.

## NeoVim

`,` leader key

### Windows

`<C-w>` window

`<C-w> v` vertical split window

`<C-w> s` horizontal split window

`<C-w> c` close window

`<C-w> q` quit window

#### Navigate windows

`<C-w> h` goto left pane

`<C-w> l` goto right pane

`<C-w> k` goto up pane

`<C-w> j` goto down pane

#### File switching

`^` previous file

### Tabs

`gt` goto next tab

### Harpoon

`<leader> a` mark a file and add to harpoon list

`<C-k>` next mark

`<C-j>` previous mark

`<leader>hp` open harpoon window 

### Telescope

`<leader> ff` find file

`<leader> fw` find word, search the current word in file content

`<leader> fg` find grep, search file contents


### Search and replace

`:%s/<search>/<replace>/g` search and replace


### Code comments

`gcc` comment out line


### NvimTree

`<leader> n` toggle NvimTree

---


## tmux

Attach last tmux session.

```sh
tmux a
```

Attach to a named tmux session.

```sh
tmux a -t <session-name>
```

`<C-b>` prefix key

`<prefix> d` dettach from tmux session


### Sessions

`<prefix> :new` new session

`<prefix> $` rename session

`<prefix> s` view sessions only
 

### Windows

`<prefix> w` view sessions and windows

`<prefix> c` create new window

`<prefix> ,` rename window

`<C-h>` previous window

`<C-l>` next window


### Panes

`<prefix> %` vertial split panes

`<prefix> "` horizotal split panes

#### Navigate panes

`<prefix> h` goto left pane

`<prefix> l` goto right pane

`<prefix> k` goto up pane

`<prefix> j` goto down pane

#### Resize panes

`<prefix> H` wider to the left pane

`<prefix> L` wider to the right pane

`<prefix> K` wider to the up pane

`<prefix> J` wider to the down pane

