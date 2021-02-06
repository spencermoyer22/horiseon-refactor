# Horiseon Refactor

## Description
In refactoring the code of Horiseon's website, the first thing done was modifying the layout of the semantics in the HTML. The website was 
created with a large quantity of div elements which created a div soup. This is not an effective way to group elements on a page, so I used
tags such as header, section, and footer to split up the content in a more organized manner.

After reorganizing the elements, I had to ensure the style.css sheet was also properly organized. I did this by changing any styles for elements
that were named differently before. I also moved small amounts of the code around to make sure styles referring to the same section were grouped
together. I added comments to the different styles that were related to each other to give any reader an easy way to find different groups of
codes. I also cut some of the coding to make universal styles that were using the same rules for styles in multiple areas of code. For example,
the content section had three different groups of children to the parent section that were following the same rules. It was simpler to create
one class and style that worked for the different items that writing the same code out for each individual item.

When the code was properly organized and styled, I also made sure that the functions of the webpage worked properly. This included fixing one of
the anchor links in the header to scroll to the section on the page. I also had to add alt attributes to the photos in the proper manner to ensure
anyone with a disability that needs to use screen reading can get the information they need.

## Built With
* HTML
* CSS

## Screenshot
![Horiseon Landing Page](assets/images/landing-page.png)

## Website
https://spencermoyer22.github.io/horiseon-refactor/

## Contribution
Made by Spencer Moyer
