# Treehouse FSJS Project 8
By Rachel Johnson

---

### Set Up and Initialize Project
The .gitignore file is in place and the node_modules folder is not stored in the repo.

Running npm install adds all necessary dependencies.

Running npm start launches the app.  

----
### Models
Project includes the following Sequelize Model and properties:  
- Book
    - title - string
    - author - string
    - genre - string - year - integer  
    
Uses the appropriate Model validation to ensure that the title and author properties will have values when the form is submitted.

---

### Routes

Project contains at least the following routes:
- / - get
- /books - get
- /books/new - get
- /books/new - post
- /books/:id - get
- /books/:id - post
- /books/:id/delete - post

---

### Views

Project contains at least the following views:
- layout.pug
- index.pug
- new-book.pug
- update-book.pug
- error.pug
- page-not-found.pug

---

### Form Fields

If title or author fields are empty, form will not submit and page shows friendly error message.

Forms employ Sequelize Model validation rather than HTML’s built in validation.

Clicking on an input’s label brings focus to corresponding input.

---

### Errors

If routing to a non-existent book id, project uses a global error handler to render a friendly "Page Not Found" or "error" page.

If navigating to a non-existent route like /noroute, the project renders a user friendly "Page Not Found" page.

---

### Styles and Layout

Project uses supplied styles.

General layout matches example markup pages.

---

### Exceeds Expectations Requirements

Main book list has search feature.  

Search works for all of the following fields:
- Title
- Author
- Genre
- Year  

Search is case insensitive.  
Search works for partial matches on strings.  
Main book list has pagination feature.  
