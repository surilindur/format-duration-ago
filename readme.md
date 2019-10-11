# Format Duration Ago

Experimental tiny add-on for The Elder Scrolls Online to change the time format displayed in guild member lists, guild history, friend lists, email and other places. The default format simply states how many minutes/hours/days/months ago something happened. The add-on here allows displaying a specific and customisable time format.

Unfortunately, the same function is also used by things such as the large announcements of guild store sales in the middle of the screen from Master Merchant, so the elegance of any custom date and time formats may depend on which part of the UI it appears in.

The add-on achieves custom time format by overriding the global `ZO_FormatDurationAgo` function used throughout the game user interface. The function is defined in the [global time functions library](https://github.com/esoui/esoui/blob/master/esoui/libraries/globals/time.lua).

This add-on requires LibAddonMenu-2.0 to function. No other requirements.
