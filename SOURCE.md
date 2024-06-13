
see the following source code and see my code <!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Code Challenge 1</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<hi>Welcome to Riyadh</hi>
<h2>Where A Traditional Past Meets A Modern Future</h2>
<img src="https://s3.amazonaws.com/learn-verified/RIYADH-MOCKUP.jpg" alt="MOCKUP.jpg"
<body>
  <div class="wrapper">
    <!-- HEADER -->
    <!-- SUB HEAD -->

    <div id="content">
      <!-- IMAGES, SMALL SUB HEADS, PARAGRAPHS, LINKS -->
    </div>
  </div>
</body>
</html>
ChatGPT
I noticed a few issues in your HTML code. Below is a revised version with corrections and improvements:

The <!DOCTYPE html> declaration should be in uppercase for consistency.
The hi tag should be h1 for the main heading.
The img tag is missing a closing > bracket.
The <head> section should include a closing </head> tag before the start of the <body> tag.
The img tag should be placed inside the body tag.
Here is the corrected HTML:

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Code Challenge 1</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <h1>Welcome to Riyadh</h1>
  <h2>Where A Traditional Past Meets A Modern Future</h2>
  <img src="https://s3.amazonaws.com/learn-verified/RIYADH-MOCKUP.jpg" alt="MOCKUP">
  
  <div class="wrapper">
    <!-- HEADER -->
    <!-- SUB HEAD -->

    <div id="content">
      <!-- IMAGES, SMALL SUB HEADS, PARAGRAPHS, LINKS -->
    </div>
  </div>
</body>
</html>
Summary of Changes:
Changed <hi> to <h1>.
Added the closing </head> tag before the <body> tag.
Corrected the img tag by adding the missing closing > bracket.
Moved the img tag inside the body tag for proper structure.
This should render the HTML correctly and follow best practices for HTML structure.

source code  HEADING

`Welcome to Riyadh`

SUB HEAD

`Where A Traditional Past Meets A Modern Future.`

IMAGE 1 FILE

`transit.jpg`

IMAGE 1 ALT TEXT

`Modern Transit`

SMALLER SUB HEAD

`Travel`

PARAGRAPH 1

`Once a mudbrick waystation along desert trading routes, Riyadh is now one of the wealthiest cities in the world. The country’s political, financial and administrative capital is also a city with a fascinating subtext.`

SMALLER SUB HEAD

`History`

PARAGRAPH 2

`Riyadh (/rɨˈjɑːd/; Arabic: الرياض‎ ar-Riyāḍ pronounced [arːiˈjɑːdˤ],"The Gardens") is the capital and largest city of Saudi Arabia. It is also the capital of Riyadh Province, and belongs to the historical regions of Najd and Al-Yamama. It is situated in the center of the Arabian Peninsula on a large plateau, and is home to 5,254,560 people, and the urban center of a region with a population of close to 7 million people.`

IMAGE 2 FILE

`garden.jpg`

IMAGE 2 ALT TEXT

`Riyadh Garden`

PARAGRAPH 3

`The city is divided into 15 municipal districts, managed by Riyadh Municipality headed by the mayor of Riyadh, and the Riyadh Development Authority, chaired by the governor of Riyadh Province, Khalid bin Bandar Al Saud. The current mayor of Riyadh is Abdullah bin Abdul Rahman Al Mogbel, appointed in 2012. Riyadh has the largest all female university in the world, the Princess Nora bint Abdulrahman University. It has been designated as a Beta World City.`

IMAGE 3 FILE

`camels-in-truck.jpg`

IMAGE 3 ALT TEXT

`The roads of Riyadh`

SMALLER SUB HEAD

`Sources`

LINK 1

`Lonely Planet`
`http://www.lonelyplanet.com/saudi-arabia/riyadh`

LINK 2

`Wikipedia`
`http://en.wikipedia.org/wiki/Riyadh`
ChatGPT
Here's the updated HTML code based on the provided source content:

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Code Challenge 1</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <h1>Welcome to Riyadh</h1>
  <h2>Where A Traditional Past Meets A Modern Future</h2>
  <img src="transit.jpg" alt="Modern Transit">
  
  <div class="wrapper">
    <!-- HEADER -->
    <!-- SUB HEAD -->
    <div id="content">
      <h3>Travel</h3>
      <p>Once a mudbrick waystation along desert trading routes, Riyadh is now one of the wealthiest cities in the world. The country’s political, financial and administrative capital is also a city with a fascinating subtext.</p>
      
      <h3>History</h3>
      <p>Riyadh (/rɨˈjɑːd/; Arabic: الرياض‎ ar-Riyāḍ pronounced [arːiˈjɑːdˤ],"The Gardens") is the capital and largest city of Saudi Arabia. It is also the capital of Riyadh Province, and belongs to the historical regions of Najd and Al-Yamama. It is situated in the center of the Arabian Peninsula on a large plateau, and is home to 5,254,560 people, and the urban center of a region with a population of close to 7 million people.</p>
      <img src="garden.jpg" alt="Riyadh Garden">
      
      <p>The city is divided into 15 municipal districts, managed by Riyadh Municipality headed by the mayor of Riyadh, and the Riyadh Development Authority, chaired by the governor of Riyadh Province, Khalid bin Bandar Al Saud. The current mayor of Riyadh is Abdullah bin Abdul Rahman Al Mogbel, appointed in 2012. Riyadh has the largest all female university in the world, the Princess Nora bint Abdulrahman University. It has been designated as a Beta World City.</p>
      <img src="camels-in-truck.jpg" alt="The roads of Riyadh">
      
      <h3>Sources</h3>
      <ul>
        <li><a href="http://www.lonelyplanet.com/saudi-arabia/riyadh">Lonely Planet</a></li>
        <li><a href="http://en.wikipedia.org/wiki/Riyadh">Wikipedia</a></li>
      </ul>
    </div>
  </div>
</body>
</html>