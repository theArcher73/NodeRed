# NodeRed

## Subflow timesplit

**Description**

This subflow has a separate output for each full hour and for the time periods 00:00-06:00, 06:00-07:30, 07:30-22:30 and 22:30-24:00, at which it makes the timestamp received at the input available.
The subflow can be adjusted individually.

**Requirements** 

node-red-contrib-weekday & node-red-contrib-time-range-switch
