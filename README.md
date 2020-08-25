# Jeopardy

## Introduction
I will take "JavaScript" for 600. 

## Objective
For this exercise, you will demonstrate your knowledge of JavaScript by creating an interactive Game of Jeopardy from the starter files provided. 

## Requirements
The following requirements must be met in order to complete the assignment successfully: 

### Step 1
Inside the files will be `index.html`, `style.css` and `jeopardy.js`. **All the changes will be made to the `jeopardy.js` file.**

### Step 2
Using JavaScript and the provided categories object, dynamically populated the game board with category titles, values, clues, and answers following the template found in the HTML.

```html
<div id="board" class="board">
  <div class="category">
    <div class="title">Category Title</div>
    <div class="cell" data-clue="the clue text" data-answer="the clue answer">clue value</div>
    <div class="cell" data-clue="the clue text" data-answer="the clue answer">clue value</div>
    <div class="cell" data-clue="the clue text" data-answer="the clue answer">clue value</div>
  </div>
  <div class="category">
    <div class="title">Category Title</div>
    <div class="cell" data-clue="the clue text" data-answer="the clue answer">clue value</div>
    <div class="cell" data-clue="the clue text" data-answer="the clue answer">clue value</div>
    <div class="cell" data-clue="the clue text" data-answer="the clue answer">clue value</div>
  </div>
  <div class="category">
    <div class="title">Category Title</div>
    <div class="cell" data-clue="the clue text" data-answer="the clue answer">clue value</div>
    <div class="cell" data-clue="the clue text" data-answer="the clue answer">clue value</div>
    <div class="cell" data-clue="the clue text" data-answer="the clue answer">clue value</div>
  </div>
</div>
```

### Step 3
Clicking on any cell on the board should insert the cells clue and answer into the overlay and add the class `show` to the overlay. 

*If this cell is clicked...*
```html
<div class="cell" data-clue="Monica & Chandler" data-answer="What is Friends">200</div>
```

*The overlay should look like this*
```html
<div id="overlay" class="overlay show">
  <div id="clue" class="clue">Monica & Chandler</div>

  <div class="responses">
    <div id="answer" class="answer">What is Friends</div>
    <button id="close" class="button close">Show Answer</button>
  </div>

</div>
```

### Step 4
Clicking on the 'Show Answer' button should add the class `show` on the answer and switch the text of the button to 'Close'. Clicking on the button again should remove the class of `show` from the answer and the overlay and change the text of the button to 'Show Answer'.
