---
layout: post
title: Remember, remember, the Fifth of November
description: Was this collaborative?
---

## This was an interesting assignment.

I made numerous edits to scripts last night and this morning, trying to work my own original into something that worked, which eventually did happen after much searching for code clues and trial and error. I didn't want to touch what was already in the repo, the *total collaborative work* for which others deserve credit for the Eureka moments - until I'd figured out what was going on and what worked and why. So I have put my version **questionnaire.sh** in the folder alongside _script.sh_, and both scripts output to answers.csv.

I had found another piece of code in my search for answers that wrote a date stamp at the end, but it was harder to resolve it into the rest of the response entries in a neat little line. Without neat little lines, the csv isn't useful. So in the end my script ended up looking essentially like the version we had all worked on.

The only real changes I made to the final script were to add commas to the output, and I removed the echo commands that were outputting user responses to the command line. I tested both scripts and they both work, and I figured out that the double ">>" was the key to appending the output file rather than overwriting it. The current answers.csv file has output from running both scripts multiple times. 

I have left it up to my collaborators to decide whether both scripts remain in the repository that we all worked on.