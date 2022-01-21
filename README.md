# Starting GDB:

  $ gdb name-of-executable
  
# Commands table

| Params | Description |
|:------:| :-----------|
| b/break    | Add break point |
| r/run      | Runs the program until a breakpoint or error |
| c          | Continues running the program until the next breakpoint or error |
| *f         | Runs until the current function is finished |
| s/step     | step into next line or into function |
| n/next/n N | step next line, don't into function |
| p | Prints the current value of the variable "var" |
| bt | Prints a stack trace |
| u | Goes up a level in the stack |
| d | Goes down a level in the stack |
| q | Quits gdb |
| gdb -tui | GDB Text User Interface |

**Refer:** http://www.yolinux.com/TUTORIALS/GDB-Commands.html
