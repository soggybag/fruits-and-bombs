# Demo Game 

This is a demo app to give an idea of the kinds of code and programming involved with programming web applications. 

View the game live [here](https://make-school-labs.github.io/few-track-demo/). 

Read the section below and follow the suggestions to make changes to the files and make the game.

HTML applications are built on three core technologies: 

- `HTML` - which expresses the structure and content of your application
- `CSS` - describes the style and presentation. 
- `JavaScript` - is the logic and functions

An analogy might be HTML as the bones, CSS as the skin or clothing, and JavaScript as the muscles. 

# Instructions
1. Let's start in the `index.html` file
    1. Find the `title` tag, and change it from `demo game` to something fun
    2. Find the `h1` tag that holds our `boring game title`, and update it with a new fun and exciting name
    3. Find the `link` to our stylesheet and add in the `href` attribute. Change this to: `href="style.css"`
    4. Take a look at what's changed on the page
2. Now over to the `style.css` file
    1. Look through the images folder and find a cool alien you want to play as
    2. In the `:root` rule, change the `--player-image` variable to your favorite alien
    3. Let's also change the `--background-image` to your favorite wall
    4. Now let's change the `--button-color` to something more readable
    5. The buttons look better, but they might look better if they were round. Find the `.button` rule
    6. Inside the `.button` rule lets add a new property `border-radius` and set it to a value of `50%`
3. Now the page looks a lot better, let's make it work
    1. Go back to the `index.html` file and find the `script` tag, add in the `src` attribute
    2. Take a look at what's going on, things are moving now!
    3. Find the `timePerBomb` and `timePerFruit` variable and change them until you find a balance you like.
    4. Find the `makeObject` function, and inside find where the speeds of the objects are set.
    5. change the speed of the bombs and fruits until you find a balance you like
4. Looks good!


<!--

## Todo - 

1. Some tasks to explore programming on the web.
 - Include comments with notes on possible values along side code
 - Building Web Applications 
 - Need a branch to demo the completed game 
 - Master branch should leave out some things that become and activity
 - Links to css files and js files
 - These files might be broken into separate files 
 - HTML 
 - Add some images of other characters
 - Add CSS styles 
 - Add JS file 
 - CSS 
 - Can be better organized for demo
 - Add opportunities for students to make improvements to the appearance 
 - #container overflow hidden 
 - #contanier round corner
 - .button round corner changes colors
 - .button:hover change colors 
 - add a box shadow to player
 - Change game images used as game elements 
 - --player-image
 - --bg-image
 - --bomb-image
 - --fruit-*
 - JS 
 - Add link to main.js
 - Change somethings in the JS to see what happens
 - Edit variables 
 - change the speed and frequency of elements 
 - speed of bombs and fruit
 - frequency of fruit vs bombs

-->