# Overview
Dustbin is a small, self-contained web app that demonstrates desktop-friendly drag-and-drop to discard items into a trash bin. It supports:
- Adding items
- Dragging items to the dustbin to move them to Trash
- Keyboard shortcuts (Delete/Backspace or T) to send focused items to Trash
- A Trash modal to restore items or delete them permanently
- Undo after trashing an item
- Local storage persistence (data stays in your browser)
- Mobile-friendly buttons for trash/restore actions

# Setup
No build steps or dependencies are required.

1. Download index.html.
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari).

Everything (HTML, CSS, JS) is embedded and works offline.

# Usage
- Add items: Type in the input and press Add or Enter.
- Move to Trash:
  - Drag an item onto the dustbin at the bottom-right, or
  - Click the trash button on the item, or
  - Focus the item and press Delete/Backspace (or T).
- Trash:
  - Click the dustbin or the “Open Trash” button to open Trash.
  - Restore an item with the restore button.
  - Delete permanently with the X button.
  - Restore All or Empty Trash from the footer controls.
- Undo: After moving to Trash, click Undo in the toast to restore quickly.
- Persistence: Your items and trash are saved automatically in localStorage.