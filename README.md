# keyLogger
A simple keyLogger using the pynput library.

### Dependencies
Requires pynput library to be installed. You can do this by opening the command prompt/ terminal and typing the following command: 

```pip install pynput```

### Log
By default, the log is created and stored in the same directory as the program. If you want to change the default directory, simply add the desired path in double quotes to the `log_dir` variable.

### Autostart
To start the program at startup, simply add the keyLogger.pyw file to your startup folder and make sure the log file is stored in a different directory so that it does not open up as well during startup.

### Stopping the keyLogger
To stop the keyLogger, simply open the task manager and close all python or pythonw related tasks.

### Future Changes
This is a very basic key logging program and I have a few ideas to make it better:
* Display the name of the window in which the key was pressed
* compile it as a .exe to make the program more versatile and independent.


_I wrote this program out of sheer curiosity and have no intentions to misuse it in any way. I hope whoever looks at this will do the same.__

_I wrote this program by following the tutorial by pyTutorials on [Youtube](https://www.youtube.com/watch?v=x8GbWt56TlY)_

_Link to the pynput repository on GitHub: `https://github.com/moses-palmer/pynput`_
