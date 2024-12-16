# HTML-runner
Simple editor for running HTML code (for personal use)

- Use confirm instead of alert to stop running when you click cancel, but sometimes it may not take effect.
- Debounce function, set the time interval for automatically running the code debounce function.
- Endless loop protection will pop up a window to remind you when the code executes too many loops, and you can terminate the code running.However, this function will require pre-injection of some code. If your code can't run normally, you can turn off this option.
- At present, the console only supports part of the methods (it is only a simple simulation, and certainly cannot be compared with other professional console displays).You can run console.table(console) in the JavaScript code box to see what methods are supported, or just call them directly, and an error will be displayed if they are not supported.
- Emergency stop can stop the code from running to prevent it from getting stuck, but usually, you can't click this button if it is stuck.

Self-use code runs, so some of the code may be written casually, and there may be some imperfections.
