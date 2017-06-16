---
layout: post
title: "Personal Story"
date: 2017-06-12
---

* * *

### Task 1
**Case Study**

Our first task this semester was to write up a case study on a related subject to do with our Project. I chose a project that was undertaken by a group in New York/New Jersey. The people involved were a part of TheThingsNetwork New York Community. The project was based on smart gardens and utilizing these to help minimize the effects of extreme water events. Such as torrential rain, hurricanes and floods etc.


* * *

### Task 2
**IPtables and Backup**

Another task was to setup some security measures on our server. To do this I followed a guide on setting up iptables

[iptables guide](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-with-ufw-on-ubuntu-14-04)

Part of this task was also to help find a solution for backing up our database that holds all of our node data. This isn't critical right now for testing purposes but will definitely be needed for final product.

Our solution we used was to use the official postgrtes back up that exists as part of postgres. There were some problems with syntax but some research provided a solution. The documentation for the backup can be found here.
* * *

### Task 3
**Gateway/Raspberry pi**

To get ready for our gateway I had to clear the SD card and put a fresh installation of jesse lite onto it. The first step was to archive what the other group had done. This was followed by downloading a copy of jesse lite (lite because it was smaller in size) and writing it to the SD card. I then inserted the card into thew raspberry pi and went onto setting up ssh settings. This was slightly problematic as the keyboard layout was not matching so some solutions had to be researched. 

After this, I tried setting the raspberry pi up for gateway configuration and followed certain guides but it was not working out so was handled by other members of the group. 
* * *

### Task 4  
**Github Pages**

I was tasked with managing our teams github repository. This included archiving past teams work and implementing something different that was more flexible. For this we decided to use static github pages run with Jekyll and formatted with Markdown language. Styling was made easy with several default layouts included when using Jekyll. 

There is a certain process to go through setting up Jekyll locally on your machine and is easier if you have certain operating systems. Basically everything but Windows. Windows does have support but it is limited and can have more issues. One specific problem I ran into while setting up was the way our pages were structured. We were using github pages and not creating directly from the master repository, meaning some changes had to be made so the pages knew where to read the css and layouts from. 

The guides used to set up are below.

#### Installing Jekyll on Windows
Guides used:
* [Jekyll 3 on Windows](https://labs.sverrirs.com/jekyll/)
* [Installation via Chocolatey](http://jekyllrb.com/docs/windows/#installation-via-chocolatey)

* * *

### Reflection
At the beginning of this project it seemed promising with the funds to back up what we thought would be a reliable solution. This however was soon to be discovered not to be the case. As this technology is still fairly new there is not a lot of support or information out there for a low budget solution. 

So our effots became more 'hacky' - trying to get older stuff to work and even our project manager buying his own hardware, although not in the right frequency. 

More research was done and we came to the decision to buy different hardware that seemed to be more promising, had a lot of documentation and support. While waiting for our new toy to arrive we managed to set up a working prototype with the gear we had - just in time for mini showcase! I found the showcase to be a good exercise as I had not had a lot to do with the setup of the server, gateway or node. As I was the only person from group avaliable at the time, I was responsible for moving the hardware and setting it up which in itself taught me a lot about how it worked. 

I think the groups efforts have produced a promising prototype that should be able to be transferred to the new hardware and on the right frequency. I definitely feel like we have made a good start and will have more of an idea of direction for next semester.
Overall it was a slow start but looking back we have come a long way.
