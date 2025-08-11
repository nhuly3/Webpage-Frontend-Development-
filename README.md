# Webpage-Frontend-Development
Developing a web page using only HTML and CSS, without the use of any web development frameworks or website builders. You will replicate the appearance of a provided reference web page as closely as possible. This exercise will enhance your ability to manually compose and modify HTML and CSS, an essential skill for web development.

# Web Page Reproduction
You are provided with an image of a web page. Your task is to replicate this page using only a text editor to write HTML and CSS.
A set of reference images showcasing the web page in three different browsers is available in Appendix A.

# CSS Requirements
The use of CSS is required to style the web page.
All styles must be written in a separate CSS file (e.g., styles.css).

# Images
Your web page must include one image: sayhello.png
Be aware that when viewing images in a browser, some browsers may automatically resize them to fit the window. Ensure your implementation maintains the correct aspect ratio.

# Active Links & Buttons
The web page contains five active links/buttons embedded within the text:
“No. 13”
“Get in Touch / Say Hello”
“Read our Latest Article”
“Sign Up”
“Contact Us”
Additionally, there are four email addresses that should be set as clickable mailto links, invoking an email client when clicked.

# Navigation & Scrolling Behavior
Clicking any of the five links should navigate to a new page: X.html.
The X.html file should be structured into nine sections, each separated by a horizontal line (<hr>).
Each section must begin with a paragraph element in the following format:
<p id="Home">
This is the start of X.html which corresponds to the “Home” link.
</p>
The five links on the main page should be configured so that when a user clicks a link (e.g., "Home"), the browser loads X.html and automatically scrolls to the corresponding section. This can be achieved using HTML anchor links (#).

# Testing & Validation
You must test your HW#1 using the Chrome browser.
Resize the browser window to match the dimensions of the provided PNG reference image and verify:
Correct font, color, and text size
Proper positioning of elements
