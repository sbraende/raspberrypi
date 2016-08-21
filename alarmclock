# Import libraries.
import os
import time
from datetime import datetime
import webbrowser

now = datetime.now()
currentHour = now.hour
currentMinute = now.minute
currentHour = str (now.hour)
currentMinute = str (now.minute)
currentTime = currentHour + " " + currentMinute
print ("The current time is: " + currentTime)

# User input alarmTime.
alarmTime = input ("Choose your time (TT TT): ") 
print ("You have chosen current alarm time: " + alarmTime)

# Convert user input to string.
alarmTime = str (alarmTime)

# Compare currentTime to set alarm time set by user.
while currentTime != alarmTime:
    now = datetime.now()
    currentHour = now.hour
    currentMinute = now.minute
    currentHour = str (now.hour)
    currentMinute = str (now.minute)
    currentTime = currentHour + " " + currentMinute
    print ("The current time is: " + currentTime + " and you have set an alarm for: " + alarmTime)
else:
    webbrowser.open('https://www.youtube.com/watch?v=Ysb4B2c62Ok') 
    print ("You are fucking amazing")

# Cleanup
print ("Program end")
