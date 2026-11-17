# RoboQuest: example task videos

Anonymous supplementary material for the review of RoboQuest. The same videos are in the supplementary material of the submission.

**Watch all videos in the browser:** https://anonymous.4open.science/w/task-videos-D37B/

The folder `videos/` contains one scripted demonstration per task, taken from the released demonstration dataset. The scripts know the hidden information but explore as an agent without it would, so each video shows the searching, inspection or testing the task requires.

**Layout of every video.** Top: the task, its family and the goal text given to the agent. Middle: the three camera views the agents receive (left scene camera, right scene camera, wrist camera). Bottom: the current stage of the demonstration, from the stage annotation stored with every frame. Puzzle Box also shows the outcome of each attempt. All videos play at 3x speed.

| # | Task | Family | What the video shows |
|---|---|---|---|
| 1 | Search Room | Search | opens compartments until all targets are found |
| 2 | Locked Storage | Search | finds tokens that unlock other compartments |
| 3 | Blackout Search | Search | searches a dark kitchen with a lantern |
| 4 | Painted Cubes | Inspect | turns cubes to read hidden marks, then sorts them |
| 5 | Marked Mugs | Inspect | lifts and tilts vessels to read the labels underneath |
| 6 | Unfamiliar Containers | Inspect | tries different actions until each box opens |
| 7 | Puzzle Box | Test | three blocked attempts before finding an order that opens the box |
| 8 | Stamp Composition | Test | test prints reveal the hidden patterns before the final board |
| 9 | Wobbly Stand | Test | a ball test finds the short leg; a thin shim fails and a thicker one levels it |
| 10 | Odd Parcel | Test | weighs parcels on a balance to find the odd ones |
