---
title: "Beginner's Guide to Aegisub"
permalink: /
---

# A Beginner's Guide to Aegisub

![Aegisub Logo](Aegisub-logo.png)

## Introduction

### What is Aegisub?

Simply put, Aegisub is an open-source subtitling software project dedicated to creating quality subtitles. Although it is mostly used by Anime fansubbers (and therefore is partially responsible for the reason why anime is as popular as it is today) it also can be used for create subtitles for any type of video. It supports many different formats for both input and output.

### Why _should_ I care?

Accessibility is a __huge__ issue in tech. Learning how to subtitle your own videos is a great skill that can help not only those with hearing impairments watch your video, but those who may not want listen to the audio component, even possibly due to convienence.

## Getting Started

### Downloading Aegisub

Aegisub source code can be downloaded from [here](https://github.com/Aegisub/Aegisub) and binaries can be downloaded [here](aegisub.org).

### Aquiring video

In order to subtitle a video, you must first have it downloaded to your device. If you wish to subtitle something that is on YouTube, it is highly recommended you use [YouTube-DL](https://youtube-dl.org/).

### Set Up

Once you open up Aegisub, you will want to import your video. To do this, click on `Video` at the top of the window, then select `Open Video`. Navigate to find your video, then select it. 

### Layout
After opening the video you should be able see the video in the upper left hand corner. You can change the size of the video at any time by changing the percent under the bottom right corner of the video. 

To the right of the video, you can see an audio graph, which allows you to select audio, allowing you to listen to snippets of dialogue and subtitle a line. 

To the bottom of the audio graph, you can see the text box, which allows you to edit the current line, along with options to change the subtitle style (that includes making the text bigger, and therefore easier to see on the video itself), and labeling which character is speaking this line. 

On the bottom, you can see all lines in the subtitle file, and double click to focus on that line.

## Subtitling

### Selecting Audio

First, we must select the line of dialogue we wish to subtitle first. First, play the video until you come across the first line of dialogue. Then, go the the audio graph and select what you think the end of the line is by right clicking on the end of the audio snippet, then left clicking on what you think is the beginning of the audio snippet. Try to be as exact as you can. Hit the space bar on your keyboard to play the audio you have selected. Adjust until you are comfortable with your selection.

### Assigning Text to the Audio Selection

Now, select the text box and enter what the audio snippet says. After you are done, hit the `Enter` or `Return` key, depending on what keyboard you are using. It will then move the audio that comes after, and create a new empty line. Repeat this process until each line of dialogue has been subtitled.

## Clean Up

The text is all there, but the timing needs some fixing. At this point, if the subtitles are used as is, people will not have enough time to process the subtitles. This is why we use lead-in and lead-out adjustments. To do this, go back to each line and press `C` to add lead-in time and `V` to lead out. Make sure the lines do not overlap each other.

## Saving/Exporting

Aegisub supports a variety of subtitle formats. In fact, have a list:

* Advanced SubStation Alpha (.ass)
* EBU Subtitling Format (.stl)
* Adobe Encore (.encore.txt)
* MicroDVD (.sub)
* SubRip (.srt) 
* Substation Alpha (.ssa)
* MPEG-4 Streaming Text (.ttxt)
* Plain-Text (.txt)
* TranStation (.transtation.txt)

You can see above that these subtitle files are mostly stored in some modified form of plain text, which means it is very easy to modify them with Notepad, if you happen to spot a minor error.

By default, Aegisub will save in it's preferred .ASS format (hey, I wasn't the one who came up with it). This is fine for saving the subtitle to either work on later, or to have as a reference. However, to make it compatible with YouTube/Google Drive and most players, it should be in .SRT format, which doesn't contain any styling information. To export in a different format, click on `File`, then select `Export Subtitles...`, then select `Export...`. Under `Save as Type`, you should select `SubRip` for maximum compatibility. In addition, if you name the subtitle file the same as the video (as in `Video.srt` for `Video.mp4`), the player will load the subtitle with the video automatically.


## Resources and Contact Info

A good series of tutorial videos (the ones that taught me how to use this program) can be found [here](https://www.youtube.com/watch?v=4gXF6Y-v6BE&list=PLqazFFzUAPc7BgGTaDAvvsGEoLolq09YP).

[Aegisub Logo](https://en.wikipedia.org/wiki/Aegisub#/media/File:Aegisub-logo.svg)

Last but not least, here is my contact infromation.

Email | Phone Number | GitHub
------|--------------|--------
squireph@msu.edu|(248) 630-5728|https://github.com/philipsquire



