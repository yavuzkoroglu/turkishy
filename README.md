# turkishy
A Turkish Q keyboard layout clone for all MacBooks with few tweaks.

*turkishy* is the same as the standard Turkish Q layout with a few key differences:

1. The dead keys in the standard Turkish Q layout are `^`, `~`, `´`, `¨`, and `` ` ``. These keys are now normal characters in Turkish Y layout. So, the user now can type these characters without having to follow them with another character.
2. CAPS LOCK is now SHIFT LOCK. Typically, a CAPS LOCK only capitalizes the letters on the keyboard. However, a SHIFT LOCK behaves like the user is continuously pressing the SHIFT key. For example, in Turkish Q layout, `SHIFT`+`1` types `!` whereas `CAPS LOCK`+`1` types `1`. In Turkish Y layout, `CAPS LOCK`+`1` types `!`, just like `SHIFT`+`1`.

**NOTE:** *turkishy* layout is superior to the other SHIFT LOCK solutions found in internet because it further implements support for the cases where extra modifiers are also pressed, e.g. `ALT`, `CTRL`+`ALT`, and so on.

**NOTE:** *turkishy* interprets pressing both `SHIFT` and `SHIFT LOCK` as pressing either one of them, unlike some SHIFT LOCK implementations where pressing both cancels each other.

**WARNING:** *turkishy* is never tested with a long keyboard layout with numeric keypad.

All the above changes aim to facilitate coding via Turkish Q keyboards.

This layout is prepared using [Ukelele 3.4.2](https://software.sil.org/ukelele/).

## Table of Contents
1. [Tested Operating Systems](#tested-systems)
2. [Installation](#installation)

<a name="tested-systems"></a>
## Tested Operating Systems
1. macOS Catalina Version 10.15.6

<a name="installation"></a>
## Installation
1. Download and copy the `TurkishY.layout` file to your `"/Library/Keyboard Layouts/"` directory.
2. Restart the OS.
3. Open `System Preferences`.
4. Open `Keyboard`.
5. Go to `Input Source` tab.
6. Press the `+` key.
7. Select `Others` as the language family.
8. Select `Turkish Y` and click `Add`. 
