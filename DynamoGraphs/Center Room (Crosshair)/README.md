## Centering Room
Room crosshair can be everywhere - this graph move it to the center. This way if you use tag all rooms, all the tags should be at the center of the room too.

- Run the top bits first. This essentially center all the rooms base on it's geometry (well if it's simple enough)
> ###### I didn't have time to investigate weird shapes - but assuming this is not common anyway.)

- There are 2 ways to go from here.
    - Delete all existing room tags in the view and recreate using tag all.
    - Unfreeze the Vector solver (***Unfreeze Me*** node) and run the graph again.

>Self noting: Transaction Start Needed to move element position in the current session. (Could be wrong but this is where I landed after 1 hours...)

<details open="open">
<summary>Video Tutorial</summary>
