# wtr
Wait for a process to finish and run a command.

## Example
```$ wtr -p emerge -c "poweroff"``` Wait for emerge to finish and poweroff the computer.
```$ wtr -p make -c "reboot" -s 5``` Wait for make to finish, wait 5 seconds, and reboot the computer.
### Installation
Run ```# install -m 755 wtr /usr/local/bin/wtr```
