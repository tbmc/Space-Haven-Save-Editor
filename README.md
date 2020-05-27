# Space Haven Storage Editor
This is a tool to edit the Large Storage's of ships in the game Space Haven.

It currently only looks at all your ship's storage, then changes
the item counts of each storage. It evens out the number of items to
the max of 250.

For example if you have 1 energy rod in one storage it will make it
have 250. If there are more than one item, say 25 items, then each
item count will be 10.

Best practice it to move each item into their own Large Storage, save the
game, then run the script.

## Installing and running

1) Install latest stable version of python 3
1) Download `editor.py`
1) Run `python editor.py`
1) Browse to your save file
1) Have fun!

# Notes
* This it will make a backup of the save. Be sure to clean this up
if you run this multiple times.
* Monster Meat will be skipped as there isn't really a need for it
in game, unless your crew is really hungry.
* Only supports local saves and not cloud saves.
