# SoBA Web Curriculum

### Lesson 5: jQuery and Underscore.js


#### Overview

For this lesson you will be transforming data with [underscore.js](http://underscorejs.org) and injecting html into the page using [jQuery](http://jquery.com). The purpose of the lesson is to introduce you to what have become standard JavaScript libraries for DOM and data manipulation.

#### Instructions

Again, make sure you fork this repository to your own account and clone it like you did for previous assignments.

Keep up the habit of branching in git, making your changes, and then merging back into your main branch. As in Assignment 4, instead of branching from main, create a "development" branch immediately after you clone the repository, and branch from this line when you edit the individual files.

#### Editing the files

For this lesson you will only be editing index.html. The page has already been prepared for you, including links to JavaScript libraries hosted on Content Distribution Networks (CDNs).

Instructions are included in the webpage. You may modify the HTML structure of the page to simplify DOM manipulation. This is a common strategy: create a container div with a unique ID and use jQuery to target it for appending new html. For reference, the instructions are included here.

I have also included creating.html, which references the various ways you create HTML and manipulate the DOM from jQuery and underscore. You may want to refer to these examples as you work on the homework.

#### The assignment

You will find the following assignments in index.html. Use the dataset provided by js/people.js.

1. Use underscore to find the oldest person. Use jQuery to inject their full name into the page, e.g. 'Oldest peron: x'

2. Use underscore to find the youngest person. Use jQuery to inject their full name into the page, e.g. 'Youngest peron: x'

3. Use underscore to find the most common hair color. Use jQuery to inject it into the page, e.g. 'Most common hair color: x'

4. Use underscore to find the most common music preference. Use jQuery to inject it into the page, e.g. 'Most popular music: x'

5. Use underscore to find the youngest person who likes 'techno' music. Log their name to the console.

6. Use underscore to find out how many people like country. Log the amount to the console.

7. Use underscore to create a new list of people. The list should contain the same people in the original list, except for now, everybody likes techno music. Log the result to the console.

8. Use underscore to create a new list of people. The list should be based on the original list, except for now, everybody is twice as old as they were before, and if they are older than 70, do not include them in the resulting list. Everything else remains the same.

9. Use underscore to iterate through the list. Use underscore templating to create a div for each person. In the div, add a paragraph for all of the attributes except firstName and lastName. For firstName and lastName, create a single paragraph for 'Name'. Define a helper function that creates the full name from the first and last names and use it in the template. Create a helper function to translate the sex attribute into text: 0 = 'Male', 1 = 'Female' and use it in the template. Be sure to extend each of the objects with your helper function! Use jQuery to inject the resulting html into the page.

#### Additional Free Form Assignment

Now that you are familiar with JavaScript, DOM manipulation and jQuery, you should be able to understand the [Twitter Bootstrap JavaScript](http://getbootstrap.com/javascript/).

Review the documentation and try to implement some of the functionality on a page of your design. Of particular utility are the Dropdown, Alert and Modal components. 

Use Twitter Bootstrap to style your page.

