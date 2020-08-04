
# Android Controller

This is an android app to allow you to send keyboard controls to a computer.

This uses bluetooth to control your computer, so be sure to have a decently fast and stable internet connection so that you can have a good gaming experience.

## Usage

Download the files under release.

Install the android app on your phone.

Remove previous pairings with the host device in host device bluetooth settings

Open the app

Send a pairing request from the host device to the controlling device

Accept the pairing on the device running Android Controller
    
Use as controller for your host device


## Features
### Support for many keys
This is the full list of what keys are supported:
```
', ,, -, ., /,
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 
;, =, [, \, ], _, `,
a, b, c, d, e, f, g, h, i, j, k, l, m,
n, o, p, q, r, s, t, u, v, w, x, y, z,
up, down, left, right,
home, end, insert, delete, pagedown, pageup, pgdn, pgup, 
fn, f1, f2, f3, f4, f5, f6, f7, f8, f9, f10,
f11, f12
prtsc, prtscr, return, scrolllock, alt, backspace,
capslock, ctrl, enter, esc, shift, space, tab,
volumedown, volumemute, volumeup, win, m1, m2, m3
```
some key support has been dropped from python AndroidController. If you need those keys, use a macro to press Shift to type them.

### Hotkey support
When entering keycodes, seperate them with a space.
For example to do the copy hotkey which is `Ctrl+C`, the keycode will be `ctrl c`.

### Macro support
Ability to send certain precisely timed keystrokes for certain games. (note: preciseness or timeness is not guaranteed)

## License

This project is licensed under the GPL License - see the [LICENSE](LICENSE) file for details

## Acknowledgements
I would like to thank my friends for finding bugs and giving suggestions for my app. Thanks :)

