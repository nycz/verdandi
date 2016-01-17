verdandi
========

A sapfo derived program to organize a diary.


Index page
----------
Each entry represents one day, and each day only has one entry.
Each entry has tags and is automatically created at a specified time (or asap after start).
Entries can be filtered on date (month, day and year), length (of the bundled file), or tags.
Should entries have the option for a short summary/header/description in the index view or just tags + date?


File structure
--------------
20XX (dir)
  - january (dir)
    - 01.txt
    - 02.txt
    - ...
    - 31.txt

The first row of the file is its metadata (tags, possibly something more).


Other views
-----------
Month or week layout?


Journaling
----------
There's a built-in simple text editor (similar to backstory editor in sapfo?) to write something about the day. Either in a loose window, in a new view (aka as backstory and viewer in sapfo) or splitscreen.
Possibly a command to open it in something else (kalpana) instead?


Scheduling-ish
--------------
Todo-like automagic tags that show up on specified days (or dates? prolly something regular). If they're not confirmed they stay unconfirmed (probably just a question mark or something as a suffix) to show that they were meant to have been done but weren't.
Possibly also an easy command to confirm a todo-tag which is syntax sugar for removing the question mark at the end.
Possible ALSO some kind of notifications, either only inside verdandi or in the actual os too/instead. Could be just a popup-box or some thing along the lines of qbittorrent's notifications or something using a third party library.