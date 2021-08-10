Text input method for 12-key keypad, where you press two keys at the same time.

Pressing two adjacent keys adds 17 key combinations, which results in 29 total keys,
so the keypad can fit 26 Latin letters, Space, Period, and Shift keys,
without using predictive text input or repetitive keypresses.

It works better on small phones with tiny buttons.

Only Latin alphabet is supported. Many other languages use more than 26 letters,
so Russian text input is not possible, unless you are okay with removing all vowels.

The app itself is a note-taking app with minimal functionality.
KaiOS does not support keyboard apps, so the text input can only be used inside one app.

=== Key table

| Key | Letter |
|-----|--------|
| 1   | Period |
| 2   | a      |
| 21  | b      |
| 25  | c      |
| 3   | d      |
| 32  | e      |
| 36  | f      |
| 4   | g      |
| 41  | h      |
| 45  | i      |
| 5   | j      |
| 58  | k      |
| 56  | l      |
| 6   | m      |
| 69  | n      |
| 7   | o      |
| 74  | p      |
| 78  | q      |
| 7*  | r      |
| 8   | s      |
| 80  | t      |
| 89  | u      |
| 9   | v      |
| 9#  | w      |
| *   | x      |
| *0  | y      |
| 0   | Space  |
| 0#  | z      |
| #   | Shift  |

=== Compilation and installation

To install application.zip to your device, launch command:

git submodule update --init --recursive

Follow instructions in make-kaios-install/README.md to download xulrunner with xpcshell tool, and adb tool.

On Debian, you can install adb from system packages:

sudo apt-get install adb

Enable debug mode in your device by entering secret code on your home screen:

    *#*#33284#*#*

Plug in USB cable, run install.sh

You should see your app in the device app list, install script freezes at the end, you can kill it with Ctrl-C
