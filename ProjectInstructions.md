# Jeopardy

## Style Guide
- Each ticket may have specific requirements to complete a task. Anything outside of stated requirements can be flexible.
- Once a ticket is completed, commit your code to your repo with a commit message **[ticket number] [status]**
  - ex: `git commit -m "U1_01 Completed"`
    - This would detail that The Landing Page portion has been completed.
- All `title` elements within the HTML documents should note the respective file.

--- 
## Wireframe
At the following link, you will find a Figma containing the four wireframes necessary for this project.

This is not meant to be pixel-perfect. 

**[Link to Project Wireframe](https://www.figma.com/file/A40d58jQlcdR0GRlwVi3GQ/jeopardy-wireframes?node-id=0%3A1&t=XRyIq1TiIZDvkMHC-1)**

## Git Requirements
- `git init`
- `git add .`
- `git commit -m "initial setup"`

# The Landing Page
### File / Folder Structure
```
- root folder
  - assets folder
  - index.html
  - styles folder
    - style.css
```

## Ticket `#U1_01`
- **Given** an `index.html` file exists.
- **When** the user visits the `index.html` file.
- **Then** they should see the landing page.
- **And** there should be a centered title at the top of the page.
- **And** a centered image that represents your Jeopardy game.
  - This can be obtained via internet. 
- **And** a "Play" button centered below the image.
- **And** a footer displaying site information.
  - Should state "*Upright Unit 1 Project Copyright [current year]*"

**Ticket Requirements**
- **image** should be handled through the HTML document.
- All styling should be within a separate CSS document.
- This ticket requires a **flex** layout.
- **Play Button** should have a hover effect

--- 

# First Round
### File / Folder Structure
```
- root folder
  - firstRound.html
  - styles [folder]
    - rounds.css
```
## Ticket `#U1_02`
- **Given** the user is on the landing page.
- **When** they click the "Play" button.
- **Then** they should be routed to the first round page.
- **Given** the user is on the first round page.
- **Then** they should see a title, that indicates it's the first round.
- **And** they should see a subtitle that indicates whose turn it is.
- **And** a 6X6 grid with category names across the top row, and points from 200 - 1000 below each category, doubling in each row.
- **And** the grid should be centered on the page.
- **And** they should see a box to enter their input, a Guess button, a Pass button.
- **And** they should see the scores of Player 1 and Player 2 displayed.
- **And** a button to navigate to the next round.
- **And** a footer displaying site information.

**Ticket Requirements**
- This ticket requires a **grid** layout for the 6x6 display.
- **All Squares** should have a hover effect
- **Footer** should have an `anchor` tag that routes back to the Landing Page.
- **Features unique** to the First Round should be styled within the *rounds.css* file.
- **Features not unique** to the First Round should be styled within the *style.css* file.

---

# Second Round
### File / Folder Structure
```
root folder
  - secondRound.html
```
## Ticket `#U1_03`
- **Given** the user is on the first round page.
- **When** they click the Next Round button to navigate to the second round page.
- **Then** they should be taken to the second round page.
- **Given** the user is on the second round page.
- **Then** they should see a title, that indicates it's the second round.
- **And** they should see a subtitle that indicates whose turn it is.
- **And** a 6X6 grid with category names across the top row, and points from 400 - 2000 below each category: [400, 600, 800, 1000, 2000].
- **And** the grid should be centered on the page
- **And** they should see a box to enter their input, a Guess button, a Pass button.
- **And** they should see the scores of Player 1 and Player 2 displayed.
- **And** a button to navigate to the next round.
- **And** a button to navigate to the previous round.
- **And** a footer displaying site information.

**Ticket Requirements**
- **Category** blocks should be associated with a secondary class and **not** have a hover effect.
  - `firstRound.html` should display the same.

---
# Final Jeopardy
```
root folder
  - finalRound.html
  - styles [folder]
    - final.css
```
## Ticket `#U1_04`
- **Given** the user is on the second round page.
- **When** they click the button to the next round.
- **Then** they should be taken to the Final Round page.
- **Given** the user is on the Final Round page.
- **Then** they should see a title indicating it's the Final Round.
- **And** a single final category with a single final answer.
- **And** One form:
  - One with a field for the amount you want to bet.
  - One for the final answer, the button for which should be disabled.

**Ticket Requirements**
- All styling unique to this document should be within **final.css**.

---
# Stretch Goals
### Note:
Stretch goals should not be attempted until previous tickets have been completed and tested.

## Ticket `#U1_05`
- Include a `README.md` to the **root** directory.
  - Detail the concept of this project in psuedo code within the document.
  -  **[Pseudo Code Article](https://www.geeksforgeeks.org/how-to-write-a-pseudo-code/)**
-  Create your own theme for the site.
   -  background images, color theme, ect.
-  Provide a placeholder where the category answer will display above the grid display.
   -  Later Concept:
      -  **WHEN** a player selects a value on the board.
      -  **THEN** the answer will be presented above the grid.
   -  *This does not have to be an active button to display anything. This is meant only to be a **placeholder*** 
-  Place a **brand** that is fixed to the top-left of the site. 
   -  This should route to the landing page whenever clicked.
   -  This should have a hover effect for user feedback.
   -  Style this so it doesn't look like a hyperlink.
-  Deploy this project through **GitHub Pages**.
   -  Update your **README.md** with a hyperlink to the deployed URL.

# Submission Requirements
- Your **GitHub Repo** should be provided within the LMS.