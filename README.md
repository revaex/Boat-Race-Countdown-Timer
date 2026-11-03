# Boat Race Countdown Timer

A simple voice countdown timer designed for boat race starts, with timed voice announcements and a final-second countdown.

**Live timer:** https://revaex.github.io/Boat-Race-Countdown-Timer/

## Features

- Set a custom countdown in minutes and seconds
- Quick presets for 1, 2, 3, 5 and 10 minutes
- Voice announcements every 30 seconds
- Spoken countdown every second during the final minute
- Pause, resume and reset controls
- End-of-countdown alert
- Optional voice announcements and voice test
- Attempts to keep the screen awake while the timer is running
- Mobile-friendly layout with automatic light/dark appearance

## Using the timer

1. Open the live timer on your phone or computer.
2. Choose a preset or set the minutes and seconds manually.
3. Make sure **Voice announcements** is enabled.
4. Use **Test voice** to check your device volume before the race.
5. Press **Start** when the countdown should begin.

For iPhone use, turn the silent switch off, turn the volume up, and keep the timer open while it is running.

## Voice timing

The timer announces the remaining time every 30 seconds. At one minute it announces **“1 minute. Counting down.”**, then speaks each remaining second until the start. At zero it announces **“Time's up”** and sounds the end alert.

The timer deliberately omits the word **“left”** from its countdown announcements.

## Technology

This is a lightweight static web app built with HTML, CSS and JavaScript. It uses the browser's built-in speech synthesis and audio APIs and does not require an account or server.