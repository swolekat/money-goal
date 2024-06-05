# Money Goal
sammi extension alternative to sub goals

## Reasoning

There were a couple of things that I didn't like about the traditional sub goals:
* bits don't count
* donations don't count
* gifted subs expire so it's always weird to update goals or not hit them
* no real way of storing previous progress for events

So basically I made my own thing that takes bits, subs, and ko-fi donations all into account.

There is a bit of an issue with subs since I assume every user is located in the US. I know there is regional pricing but I'm unable to get the data for a sub when it happens. If you want to change the values feel free to do so by modifying the buttons.

## Prerequisites

If you want to use the kofi trigger, you'll need to get the [ko-fi triggers extension](https://christinak.itch.io/ko-fi-triggers) from Christina K. It's $1 but I think it's worth it.

Other than that, if you've already set up sammi and obs, you don't need to do anything.

## Installation

Go to the latest release and download the `.sef` file. Then in sammi select `SAMMI BRIDGE` on the left, then `Install an Extension`. Select the sef file you downloaded. If it worked, you should see a new deck. Go into the new deck and run the green button. This will create the scene.

## Alternate canvas sizes

I'm assuming you're using a 1920x1080 canvas. If you're not, there's a couple of things you'll need to do.

First, in OBS, update the properties of `moneyGoalForeground` and `moneyGoalBackground` to have your new width.

Next, in the deck that was created, in the `Update ui` button, change the value of the first line from 1920 to whatever your screen size is.


## Customization

Since all of these are obs sources you can change them to look however you like. I, for example, like to have `moneyGoalForeground` have a rainbow filter.

## Changing the Goal

Inside of your sammi folder there will be a new file called `moneyGoal.ini`. You can modify this like a text file. Change the three fields to whatever you'd like.

## Support
This project is free for anyone to use and update. If you need to contact me specifically, stop by my stream at http://twitch.tv/swolekat or leave an issue on github.

If you'd like to send a couple of bucks my way you can do so at my [ko-fi](https://ko-fi.com/swolekat).