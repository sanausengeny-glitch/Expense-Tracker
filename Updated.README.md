# Personal Budget & Expense Tracker 💰

## Project Overview

The **Personal Budget & Expense Tracker** is a web-based application designed to help users record, organize, and monitor their daily expenses. This project is being developed progressively from **Week 1 to Week 8**, with each stage introducing new web development concepts and improving the application's functionality.

The current version focuses on building a strong **HTML5 and CSS3 foundation** by creating a structured user interface, expense management form, expense table, multimedia content, and advanced CSS styling techniques.

This project represents the first stage of a complete developer portfolio project that will later include JavaScript functionality, data storage, calculations, and enhanced user experience features.

---

# Current Features

## 1. Expense Entry Form

The application includes an **Add Expense** section where users can enter expense information.

Features include:

- Expense name input field
- Amount input field
- Date selection field
- Category selection dropdown
- Add Expense button

The form structure is prepared for future JavaScript integration where users will be able to dynamically add expenses.

---

## 2. Expense Management Table

A structured expense table displays recorded expenses.

The table includes:

| Column | Description |
|---|---|
| Name | Expense title or description |
| Amount | Cost of the expense |
| Category | Expense classification |
| Date | Date the expense occurred |

The table uses proper HTML table elements:

- `<table>`
- `<thead>`
- `<tbody>`
- `<tr>`
- `<th>`
- `<td>`

Five sample expense records are included as placeholder data.

---

## 3. Multimedia Integration

The webpage includes multimedia elements to improve user engagement:

### Logo/Image

An image element is added with:

- Source (`src`)
- Alternative text (`alt`)
- Width attribute

### Budgeting Video

A YouTube budgeting tips video is embedded using an iframe containing:

- Width
- Height
- Title
- Frame border settings

---

## 4. Interactive Help Section

A collapsible information section was created using:

- `<details>`
- `<summary>`

This provides users with instructions on how to use the tracker while keeping the interface clean.

---

# CSS Styling Implementation

The project applies modern CSS techniques to improve the appearance and usability of the webpage.

## Styling Includes:

- Page layout formatting
- Form styling
- Table design
- Button styling
- Hover effects
- Input focus effects
- Background colors
- Spacing and alignment

---

# Advanced CSS Selectors Used

The project demonstrates advanced CSS selector concepts including:

## 1. Descendant Selector

Example:

```css
.expenses-section td {
    color: #333;
}
```

Targets table cells inside the expenses section.

---

## 2. Direct Child Selector

Example:

```css
.add-expense-section > form {
    padding:15px;
}
```

Targets forms directly inside the Add Expense section.

---

## 3. Position Pseudo-Class Selector

Example:

```css
tbody tr:nth-child(even){
    background:#f2f2f2;
}
```

Creates alternating table row colors for better readability.

---

## 4. Negation Selector

Example:

```css
input:not([type="button"]){
    border:1px solid #999;
}
```

Applies styling to inputs except specified types.

---

## 5. Focus Selector

Example:

```css
input:focus{
    border:2px solid blue;
}
```

Highlights input fields when users interact with them.

---

# Technologies Used

## Frontend Technologies

- HTML5
- CSS3

## Development Tools

- Visual Studio Code
- Google Chrome Developer Tools
- Git and GitHub

---

# Project Structure

```
Expense-Tracker/

│── index.html       # Main webpage structure
│── style.css        # Website styling and CSS selectors
│── README.md        # Project documentation
```

---

# How to Run the Project

1. Clone the repository:

```
git clone https://github.com/sanausengeny-glitch/Expense-Tracker.git
```

2. Open the project folder.

3. Open:

```
index.html
```

in any modern web browser.

---

# Learning Outcomes

Through this project, I practiced:

- Creating semantic HTML structures
- Building forms and tables
- Using multimedia elements in webpages
- Linking external CSS files
- Applying CSS selectors
- Using browser DevTools for debugging
- Organizing a professional GitHub project

---

# Future Development Roadmap

Future versions of this project will include:

### Week 3+
- Improved responsive design
- Better user interface

### Week 4+
- JavaScript integration

### Week 5+
- Dynamic expense creation and deletion

### Week 6+
- Expense calculations
- Budget summaries

### Week 7+
- Data persistence using Local Storage

### Week 8
- Final polished portfolio-ready application

---

# Author

**Sanau Sengeny**

Web Development Student  
Power Learn Project (PLP)

---

⭐ This project is continuously improving as new web development skills are introduced.
