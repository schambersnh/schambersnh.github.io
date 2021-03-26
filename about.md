---
layout: page
title: About
permalink: /about/
---

I am a software developer residing in Middletown, CT. I received my masters in Computer Science from the University of New Hampshire.

Personally, I play three instruments, was part of a college a cappella group, and I am an avid bowler (who won NH states in 2017!)


### Projects
* Toucan: Our team had an issue where upstream data caused a lot of headaches on our side. To have better controls in place, I developed a machine learning solution utilizing AWS sagemaker and the random cut forest algorithm to determine if the files we received from that team were 'normal' or not. The algorithm would return a confidence score, and if it was 2 standard deviations away from the mean, we would warn our team on slack. Three standard deviations? Fail the job, sound the alarms, look into the issue. This **successfully** caught a $90 million dollar potential impact early in 2021, and has been adopted by multiple other teams in the company.

* Down payment saver - Magic Mirror: Grabbed some open source code, and developed a module (the house in the middle) to track how down payment saving is going! Each brick is 1% of your goal towards that eventual dream home. Utilized canvas.js to draw the house, backend is hooked up to a google sheet that's updated manually on a monthly basis with savings, investments, etc. Would love to introduce plaid, or oauth connections to banks in the future.

![image](https://user-images.githubusercontent.com/8736660/112698860-01512880-8e61-11eb-963f-8a82e236ba56.png)


* Pet Insurance App: Also developed at a company hackathon, so the source code is unfortunately locked down. Worked on a team to develop an android app that read vet bills using Tesseract, an open source OCR technology. The app worked well enough, but we had difficulties getting above a 80% success rate.  With more time, I would've went down two avenues to fix this problem. The first would be to use OpenCV to 'massage' the picture into something that the framework had an easier time working with (i.e. removing parts of the image that were irrelevant). The second would be to look into a licensed OCR framework that may have more image processing capabilities. Overall, it was a fun project that I'd like to tackle again at some point in the future. 

* [SPDY vs HTTP /1.1](https://github.com/schambersnh/school/tree/master/spdy): I did an empirical research project as part of my undergraduate focusing on comparing performance between HTTP /1.1 and SPDY. SPDY was the hip new Google proprietary protocol at the time, and it was eventually approved as the working base of HTTP / 2.0, a much needed upgrade. I developed a testing framework in python using Selenium Webdriver to control a network emulator in the middle of my laptop and a webserver to gather mass amounts of data for analysis.

* [Anytime vs Realtime Heuristic Search for Online Planning](https://github.com/UNH-Robotics/real-time-search): Wrote simulation code to compare realtime and anytime heuristic planning for robots. My team's paper was accepted into [SoCS](http://socs17.dreamhosters.com/) in 2016.

* [Chemistry Tutoring Placement](https://github.com/UNH-Chemistry-Tutoring-Placement): Utilized combinatorial optimization algorithms to help the chemistry department map tutors to tutees. My team was responsible for the tree search, while another team tried an iterative local search. This project was originally unappealing to me, but after thinking about it more, and realizing that if 300 students had to be placed in 10 study groups, that's a massive state space of 10^300 possible solutions! It was fun competing to see who could get the better solution with such a complex problem.

### Contact me

Feel free to contact me about any and everything at [stephenchambers515@gmail.com](stephenchambers515@gmail.com)
