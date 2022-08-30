# Bangla-Calendar-Clock

For our level 4 term 1 microcontroller project (EEE-416) we have developed a calendar clock that can show time, date, part of the day, day of the week in Bangla.
We used Dot Led Matrix as display of our calendar clock. We used esp32 as our main controller unit. We segmented our display in different part for showing all the features of our clock. On the upper left part of the clock, we can see the time and on the upper right, the time of the day and day of the week. On the lower half we can see the date in three different calendar (Gregorian, Bangla and Hijri) which are toggled every 20 seconds. The clock synchronizes through wi-fi and the RTC used inside keeps the clock updated even when the power is turned off.

![](calendar%20Clock.jpg)
