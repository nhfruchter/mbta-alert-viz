# mbta-alert-viz
Visualizations of MBTA alert data for red line

## What is this?
The Red Line is a crucial public transit artery in Boston, but is also notoriously unreliable.

A while back, I asked the MBTA's developer office for data on historical Red Line alerts and they gave me a dump of all service alerts up to that day. I recently got a refresh of all 2016 alerts and decided to look at 2016's full set of alerts.

I took all the alerts, filtered out ones that didn't involve the Red Line, and then removed all alerts that had a "cause" related to construction work, police actions, and medical emergencies. (I figured those didn't directly relate to track or train problems.)

I then labeled stations present in the alert text for issues "at" or "near" stations, or "between" stations. "At" or "near" counted for one issue at a station; "between" incremented the two mentioned stations by a smaller amount.

See also: [Reddit discussion](https://www.reddit.com/r/boston/comments/72fp5e/red_line_problems_in_2016_a_map/).

## The data

## License
Data used here was kindly provided by developer@mbta.com. Use of MBTA data is subject to the MassDOT Developer's License Agreement which can be found at http://www.massdot.state.ma.us/DevelopersData.aspx.
