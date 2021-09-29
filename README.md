🏋🏽‍♀️ Compound Operators Cardio 2.0🏋🏽‍♀️
=================================
We are going to get some more practice with compound operators and conditional expressions in preperation for our conditioals project!  
![](https://media.giphy.com/media/hWddcO7xQWCqIew5rH/giphy.gif)

`.value`
--------
This practice repl.it will require you to use the `.value` propery with `document.querySelector()`. The value property sets or returns the value contained within a form, text input field, drop down menu, etc. For example, if we have a space that we want a user to type in their age, in order to return that value from the text input field when a button is clicked, we would need to do the following:
```javascript
var button = document.querySelector(#button);
var age = document.querySelector(#age);
button.addEventListener("click", function(){
  // Updates the value of age to the value that is inside the text input field that has an id of age.
  age = document.querySelector("#age").value;
})
```

TASKS FOR TODAY
--------------
1. The code below will get the information from the #answer1 text area every time the button is clicked. **INSIDE** the event listener, check if the user's guess is equal to the secretNumber. Return a message based on 3 possible cases: 
a. They were right
b.  Their guess was higher than the number, and
c.  Their guess was lower than the number.  
![](https://media.giphy.com/media/L7z02o6mjwKArO18W9/giphy.gif)

2. Are you a teenager? The two variables below will store the age and the second button. If the user is between the ages of 13 and 19, return a message that they are a teenager. Otherwise return a message telling them they are not a teenager.  
![](https://media.giphy.com/media/BKt10hBCAwv5TxuTas/giphy.gif)

3. Ask the user the day of the week and their age (you can use the previous age variable). 
a. If it is Saturday or Sunday and they are a teenager, tell them they can sleep in. 
b. If it is not Saturday or Sunday (i.e. it's a school day) and they are a teenager, tell them to go to school. 
c. If they are not a teenager and it is not a weekend, tell them to go to work.  
![](https://media.giphy.com/media/xVE3t6XN038ITJtiP0/giphy.gif)

4. You are applying for a scholarship. The scholarship requires that you have above a 3.0 GPA and above a 1100 on the SAT. Write a program that:
a. Asks the user for their GPA
b. Ask the user for their SAT score
c. Prints out (1) "You can apply!" if they meet both requirements, (2) prints out "increase your GPA" if they are just missing the GPA requirement, (3) prints out "increase your SAT score" if they are just missing the SAT requirement, and (4) prints out "increase GPA and SAT" if they are missing both requirements.  
![](https://media.giphy.com/media/LaYSoNDgfFFHGKUP5b/giphy.gif)

5. Ask the user to put in the current temperature. Ask them also to put in the current weather (e.g. sunny, rainiy, snowing, etc). 
a. If it is below 30 degrees or it is snowing, tell them they need to bring warm clothing today. 
b. If it is below 50 degrees or it is raining, tell them to wear a jacket. 
c. Otherwise, tell them that it looks like a good day outside.  
![](https://media.giphy.com/media/CThZK1DSD3xO9ih8Fx/giphy.gif)

6. Add your own question and input to the HTML. Create the code in the `script.js` file to process the user input.