########## Waseed Obaid's Personal Portfolio ##############

#Course: INFR3120 – Web and Script Programming  
#Assignment:** Assignment 1 – Portfolio Website using HTML5 and CSS3  

Responsive Design 

The website uses fluid design which is separated by 3 files to support mobile, tablets, and desktop.

The `style.css` file contains the shared styling used across the website.

Desktop Layout
The desktop layout displays content sections in two columns using CSS floats and percentage widths. This makes use of the additional horizontal space available on larger screens. These are screens that are larger than 960pixels

Tablet Layout
The tablet layout removes the section floats and stacks content vertically. The widths and navigation spacing are adjusted to fit medium-sized screens which are between 461 and 960 pixels as these tend to be standard tablet sizes.

Mobile Layout
The mobile layout uses a single-column design. Navigation links are stacked vertically, and images, videos, and form fields are resized to fit mobile screens which are 460 pixels or smaller. 

These viewport dimensions were chosen based on the responsive design examples covered in this course.

Color Scheme

The website uses a creamy and sage colour scheme which felt appropriate for this assignment. It provides a professional and clean look. 

The color palette uses related green tones with a neutral cream background to maintain a consistent appearance.


Gradients

The website uses two types of linear gradients as required by the assignment.


The regular linear gradient is applied to the `body` element in `style.css`.
background: linear-gradient(#F3F1E9, #A3B5A0);
This creates a vertical transition from cream to sage green across the website background.



I also used the angled linear gradient for the article portion background on the Projects page.

#projects-page article {
    background: linear-gradient(135deg, #E8EBE3, #B7C8B2);
}

The 135-degree angle creates a diagonal transition between two green colors.



