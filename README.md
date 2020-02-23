A Survey Form

See working version:

https://wesgray76.github.io/survey-form/
[1mdiff --git a/README.md b/README.md[m
[1mindex f9d6b72..4158b59 100644[m
[1m--- a/README.md[m
[1m+++ b/README.md[m
[36m@@ -1,5 +1,5 @@[m
[31m-A Survey Form[m
[31m-[m
[31m-See working version:[m
[31m-[m
[31m-https://wesgray76.github.io/survey-form/[m
[32m+[m[32mA Survey Form[m[41m[m
[32m+[m[41m[m
[32m+[m[32mSee working version:[m[41m[m
[32m+[m[41m[m
[32m+[m[32mhttps://wesgray76.github.io/survey-form/[m[41m[m
[1mdiff --git a/index.html b/index.html[m
[1mindex fd38ddc..b753155 100644[m
[1m--- a/index.html[m
[1m+++ b/index.html[m
[36m@@ -1,115 +1,115 @@[m
[31m-<html lang="en">[m
[31m-  <head>[m
[31m-    <meta  charset="utf-8">[m
[31m-    <title>Cookie Survey</title>[m
[31m-    <style>[m
[31m-      body {[m
[31m-        font-family: sans-serif;[m
[31m-        font-size: 1rem;[m
[31m-        font-weight: 400;[m
[31m-        line-height: 1.4;[m
[31m-        margin: 0;[m
[31m-        background-color: #BD8C61;[m
[31m-      }[m
[31m-[m
[31m-      #description {[m
[31m-        text-align: center;[m
[31m-        display: block;[m
[31m-        border: 2px solid black;[m
[31m-        border-radius: 12px;[m
[31m-        width: 600px;[m
[31m-        margin: 0 auto;[m
[31m-        background-color: #EFE2B2;[m
[31m-      }[m
[31m-[m
[31m-      #title {[m
[31m-        text-align: center;[m
[31m-        display: block;[m
[31m-        border: 2px solid black;[m
[31m-        border-radius: 12px;[m
[31m-        width: 600px;[m
[31m-        margin: 0 auto;[m
[31m-        background-color: #EFE2B2;[m
[31m-      }[m
[31m-[m
[31m-      .form-group {[m
[31m-        text-align: center;[m
[31m-        margin: 10px;[m
[31m-      }[m
[31m-[m
[31m-      p {[m
[31m-        margin: 10px;[m
[31m-      }[m
[31m-[m
[31m-      #survey-form {[m
[31m-        border: 2px solid black;[m
[31m-        border-radius: 12px;[m
[31m-        width: 600px;[m
[31m-        margin: 0 auto;[m
[31m-        background-color: #EFE2B2;[m
[31m-      }[m
[31m-    </style>[m
[31m-    </head>[m
[31m-[m
[31m-    <body>[m
[31m-      <h1 id="title">Cookie Survey</h1><br>[m
[31m-      <p id="description">What is your favorite cookie?</p><br>[m
[31m-      <form id="survey-form">[m
[31m-        <div class="form-group">[m
[31m-          <label id="name-label" for="name">Name:</label>[m
[31m-          <input type="text" name="name" id="name" class="form-control" placeholder="Enter your name" required>[m
[31m-        </div>[m
[31m-[m
[31m-        <div class="form-group">[m
[31m-          <label id="email-label" for="email">Email:</label>[m
[31m-          <input type="email" name="email" id="email" class="form-control" placeholder="Enter your Email" required/>[m
[31m-        </div>[m
[31m-[m
[31m-        <div class="form-group">[m
[31m-          <label id="number-label" for="number">Age:</label>[m
[31m-          <input type="number" name="age" id="number" min="5" max="99" class="form-control" placeholder="Age" required/>[m
[31m-        </div>[m
[31m-[m
[31m-        <div class="form-group">[m
[31m-          <label for="type">Type of favorite Cookie</label>[m
[31m-          <select id="dropdown" name="type" class="form-control" required>[m
[31m-            <option disabled selected value>Select Type</option>[m
[31m-            <option value="Chocolate">Chocolate Chip</option>[m
[31m-            <option value="Oreo">Oreo</option>[m
[31m-            <option value="Sugar">Sugar Cookie</option>[m
[31m-            <option value="Snickerdoodles">Snickerdoodles</option>[m
[31m-            <option value="M&M">M&M</option>[m
[31m-          </select>[m
[31m-        </div>[m
[31m-[m
[31m-        <div class="form-group">[m
[31m-          <p>Would you recommend these to a friend?</p>[m
[31m-          <input type="radio" name="user-recommend" value="yes" class="input-radio" checked>[m
[31m-          <label for="yes">Yes</label><br>[m
[31m-          <input type="radio" name="user-recommend" value="no" class="input-radio">[m
[31m-          <label for="no">No</label><br>[m
[31m-          <input type="radio" name="user-recommend" value="undecided" class="input-radio">[m
[31m-          <label for="undecided">Undecided</label>[m
[31m-        </div>[m
[31m-[m
[31m-        <div class="form-group">[m
[31m-          <p>What beverage do you drink with cookies?</p>[m
[31m-          <input type="checkbox" name="drink" value="milk" class="input-checkbox" checked>[m
[31m-          <label for="milk">Milk</label><br>[m
[31m-          <input type="checkbox" name="drink" value="juice" class="input-checkbox">[m
[31m-          <label for="juice">Juice</label><br>[m
[31m-          <input type="checkbox" name="drink" value="other" class="input-checkbox">[m
[31m-          <label for="other">Other</label>[m
[31m-        </div><br>[m
[31m-[m
[31m-        <div class="form-group">[m
[31m-          <textarea name="comment" rows="8" cols="35" id="comments" class="input-textarea" placeholder="Enter your comments here"></textarea>[m
[31m-        </div><br>[m
[31m-[m
[31m-        <div class="form-group">[m
[31m-          <button type="submit" id="submit" class="submit-button">Submit</button>[m
[31m-        </div>[m
[31m-      </form>[m
[31m-      <script type="text/javascript" src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>[m
[31m-    </body>[m
[31m-</html>[m
[32m+[m[32m<html lang="en">[m[41m[m
[32m+[m[32m  <head>[m[41m[m
[32m+[m[32m    <meta  charset="utf-8">[m[41m[m
[32m+[m[32m    <title>Cookie Survey</title>[m[41m[m
[32m+[m[32m    <style>[m[41m[m
[32m+[m[32m      body {[m[41m[m
[32m+[m[32m        font-family: sans-serif;[m[41m[m
[32m+[m[32m        font-size: 1rem;[m[41m[m
[32m+[m[32m        font-weight: 400;[m[41m[m
[32m+[m[32m        line-height: 1.4;[m[41m[m
[32m+[m[32m        margin: 0;[m[41m[m
[32m+[m[32m        background-color: #BD8C61;[m[41m[m
[32m+[m[32m      }[m[41m[m
[32m+[m[41m[m
[32m+[m[32m      #description {[m[41m[m
[32m+[m[32m        text-align: center;[m[41m[m
[32m+[m[32m        display: block;[m[41m[m
[32m+[m[32m        border: 2px solid black;[m[41m[m
[32m+[m[32m        border-radius: 12px;[m[41m[m
[32m+[m[32m        width: 600px;[m[41m[m
[32m+[m[32m        margin: 0 auto;[m[41m[m
[32m+[m[32m        background-color: #EFE2B2;[m[41m[m
[32m+[m[32m      }[m[41m[m
[32m+[m[41m[m
[32m+[m[32m      #title {[m[41m[m
[32m+[m[32m        text-align: center;[m[41m[m
[32m+[m[32m        display: block;[m[41m[m
[32m+[m[32m        border: 2px solid black;[m[41m[m
[32m+[m[32m        border-radius: 12px;[m[41m[m
[32m+[m[32m        width: 600px;[m[41m[m
[32m+[m[32m        margin: 0 auto;[m[41m[m
[32m+[m[32m        background-color: #EFE2B2;[m[41m[m
[32m+[m[32m      }[m[41m[m
[32m+[m[41m[m
[32m+[m[32m      .form-group {[m[41m[m
[32m+[m[32m        text-align: center;[m[41m[m
[32m+[m[32m        margin: 10px;[m[41m[m
[32m+[m[32m      }[m[41m[m
[32m+[m[41m[m
[32m+[m[32m      p {[m[41m[m
[32m+[m[32m        margin: 10px;[m[41m[m
[32m+[m[32m      }[m[41m[m
[32m+[m[41m[m
[32m+[m[32m      #survey-form {[m[41m[m
[32m+[m[32m        border: 2px solid black;[m[41m[m
[32m+[m[32m        border-radius: 12px;[m[41m[m
[32m+[m[32m        width: 600px;[m[41m[m
[32m+[m[32m        margin: 0 auto;[m[41m[m
[32m+[m[32m        background-color: #EFE2B2;[m[41m[m
[32m+[m[32m      }[m[41m[m
[32m+[m[32m    </style>[m[41m[m
[32m+[m[32m    </head>[m[41m[m
[32m+[m[41m[m
[32m+[m[32m    <body>[m[41m[m
[32m+[m[32m      <h1 id="title">Cookie Survey</h1><br>[m[41m[m
[32m+[m[32m      <p id="description">What is your favorite cookie?</p><br>[m[41m[m
[32m+[m[32m      <form id="survey-form">[m[41m[m
[32m+[m[32m        <div class="form-group">[m[41m[m
[32m+[m[32m          <label id="name-label" for="name">Name:</label>[m[41m[m
[32m+[m[32m          <input type="text" name="name" id="name" class="form-control" placeholder="Enter your name" required>[m[41m[m
[32m+[m[32m        </div>[m[41m[m
[32m+[m[41m[m
[32m+[m[32m        <div class="form-group">[m[41m[m
[32m+[m[32m          <label id="email-label" for="email">Email:</label>[m[41m[m
[32m+[m[32m          <input type="email" name="email" id="email" class="form-control" placeholder="Enter your Email" required/>[m[41m[m
[32m+[m[32m        </div>[m[41m[m
[32m+[m[41m[m
[32m+[m[32m        <div class="form-group">[m[41m[m
[32m+[m[32m          <label id="number-label" for="number">Age:</label>[m[41m[m
[32m+[m[32m          <input type="number" name="age" id="number" min="5" max="99" class="form-control" placeholder="Age" required/>[m[41m[m
[32m+[m[32m        </div>[m[41m[m
[32m+[m[41m[m
[32m+[m[32m        <div class="form-group">[m[41m[m
[32m+[m[32m          <label for="type">Type of favorite Cookie</label>[m[41m[m
[32m+[m[32m          <select id="dropdown" name="type" class="form-control" required>[m[41m[m
[32m+[m[32m            <option disabled selected value>Select Type</option>[m[41m[m
[32m+[m[32m            <option value="Chocolate">Chocolate Chip</option>[m[41m[m
[32m+[m[32m            <option value="Oreo">Oreo</option>[m[41m[m
[32m+[m[32m            <option value="Sugar">Sugar Cookie</option>[m[41m[m
[32m+[m[32m            <option value="Snickerdoodles">Snickerdoodles</option>[m[41m[m
[32m+[m[32m            <option value="M&M">M&M</option>[m[41m[m
[32m+[m[32m          </select>[m[41m[m
[32m+[m[32m        </div>[m[41m[m
[32m+[m[41m[m
[32m+[m[32m        <div class="form-group">[m[41m[m
[32m+[m[32m          <p>Would you recommend these to a friend?</p>[m[41m[m
[32m+[m[32m          <input type="radio" name="user-recommend" value="yes" class="input-radio" checked>[m[41m[m
[32m+[m[32m          <label for="yes">Yes</label><br>[m[41m[m
[32m+[m[32m          <input type="radio" name="user-recommend" value="no" class="input-radio">[m[41m[m
[32m+[m[32m          <label for="no">No</label><br>[m[41m[m
[32m+[m[32m          <input type="radio" name="user-recommend" value="undecided" class="input-radio">[m[41m[m
[32m+[m[32m          <label for="undecided">Undecided</label>[m[41m[m
[32m+[m[32m        </div>[m[41m[m
[32m+[m[41m[m
[32m+[m[32m        <div class="form-group">[m[41m[m
[32m+[m[32m          <p>What beverage do you drink with cookies?</p>[m[41m[m
[32m+[m[32m          <input type="checkbox" name="drink" value="milk" class="input-checkbox" checked>[m[41m[m
[32m+[m[32m          <label for="milk">Milk</label><br>[m[41m[m
[32m+[m[32m          <input type="checkbox" name="drink" value="juice" class="input-checkbox">[m[41m[m
[32m+[m[32m          <label for="juice">Juice</label><br>[m[41m[m
[32m+[m[32m          <input type="checkbox" name="drink" value="other" class="input-checkbox">[m[41m[m
[32m+[m[32m          <label for="other">Other</label>[m[41m[m
[32m+[m[32m        </div><br>[m[41m[m
[32m+[m[41m[m
[32m+[m[32m        <div class="form-group">[m[41m[m
[32m+[m[32m          <textarea name="comment" rows="8" cols="35" id="comments" class="input-textarea" placeholder="Enter your comments here"></textarea>[m[41m[m
[32m+[m[32m        </div><br>[m[41m[m
[32m+[m[41m[m
[32m+[m[32m        <div class="form-group">[m[41m[m
[32m+[m[32m          <button type="submit" id="submit" class="submit-button">Submit</button>[m[41m[m
[32m+[m[32m        </div>[m[41m[m
[32m+[m[32m      </form>[m[41m[m
[32m+[m[32m      <script type="text/javascript" src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>[m[41m[m
[32m+[m[32m    </body>[m[41m[m
[32m+[m[32m</html>[m[41m[m
