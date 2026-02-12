📘 HTML Basics – Student Learning Guide

📌 Day 1 – Introduction to HTML

#🎯 What You'll Learn Today

1.What is HTML?

2.HTML Document Structure

3.Important HTML Tags

html,
head,
body,
h1 – h6,
p,
a,
img,
div,
span

4.Create a Simple Profile Page

#🧠 Theory: Understanding HTML
🔹 What is HTML?

HTML (HyperText Markup Language) is the standard language used to create web pages.

👉 It provides the structure of a webpage.
👉 It tells the browser how to display content.

Think of HTML as the skeleton of a website.

Example:

<h1>Hello World</h1>
<p>This is my first webpage.</p>


2.🏗️ HTML Document Structure

Every HTML page follows a basic structure:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
</head>
<body>

    <h1>Welcome</h1>
    <p>This is a simple HTML page.</p>

</body>
</html>

#🔍 Explanation

<!DOCTYPE html> → Defines HTML5

<html> → Root element

<head> → Contains meta information

<body> → Contains visible content

3.🏷️ Important HTML Tags

1️⃣ <html>

Root element of the webpage.

2️⃣ <head>

Contains title, meta, links, scripts.

3️⃣ <body>

Contains all visible content.

4️⃣ Headings <h1> – <h6>

Used for titles and subtitles.

<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Section</h3>

5️⃣ Paragraph <p>
<p>This is a paragraph.</p>

6️⃣ Anchor Tag <a>

Used to create links.

<a href="https://github.com">Visit GitHub</a>

7️⃣ Image Tag <img>
<img src="profile.jpg" alt="Profile Image" width="150">


src → Image path

alt → Alternative text

8️⃣ <div>

Block-level container for grouping elements.

<div>
   <h2>About Me</h2>
   <p>Content here</p>
</div>

9️⃣ <span>

Inline container for styling small parts of text.

<p>This is <span style="color:blue;">important</span> text.</p>
