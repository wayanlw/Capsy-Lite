# Capsy-Lite
This is the Lite version of the [Capsy](https://github.com/wayanlw/Capsy) App.

## Super efficient keyboard workflow with the underutilized CapsLock key

After using the keyboard for so many years and trying to optimize its use in every possible way, I concluded that the design of the qwerty keyboard is not as efficient as it could be. I got inspired to look for a solution after using the VIM editor, whose philosophy is minimizing hand movements.

To test my hypothesis, I observed my keyboard usage over a month using a keylogger script. I observed frequently used key-combinations and corresponding hand movements. And this uncovered the amount of unnecessary hand movements that we do while using the keyboard for day-to-day work. Almost all the frequently used key combinations required significant hand movement.


| Rank | Key Combination | Hand Movement                                                                                     | Capsy Key binding                                                                                        | Capsy Hand Movement                                 |
| ---- | --------------- | ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| 1    | Alt+tab         | Left hand Left & down to alt key                                                                  | Capslock + z                                                                                             | No Movement                                         |
| 2    | Backspace       | Right hand up to BS key. When used with the mouse have to take the right hand away from the mouse | Capslock + b (For left hand) <br> Capslock + n (For right hand)                                          | No Movement. Can be used with mouse simultaneously. |
| 3    | Esc             | Left hand up and right to ESC                                                                     | Capslock + q                                                                                             | No Movement                                         |
| 5    | Enter           | Minimal                                                                                           | Capslock + c (for left hand) <br> Capslock + / (For right hand) <br> Side Mouse Button (Used with mouse) | No Movement. Can be used with mouse simultaneously. |
| 6    | Arrows          | Right hand right and down to the arrow key area                                                   | Capslock + ijlk                                                                                          | No Movement. Can be used with mouse simultaneously. |
| 7    | Cntrl-v (Paste) | Left hand down and left. One finger to ctrl and the other to v                                    | Capslock + f                                                                                             | No movement                                         |
| 8    | Delete          | Right hand right. When used with the mouse have to take the right hand away from the mouse        | Capslock + v (For left hand) <br> Capslock + , (for right hand)                                          | No movement                                         |
| 9    | Ctrl+c (Copy)   | Left hand down and left. One finger to ctrl and the other to c                                    | Capslock + d                                                                                             | No movement                                         |
| 10   | Ctrl+z (Undo)   | Left hand down and left. One finger to ctrl and the other to z                                    | Capslock + e                                                                                             | No movement                                         |

This script tries to
1. Minimize hand movements while using the keyboard.
2. Enhance **Keyboard-Mouse** parallel use experience. (Using keyboard with the left hand and mouse with the right)

#### Credits & Inspirations
- [VIM](https://www.vim.org/)
- [Daniel Kvarfordt](https://gist.github.com/Danik/5808330)
- [ThatOneCoder](https://github.com/ThatOneCoder/ahk/blob/master/Wynshaft.ahk.txt)
- [Gustavo Duarte](http://duartes.org/gustavo/blog/post/home-row-computing)

This script has saved me a ton of time. I run this on every computer that I use. The size of the program is less than 1 MB and it doesn't require admin privileges.

#### Functionality:
- Deactivates Capslock for normal (accidental) use.
- Use CapsLock and Right-Shift keys as modifier keys
- Hold the Capslock and drag any window with the right mouse button (not just the title bar).
- Access the following functions when pressing Capslock:

**Disclaimer -  Once the combinations get into your muscle memory, the script becomes very addictive. If you are switching computers frequently (Eg. IT support) please be mindful of it.**
# Installation Instructions
1. Download ` Capsy.exe ` on your computer
2. Simply run the program by double-clicking.
3. Doesn't require admin privileges

If you know how to use [Autohotkey](https://www.autohotkey.com/), you can download the script ` Capsy.ahk ` and change it to suit your own needs.

# Usage Instructions

## Navigation Keys

| Function                                                                           | Hotkey           | Simulated Keys           |
| ---------------------------------------------------------------------------------- | ---------------- | ------------------------ |
| Up Arrow                                                                           | ` Capslock + i ` | {Up}                     |
| Left Arrow                                                                         | ` Capslock + j ` | {Left}                   |
| Down Arrow                                                                         | ` Capslock + k ` | {Down}                   |
| Right Arrow                                                                        | ` Capslock + l ` | {Right}                  |
| -----------------                                                                  | ---------        | ------------------------ |
| Ctrl + Left Arrow                                                                  | ` Capslock + h ` | {Ctrl}+{Left}            |
| Ctrl + Rigth Arrow                                                                 | ` Capslock + ; ` | {Ctrl}+{Right}           |
| -----------------                                                                  | ---------        | ------------------------ |
| Page Up                                                                            | ` Capslock + u ` | {pgUp}                   |
| Page Down                                                                          | ` Capslock + o ` | {pgDn}                   |
| -----------------                                                                  | ---------        | ------------------------ |
| Home (Go to the beginning of a line)                                               | ` Capslock + y ` | {Home}                   |
| End (Go to the end of a line)                                                      | ` Capslock + p ` | {End}                    |
| Go to the beginning of the page                                                    | ` Capslock + 5 ` | {Ctrl}+{Home}            |
| Go to the beginning of the page                                                    | ` Capslock + 6 ` | {Ctrl}+{End}             |
| -----------------                                                                  | ---------        | ------------------------ |
| * All navigation keys functions with holding Shift key for Selection/Highlighting. |                  |                          |


<br>

## Action Keys
| Function                                                        | Hotkey                           | Simulated Keys                                  |
| --------------------------------------------------------------- | -------------------------------- | ----------------------------------------------- |
| Escape                                                          | ` Capslock + q `                 | {Esc}                                           |
| Enter (Using Left Hand)                                         | ` Capslock + c `                 | {Enter}                                         |
| Delete                                                          | ` Capslock + v `                 | {Delete}                                        |
| BackSpace                                                       | ` Capslock + b `                 | {BS}                                            |
| -----------------                                               | ---------                        | ------------------------                        |
| Backspace (Right Hand)                                          | ` Capslock + n `                 | {BS}                                            |
| Backspace preceding word                                        | ` Capslock + m `                 | {Ctrl}+{BS}                                     |
| Delete                                                          | ` Capslock + , `                 | {Delete}                                        |
| Delete the next word                                            | ` Capslock + . `                 | {Ctrl}+{Delete}                                 |
| Enter (Using Right Hand)                                        | ` Capslock + / `                 | {Enter}                                         |
| -----------------                                               | ---------                        | ------------------------                        |
| Undo                                                            | ` Capslock + e `                 | {Ctrl}+z                                        |
| Redo                                                            | ` Capslock + r `                 | {Ctrl}+y                                        |
| -----------------                                               | ---------                        | ------------------------                        |
| Cut                                                             | ` Capslock + s `                 | {Ctrl}+x                                        |
| Copy                                                            | ` Capslock + d `                 | {Ctrl}+c                                        |
| Paste                                                           | ` Capslock + f `                 | {Ctrl}+v                                        |
| -----------------                                               | ---------                        | ------------------------                        |
| Delete Line                                                     | ` Capslock + g `                 | {Home}  {Shift}+{End}  {del}                    |
| Copy Line                                                       | ` Capslock + g (pressed twice) ` | {Home}  {Shift}+{End}  {Ctrl}+c                 |
| Select Line                                                     | ` Capslock + g (hold) `          | {Home}  {Shift}+{End}                           |
| Select and Copy current word                                    | ` capslock + t `                 | {Ctrl}+{Left}  {Shift}+{Ctrl}+{Right}  {Ctrl}+c |
| Delete current word                                             | ` capslock + t (pressed twice) ` | {Ctrl}+{Left}  {Shift}+{Ctrl}+{Right}  {del}+   |
| -----------------                                               | ---------                        | ------------------------                        |
| Copy Line                                                       | ` Capslock + g `                 | {Home}  {Shift}+{End}  {Ctrl}+c                 |
| Delete Line                                                     | ` Capslock + g (pressed twice) ` | {Home}  {Shift}+{End}  {del}                    |
| Select Line                                                     | ` Capslock + g (hold) `          | {Home}  {Shift}+{End}                           |
| -----------------                                               | ---------                        | ------------------------                        |
| Sorround the selection with curly braces                        | ` Capslock + space + [ `         | Converts xxx in to {xxx}                        |
| Sorround with Parnthesis                                        | ` Capslock + space + ( `         | Converts xxx in to (xxx)                        |
| Sorround with Quotation Marks                                   | ` Capslock + space + ' `         | Converts xxx in to "xxx"                        |
| -----------------                                               | ---------                        | ------------------------                        |
| Save                                                            | ` Capslock + a `                 | {Ctrl}+s                                        |
| Save as                                                         | ` Capslock + a (pressed twice) ` | {Ctrl}+{Shift}+s                                |
| -----------------                                               | ---------                        | ------------------------                        |
| Cycle open applications                                         | `Capslock + z `                    | {Alt}+{Tab}                                     |
| -----------------                                               | ---------                        | ------------------------                        |
| Find                                                            | `Capslock + x`                     | {Ctrl}+f                                        |
| Find selection (pastes the current selection to the search box) | `Capslock + x (Long press`)        | {Ctrl}+c {Ctrl}+f                               |


<br>

## Special key combinations

| Function                                            | Hotkey                      | Simulated Keys                                                          |
| --------------------------------------------------- | --------------------------- | ----------------------------------------------------------------------- |
| Shift (Can be used in combinations with other keys) | `Capslock + Tab `           | {Shift}                                                                 |
| ----                                                | ----                        | ----                                                                    |
| Enter Blank line below                              | `capslock + enter `         | {End}{enter}                                                            |
| Enter Blank line above                              | `capslock + space + enter ` | {Home}{enter}{Up}                                                       |
| ----                                                | ----                        | ----                                                                    |
| Duplicate the current line                          | `capslock + PgUp `          | {Home}   {Shift}+{End}  {Ctrl}+c  {End}  {Enter}  {Ctrl}+v  {up}  {End} |
| Duplicate the current line Down                     | `capslock + PgDown `        | {Home}   {Shift}+{End}  {Ctrl}+c  {End}  {Enter} {Ctrl}+v               |
| ----                                                | ----                        | ----                                                                    |

<br>

## Web Search
| Function                     | Hotkey              |
| ---------------------------- | ------------------- |
| Search Web                   | ` Win + s `         |
| Search selection in Web      | ` Win + Shift + s ` |
| Serach Youtube               | ` Win + y `         |
| Search Seleection in Youtube | ` Win + Shift + y ` |

<br>

## Window Management
| Function                 | Hotkey                                                                                   | Simulated Keys |
| ------------------------ | ---------------------------------------------------------------------------------------- | -------------- |
| Close tab / instance     | `Alt + q `                                                                               | {Ctrl}+{w}     |
| Exit Current Application | `Alt + Shift + q `                                                                       | {Alt}+{F4}     |
| Move windows             | Drag the window from anywhere with the right mouse button whilst holding the Capsloc Key |                |

<br>

## Quick copy text

| Function                                                            | Hotkey           |
| ------------------------------------------------------------------- | ---------------- |
| Quick copy to Notepad                                               | `Ctrl+Alt+c`       |
| Select the App to be copied to (Activate the app before the hotkey) | `Ctrl+Win+Shift+z` |
| Copy selection to the selected app                                  | `Shift+Alt+c`    |
| Reset the App                                                       | `Ctrl+Win+r`       |


## Toggle CapsLock

| Function            | Hotkey         |
| ------------------- | -------------- |
| Toggle Capslock key | `win + capslock` |
| Exit                | `Right Ctrl + q` |

<br>