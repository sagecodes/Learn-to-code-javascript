# Learn to Code: Introduction to JavaScript

Brought to you by Galvanize. Learn more about the way we teach code at [galvanize.com](http://galvanize.com).

## Overview
The goal of this brief course is to provide you with a fun introduction to the world of web development with Javascript.

#### Here's what we'll be doing:
* Overview of basic JavaScript concepts
* Building a simple application using javascript
* Playing around in the sandbox

#### Before you begin, a quick gut check:
* This course is for absolute beginners
* Feel free to move ahead
* Help others when you can
* Be patient and nice
* You will get through it!

#### What is programming?
Programming is giving your computer a set of instructions to perform a task. 

## Setting up your computer
(Brace yourself...)

#### Please set up the following:
* A web browser to see what we're working on as others see it (Recommend Google Chrome: [chrome.google.com] (http://chrome.google.com))
* We will be using an online text editor for this workshop. You can sign up here: [https://repl.it/](https://repl.it/)

## What is javascript?


## Javascript Basics:

### Data Types:
We're going to stick with the basics, so We wont be going over EVERY data type in javascript, but you you can read a more comprehensive list [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures).  

Feel free to try these code samples out in your developer console!

#### Numbers:

Numbers are written just like you would think. Just the number! No quotes or symbols to worry about.

`25` `100`

Multiple, Add, Divide, Compare

- `5 * 5` | output: 25
- `5 + 5` | output: 10
- `8 / 2` | output: 4
- `8 > 2` | output: true

#### Strings:
Strings can be a collection of letters, symbols and/or numbers. They are made by surrounding the content with quotation marks.

`"Hello, World."`
`"CrAzy Random String 987879896jvdjvda &&(&(@*(*"`

#### Booleans:
You can think of Booleans as yes(true) and no(false)

`true` `false`

We'll go into how to use these in a little bit. For now just remember they exist!


## Variables:
Variable are a way to store information.
This is super useful! You can then receive or update the variable in your program. You'll see this later!

- `var twitter = "@sagecodes";`
- `var score = 0;`


## Comparison Operators:
Comparison Operators are used quite frequently in programming. Its a great way to compare data.

Again we won't cover ALL of the comparison operators in this workshop, but you can see a full list of them [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

- `==` Equal
- `!=` Not Equal
- `>` Greater Than
- `>=` Greater Than or Equal
- `<` Less Than
- `<=` Less Than or Equal

Example:

`current_score >= highest_score`
This would return a boolean value. Depending on the values of these variables this would return either `true` or `false`. Try it in your console using numbers instead of variables!


## Functions
Reduce, Reuse, Recycle

Functions make it easy to reuse code. If you find yourself repeating code you may want to turn it into a function!

Example:
This function takes in two arguments(a, b) and returns the value of them added together. 

```
function add(a, b) {
	return a + b; 
};
```
to use the function call it by writing its name and open/close parenthesis(). With arguments passed inside the parenthesis():

- `add(5,5)` | output: 10
- `add(2,5)` | output: 7

In this simple example you're not saving a ton of code, but imagine a function that uses many lines of code! 


## Conditionals

When writing a program you'll often want to check if data meets a certain condition or not. In javascript you'll often use the `if` statement. This may be followed by `else if` or `else` depending on how many conditions need to be checked.

Example:

```
if (guess == answer) {
    message = "You Win!";
} else if (guess < answer) {
    message = "Your guess is too low!";
} else if (guess > answer){
    message = "your guess is too high!";
} else {
	message = "I think you entered something wrong..."
}
```

## Loops
We're going to go over some of the basic loops in javascript, but yet again we're not going to cover everything, so you may want to read more about loops [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration).

Loops are used when you want to repeat something. You can repeat the exact same thing, or change some variable and repeat the action again.

two common types of loops are `for` and `while`.
`for` loops are often used to run a loop a specified amount of time.

`while` loops are often used to run a loop indefinitely until certain criteria are met.

Example:

This `for` loop will run 5 times, and print out the value of `i` to the console. 

```
var i;
for (i = 1; i <= 5; i++) {
    console.log(i)
}
```

If `i` were set to 1 it would run this loop and print the string until the value of `i` changed. If you run this in your browser it will probably crash it!

```
var i = 0;
while (i == 1) {
    console.log("I will crash your browser")
}
```


## Interact with dialog boxes
using dialog boxes can be simple way to get started interacting with users.

Alert: Pop up information in a dialog box

`alert("Hello, I'm a pop up");`
 
Prompt: get information from a user in dialog box

`prompt("I'm a pop up you can type in!")`


## Lets do some code!
You just learned a lot! Lets put it together and build something!

Sign up if you haven't already and create a new project: https://repl.it/

If you get stuck or want to look ahead at the completed project you can view it [here](https://repl.it/@SageElliott/GuessingGame).

What are some ideas for improvements? 

- Exit on command
- data validation
- input the number range from popup


# YOU DID IT! YOU'RE NOW A PROGRAMMER!

## Welcome! :)


## Upcoming Events!
[Galvanize Web Development Foundations with JavaScript - 7/23 - 8/29](https://www.eventbrite.com/e/galvanize-web-development-foundations-with-javascript-seattle-723-829-tickets-45261516414) - Use Coupon code `learn2code` for 10% off

[Galvanize Seattle Web Development Capstone Showcase (7/19)](https://www.eventbrite.com/e/galvanize-seattle-web-development-capstone-showcase-719-tickets-46775091558?aff=ebdssbdestsearch) See final projects of our graduating class!

[Getting your Foot in the door - 7/25](https://www.eventbrite.com/e/getting-your-foot-in-the-door-tickets-48147532566)


[Learn to Code: Introduction to Git & Github - 7/26](https://www.eventbrite.com/publish?crumb=9d45df65e80535&eid=48139700139)


## What is Galvanize?
###### We are a community!
#### Immersive Bootcamp
- [Data Science](https://www.galvanize.com/seattle/data-science)
- [Web Development](https://www.galvanize.com/seattle/web-development)

#### Part-Time Courses
- [Data Analytics](https://www.galvanize.com/seattle/data-analytics)
- [Web Development Foundations with JavaScript](https://www.galvanize.com/seattle/web-development-foundations)
- [Data Science Fundamentals](https://www.galvanize.com/seattle/data-science-fundamentals)
- [Front End Web Development](https://www.galvanize.com/seattle/front-end-web-development)


#### Co-working Space
[work in our building!](https://www.galvanize.com/entrepreneur)

#### Events 
We host sooo many events! check out out [calendar](https://www.galvanize.com/seattle/events)

## Questions:
Please feel free to reach out to me with any questions!

- Twitter: [@sagecodes](https://twitter.com/@sagecodes)
- LinkedIn: [sageelliott](https://www.linkedin.com/in/sageelliott/) 
- Email: [sage.elliott@galvanize.com](mailto:sage.elliott@galvanize.com)

#### About the Instructors

[Sage Elliott](https://www.linkedin.com/in/sageelliott/) is a technology evangelist for Galvanize based in Seattle. Previously he worked as a Software and hardware engineer for startup around Seattle WA and Melbourne Fl.

You can email him at [sage.elliott@galvanize.com](mailto:age.elliott@galvanize.com) or tweet [@sagecodes](https://twitter.com/sagecodes) for any further questions.





