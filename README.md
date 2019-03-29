You were tasked with writing the UI for controlling a robot. The robot has 2 emotions: Happy, Sad. Each emotion has a level from 1 to 100, and can be adjust by using a slider. 
 
- Initially each emotion is at level 50 (middle) 
- Happy and Sad is opposite of each other. When user tunes up Happy (eg: going from 40 to 50), Sad will go down (eg: going 50 to 40), and vice versa 
- If Sad goes up rapidly, which means if it goes more than 30 levels / second (eg: going from 50 to 81 in less than a second), you output a message: "​Alarm, our robot has a broken heart​" 
- If Happy (or Sad) goes ​exactly​ like this: up / down / up / down / up / down, you output a message: "​Hey operator, stop messing with my Happy (or Sad) sensor​". After that the UI is frozen for 3 seconds. 
- When Happy reaches 100, output a message "​I'm extremely happy !!!​" repeatedly every 0.5 second. When Happy are set from 90 to 100, output that message every 1 second. If Happy goes less than 90, stop outputting. 
 
Requirements - Must use ReactJS - Submit source code to git.nfq.asia - Deploy the application on some (free) service like Heroku for us to see 