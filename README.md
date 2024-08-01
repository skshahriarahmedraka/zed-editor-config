This configuration provides Vim-like key bindings for an editor. It includes comprehensive key mappings for various contexts and modes, ensuring efficient navigation and editing. Here's an overview of the main key bindings:

### Global Context
- `ctrl-6`: Switch to alternate file (like Vim's `ctrl-^`).

### Editor with Vim Control
#### Navigation
- `h`, `left`, `backspace`: Move left.
- `j`, `down`, `enter`: Move down.
- `k`, `up`: Move up.
- `l`, `right`: Move right.
- `space`: Move right.
- `$`, `end`: Move to end of line.
- `^`: Move to first non-whitespace character.
- `_`: Move to start of line downward.
- `shift-g`: Move to end of document.
- `{`: Move to start of paragraph.
- `}`: Move to end of paragraph.

#### Word and Subword Motions
- `w`, `shift-w`: Next word start.
- `e`, `shift-e`: Next word end.
- `b`, `shift-b`: Previous word start.

#### Searching and Finding
- `/`, `g /`: Search.
- `*`, `#`: Move to next/previous match.
- `n`, `shift-n`: Move to next/previous search result.
- `%`: Go to matching character (e.g., parenthesis, bracket).
- `f`, `t`: Find forward/backward.
- `shift-f`, `shift-t`: Find backward/forward.

#### Marks and Jumps
- `m`: Set mark.
- `'`, `` ` ``: Jump to mark.

#### Miscellaneous
- `ctrl-o`: Jump back.
- `ctrl-i`: Jump forward.
- `escape`, `ctrl-[`: Switch to normal mode.
- `v`: Start visual mode.
- `shift-v`: Start visual line mode.
- `ctrl-v`, `ctrl-q`: Start visual block mode.

### Normal Mode
#### Editing
- `c`, `shift-c`: Change.
- `d`, `shift-d`: Delete.
- `y`, `shift-y`: Yank.
- `i`, `shift-i`: Insert before/first non-whitespace.
- `a`, `shift-a`: Insert after/end of line.
- `x`, `shift-x`: Delete character.
- `o`, `shift-o`: Open new line below/above.
- `~`: Toggle case.
- `ctrl-a`, `ctrl-x`: Increment/decrement number.
- `p`, `shift-p`: Paste.

#### Undo and Redo
- `u`: Undo.
- `ctrl-r`: Redo.

#### Replace
- `r`: Replace single character.
- `s`, `shift-s`: Substitute.

#### Indentation
- `>`, `<`: Indent/outdent.

#### Case Changes
- `g u`: Convert to lowercase.
- `g shift-u`: Convert to uppercase.
- `g ~`: Toggle case.

#### Comments
- `g c c`: Toggle comment.

### Visual Mode
#### Editing
- `u`, `U`: Convert to lowercase/uppercase.
- `o`, `shift-o`: Move to other end.
- `d`, `x`, `shift-d`, `shift-x`: Delete.
- `y`, `shift-y`: Yank.
- `p`, `shift-p`: Paste.
- `c`, `shift-s`, `shift-r`: Change.
- `~`: Toggle case.
- `*`, `#`: Move to next/previous match.
- `ctrl-a`, `ctrl-x`: Increment/decrement.
- `shift-i`: Insert before.
- `shift-a`: Insert after.
- `shift-j`: Join lines.

### Insert Mode
- `escape`, `ctrl-[`, `ctrl-c`: Return to normal mode.
- `ctrl-x ctrl-o`: Show completions.
- `ctrl-w`: Delete previous word.
- `ctrl-u`: Delete to beginning of line.
- `ctrl-t`, `ctrl-d`: Indent/outdent.

### Replace Mode
- `escape`, `ctrl-[`, `ctrl-c`: Return to normal mode.

### Waiting for Input
- `tab`, `enter`: Confirm.
- `escape`, `ctrl-[`: Cancel.

### Search
- `enter`: Submit search.
- `escape`: Dismiss search.

### Project Panel
- `:`, `g /`: Toggle command palette and deploy search.
- `h`, `j`, `k`, `l`: Collapse/expand/select entries.
- `enter`, `o`, `t`, `v`, `p`: Open entry.
- `shift-d`: Delete entry.
- `shift-r`: Rename entry.

### Other Panels
- Similar navigation and selection bindings as in the editor and project panel.

This setup aims to make the editor experience similar to Vim, allowing for efficient text manipulation and navigation while preserving familiar Vim key bindings.

