# Pomodoro Timer

This is a Pomodoro Timer implemented in Python using the Tkinter library. The Pomodoro Technique is a time management method that breaks work into intervals, traditionally 25 minutes in length, separated by short breaks. This timer helps users follow the Pomodoro Technique by providing a visual countdown and tracking completed work sessions.

## Features

- Customizable work duration (default: 25 minutes)
- Customizable short break duration (default: 5 minutes)
- Customizable long break duration (default: 15 minutes)
- Start and reset functionality
- Display of remaining time in minutes and seconds
- Visual indication of work and break periods
- Marking completed work sessions with checkmarks

## Prerequisites

- Python 3.x
- Tkinter library

## How to Run

1. Clone the repository or download the `main.py` file.
2. Open a terminal/command prompt and navigate to the project directory.
3. Run the following command to start the timer:

   ```bash
   python main.py
   ```

4. The Pomodoro Timer window will open.
5. Click the "Start" button to begin the timer.
6. Use the "Reset" button to restart the timer.
7. The timer will automatically switch between work and break periods based on the predefined durations.
8. Completed work sessions will be marked with checkmarks below the timer.

## Customization
You can customize the durations of work, short breaks, and long breaks by modifying the following variables in the main.py file:

```python
WORK_MIN = 25       # Duration of work period in minutes
SHORT_BREAK_MIN = 5 # Duration of short break period in minutes
LONG_BREAK_MIN = 15 # Duration of long break period in minutes
```

Feel free to adjust these values according to your preferences.
