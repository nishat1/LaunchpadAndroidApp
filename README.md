# LaunchpadAndroidApp
This app was created for our Computer Engineering project course. This last project was an open ended project with a few requirements including: integrating an Arduino, Raspberry Pi, web server, and a website or app. Within a group of 6, my partner, Karn, and I took the role of implementing the app. 

The idea for this project was based around the concept of integrating music, Computer Engineering, and Internet-of-Things. We decided to create a physical launchpad that would using the Arduino and Raspberry Pi to play uploaded sounds. The sounds would be uploaded/updated using an Android app. 

The role of the app was to essentially send requests to a web server with updated button sounds. The app visually mimics a physical launchpad where a user can listen to sounds on the app and "send" a prefered layout to the physical launchpad. The app has a drawer of sounds and when each sound is clicked in "sound play mode", a sound file is played from the web server. A perfered sound can then be assigned to a button. The buttons can then be clicked to play sounds in "sound play mode". The app allows the user to play multiple sounds simultaneously in response to multiple button presses by using background threads. 

The original app with progressive commits is in a private repository from our class CPEN-291. I transferred the work from the private repository to this public repository so the source code can be visible. The app development process spanned 2 weeks. This included brainstorming the layout and tools required for the app, learning web server communication, and integrating our knowledge and ideas. 

Partner for app development: Karn Rahal (https://github.com/krahal)
