## HTML/CSS/Git

### 1 

1. HTML - `vocab` `HTML`

	:question: What does HTML stand for?
	* Helper Text Machine Language
	* Hypertext Markup Language 
	* Helpful Text Multiple Layers
	* Hypertext Middle Level

### 2 

1. HTML Links -

	:question: The correct HTML code for adding a link is:
	* `<link src="http://www.google.com">Google</link>`
	* `<a src=http://www.google.com>Google</a>`
	* `<href="http://www.google.com">Google</href>`
	* `<a href="http://www.google.com">Google</a>` 

### 3 

1. Header Sizes 

	:question: Which of the following is the largest heading size by default?
	* h0
	* h6
	* h1 
	* h10

### 4 

1. Image elements -

	:question: The ____ element tag is used to add an image.
	* `<jpg>`
	* `<a>`
	* `<pic>`
	* `<img>` 

### 5 

1. CSS - 

	:question: What does CSS stand for?
	* Cooperative Standard Styling
	* Creative Style Syntax
	* Colorful Special Styling
	* Cascading Style Sheets 

### 6 

1. HTML CSS Linking - 

	:question: A CSS file is located in a folder and that folder is adjacent to the HTML file you are in. The HTML file you are in links to the CSS file using:
	* `<link rel="stylesheet" type="text/css" href="css/style.css">` 
	* `<a rel="css" type="text/css" href="css/style.css">`
	* `<css rel="stylesheet" type="text/css" src="css/style.css">`
	* `<l rel="stylesheet" type="text/css" src="css/style.css">`

### 7 

1. CSS Syntax - 

	:question: The CSS syntax to style all `<p>` elements to appear bold is:
	* `p { font-weight: bold; }` 
	* `p ( font-weight = bold );`
	* `p [ font-weight: "bold" ]`
	* `p font-weight: bold;`

### 8 

1. CSS Classes - 
	:question: All class names in a CSS file are preceded by the symbol:
	* :
	* \#
	* \-
	* \. 

### 9 

1. CSS IDs - 

	:question: All ID names in a CSS file are preceded by the symbol:
	* :
	* \# 
	* \-
	* \.

### 10 

1. Element Size Calculations - 

	:question: Including margins, how wide is the following element:
	```CSS
	#box {
		width: 20px;
		height: 40px;
		margin: 10px 20px 30px 40px;
		padding: 40px 30px 20px 10px;
		border-width: 10px;
	}
	```
	* 140px 
	* 130px
	* 100px
	* 80px

### 11 

1. Block Elements -

	:question: Which of the following is treated as a block element?
	* `<img>`
	* `<p>` 
	* `<a>`
	* `<link>`

### 12 

1. Block Element Alignment - 
	:question: We can align a block element to the left or right of the screen using the ____ CSS property.
	* align
	* float 
	* left
	* justify

### 13 

1. Moving Elements in Relation - 

	:question: ____ positioning moves elements in relation to their original/default location.
	* Absolute
	* Negative
	* Relative 
	* Exact

### 14 

1. Layering Elements

	:question: The CSS property ____ allows us to layer elements above and below each other.
	* z-level
	* h-index
	* h-level
	* z-index 

### 15 

1. Moving Elements Relatively 

	:question: ____ positioning helps place elements relative to their nearest positioned ancestor element.
	* Absolute 
	* Negative
	* Relative
	* Exact

### 16 

1. Display: none Property 

	:question: The `display: none` property allows us to:
	* prevent pop-up windows
	* close the browser
	* hide an element 
	* remove all images only

### 17 

1. CSS Precedence 

	:question: An HTML file is loading file1.css and file2.css, with file1.css linked before file2.css. The file1.css file lists a class with a font size of 10px. The file2.css file lists the same class but with a font size of 15px. Which CSS file will take precedence in determining the font size for that class?
	* The file1.css file linked in the HTML file
	* The file2.css file linked in the HTML file 
	* The CSS file with the highest number in the name
	* None of them - it will cause an error

### 18 

1. CSS Resets - 
	:question: CSS Resets are an important tool for:
	* creating cross browser compatibility 
	* preventing browser crashes
	* stopping the spread of malware
	* avoiding website hacking

### 19 

1. Class and ID Stacking - 

	:question: What will be the size of the text displayed by the following code?
	```HTML
	<style>
		.myClass {
			font-size: 10px;
		}
		#myID {
			font-size: 20px;
		}
	</style>

	<p id="myID" class="myClass">Hello Boot Camp!</p>
	```
	* 10px
	* 20px 
	* 30px
	* None of the above - This will cause an error

### 20 

1. Special State Keywords -

	:question: Keywords added to CSS selectors that specify a special state of an element are called:
	* primary-selectors
	* main-ids
	* state-elements
	* pseudo-classes 

### 21 

1. CSS Frameworks Purpose - 

	:question: A primary reason for using CSS Frameworks like Bootstrap is to:
	* save significant time building a website 
	* avoid typos and errors in the code
	* allow better collaboration among developers
	* make websites perform faster

### 22 

1. Bootstrap Grid -

	:question: The Bootstrap grid sits inside a ____.
	* CSS file
	* container 
	* relative row
	* master column

### 23 

1. Bootstrap Grid Columns -

	:question: In a Bootstrap grid, the sum total of all columns within a row must add up to ____.
	* 10
	* 20
	* 12 
	* 15

### 24 

1. Bootstrap Grid Classes - 

	:question: To make a column one-half the width of its row, we would use the ____ Bootstrap helper class.
	* col-md-5
	* col-md-10
	* col-md-2
	* col-md-6 

### 25 

1. Mobile Responsiveness -

	:question: ____ are used to help create mobile responsive websites.
	* Media queries 
	* Browser logs
	* Size requests
	* Specialized browsers

### 26 

1. Website Display - 

	:question: ____ refers to the display being used to view a website.
	* Browser
	* Viewport 
	* Displayport
	* Screen

### 27 

1. Git Benefits - 

	:question: Which of the following is NOT a benefit of using Git?
	* having a version history of code changes
	* easing code conflict resolution
	* allowing multiple developers to work together
	* being able to translate code between languages 

### 28 

1. GitHub Workflow -

	:question: What is the typical work flow of committing your work?
	* Commit changes; Push; Clone
	* Add changes to staging; Commit changes 
	* Pull Changes; Commit changes; Add changes to staging
	* Add changes staging; Save to Git; Send to Github

### 29 

1. GitHub Pages Deployment 

     When deploying your site to GitHub Pages, the repository must contain the file:
	* style.css
	* run.html
	* index.html 
	* index.css

### 30 

1. GitHub Pages URL 

	:question: A repository named `portfolio` deployed to GitHub Pages by user `johnsmith1` may be found at the following URL:
	* `https://johnsmith1.github.io/portfolio` 
	* `https://www.github.com/johnsmith1/portfolio`
	* `https://portfolio.github.io/johnsmith1`
	* `https://johnsmith1.github.com/portfolio`

### 31 

1. Git Collaboration 

	:question: When developers are collaborating on a project, they all write their code in their own Git ____.
	* repository
	* branch 
	* page
	* file
