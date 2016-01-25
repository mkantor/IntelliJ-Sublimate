IntelliJ-Sublimate
==================

A (sane) Sublime / TextMate inspired keymap for IntelliJ 15

## Notes

* I haven't tested this on previous versions of IntelliJ
* Keymap only setup for OSX at this time


## Installation

### Import

Copy the `SubliMate.xml` files to their respective directories in `~/Library/Preferences/IntelliJIdea*/`. For example:

```bash
$ cp ./keymaps/SubliMate.xml ~/Library/Preferences/IntelliJIdea15/keymaps/
```

### Enable

Settings > Keymap > Keymaps: [Select SubliMate]

Settings > Editor > Colors & Fonts > Scheme name: [Select SubliMate]

## Shortcuts

I've mixed together some Sublime and TextMate shortcuts, occasionally breaking IntelliJ shortcuts when necessry. Feel free to fork and help make a better overall collection of shortcuts!

* Open File - ⌘T
* Find Function - ⌘⇧T
* Find - ⌘F
* Find in Path - ⌘⇧F
* Replace - ⌘R or ⌘⌥F
* Replace in Path - ⌘⇧R or ⌘⌥F
* Close Tab - ⌘W
* Reopen Tab - ⌘⇧W
* Close All Tabs - ⌘⌥W
* Close All Other Tabs - ⌘⇧⌥W
* Find Action (Quick Command Palette) - ⌘P or ^⌘T
* Wrap (contents in...) - ⇧^W
* Duplicate Lines (⌘D duplicates line OR selection) - ⌘⇧D
* Delete Line - ⌘K
* Go To Next Match Found (while searching) - ⌘G
* Go To Previous Match Found (while searching) - ⌘⇧G
* Go To Line Number - ^G or ⌘L
* others I'm probably forgetting

I removed ⌘⇧M so that I could reuse it for my system-wide Zoom shortcut
