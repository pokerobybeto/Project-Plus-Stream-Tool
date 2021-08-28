![preview](https://cdn.discordapp.com/attachments/799303953912168469/881011199783895120/unknown.png)

# Project+-Stream-Tool
*Also available for [Melee](https://github.com/Readek/Melee-Stream-Tool), [Ultimate](https://github.com/pokeroby_beto/Ultimate-Stream-Tool), [Rivals of Aether](https://github.com/Readek/RoA-Stream-Tool) and [Rushdown Revolt](https://github.com/Readek/Rushdown-Revolt-Stream-Tool)!*

So you're interested in doing Project+ streams, huh? Luckily for you, with this tool you'll be able to update all the variables you need for the provided overlays with the provided GUI, and easily customize the overlays to make them your own! 

The tool is free, but if you want to keep supporting the project and other Smash and non related stuff, you can donate me something on [Paypal](https://www.paypal.me/robertofiore2712). Thanks in advance!

---

## Features
- [Handy interface](https://cdn.discordapp.com/attachments/799303953912168469/881017042038321192/unknown.png) to quickly change everything you need, like player names, characters, scores, round, casters...
- Easy and fast setup using a browser source. Drag and drop!
- A game overlay for both [16:9](https://pbs.twimg.com/media/E92NbjHWUAE0lxY?format=jpg&name=large) and [4:3](https://pbs.twimg.com/media/E92NbJ7XMAIyAWb?format=jpg&name=large) is included, with renders and stock icons for all characters and skins!
- A [VS Screen](https://pbs.twimg.com/media/E92NaovWQAQ8hN3?format=jpg&name=large) is also included, to be used in pauses between games.
- Easy to customize! Made in html/javascript, every file can be edited at will!
- This is **not** a Stream Control clone. It doesn't have anything to do with it, everything is custom made.
- If you have any feedback, whether it's an issue with the program or a feature you'd like to see in a future release, you can write down your suggestions in [this form](https://forms.gle/2TLLcnd1nxtHohZs5)

---

## Setup Guide
You can watch [this video](https://www.youtube.com/watch?v=417QjymeOMk) I made or follow the steps below. (It is for Smash Ultimate but it's the same thing).

These are instructions for regular OBS Studio, but I imagine you can do the same with other streaming software:
- Dowmload the ZIP file.
- Extract somewhere.
- Drag and drop `Game Scoreboard 16.9/4.3.html` into OBS, or add a new browser source in OBS pointing at the local file.
- If the source looks weird, manually set the source's propierties to 1920 width and 1080 height, or set your OBS canvas resolution to 1080p, or make the source fit the screen.
- In the source's propierties, change *Use custom frame rate* -> `60` (if streaming at 60fps of course).
- **Also tick** `Refresh browser when scene becomes active`.
- Manage it all with the `Project+ Stream Tool` executable.

Repeat from the 3rd step to add the `VS Screen.html`, though I recommend you to do so on another scene.

### Interface shortcuts!
- Press `Enter` to update.
- Press either `F1` or `F2` to increase P1's or P2's score.
- Press `ESC` to clear player info.

2 basic transitions are included in the `Resources/OBS Transitions` folder, if you don't have a transition yourself of course. To use them on OBS:
- Add a new stinger transition.
- Set the video file to `Game In.webm` or `Swoosh.webm`.
- Transition point -> `350 ms`.
- I recommend you to set the Audio Fade Style to crossfade, just in case.
- On the scene's right click menu, set it to Transition Override to the transition you just created.

The interface will also update basic text files with the match info at `Resources/Texts/Simple Texts/` so you can add them to OBS with ease.


---

## Customizing stuff

Note: unfortunately, the source code is not available to download. 

You can still customize how your Scoreboard and VS screen look by replacing the files in the overlay folder.

While to change the position of the icons and writings you should modify parts of the code contained in the `html` and `js` files.

And most importantly, this project was created using [RoA-Stream-Tool](https://github.com/Readek/RoA-Stream-Tool) as a base, so if you wanna go crazy on customizations, I really recomend you to check out that first, since it's way more documented (and also has a wiki!), especially if you wanna adapt this to other games. This Project+ version is way more locked down.

---

## Credits

The "Project+ Stream Tool" was made by [beto](https://twitter.com/pokeroby_beto). 

This is an upgraded version of the [Melee Stream Tool](https://github.com/Readek/Melee-Stream-Tool) made by [Readek](https://twitter.com/Readeku).

The scoreboard was made by [beto](https://twitter.com/pokeroby_beto). 

All the renders were taken from [Streameta](https://streameta.com/games/#PPlus)

For any feedback you can fill [this form](https://forms.gle/2TLLcnd1nxtHohZs5) or contact [beto](https://twitter.com/pokeroby_beto) on Twitter.
