# 🌐 HTML Multi-page Website Structure

This project is a beginner-friendly exercise to build the **structure of a simple multi-page website using only HTML**. The primary goal is to understand how to organize content semantically across several web pages without applying any design or styling yet.

## 📌 Project Objective

The purpose of this project is to:

- Learn how to build multiple pages in a website.
- Understand and use **semantic HTML** elements properly.
- Structure pages to allow **easy styling** later.
- Add **basic SEO meta tags**.
- Practice creating a **reusable navigation bar**, a **sidebar**, and a **contact form**.

⚠️ **No CSS or JavaScript is used** in this project. It focuses purely on the **HTML structure**.

---

## 📄 Pages Included

The website contains the following pages:

1. `index.html` — Home page
2. `projects.html` — Projects portfolio page
3. `articles.html` — Blog or article listing
4. `contact.html` — Contact form page

Each page includes:

- A semantic HTML structure
- A `<header>`, `<nav>`, `<main>`, `<aside>`, and `<footer>`
- SEO-friendly `<meta>` tags
- A shared navigation menu
- Sidebar content with embedded SVG icons
- The contact page includes a working HTML form

---

## 🏗️ Folder Structure

```

html-multipage-site/
├── index.html
├── projects.html
├── articles.html
├── contact.html
├── README.md
└── (no styling or CSS files)

````

> *You may add a `/icons/` or `/assets/` folder in the future if you switch from SVG inline to external image files.*

---

## 🧱 Semantic Structure Overview

Each HTML page uses proper HTML5 structure:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- SEO tags: title, description, keywords, etc -->
  </head>
  <body>
    <header> ... </header>
    <nav> ... </nav>
    <main>
      <section> ... </section>
      <aside> ... </aside> <!-- Sidebar -->
    </main>
    <footer> ... </footer>
  </body>
</html>
````

This ensures accessibility, SEO readiness, and clean separation of page sections.

---

## 🔎 Meta Tags Used

Every page includes important meta tags inside `<head>` for SEO:

```html
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="description" content="Brief description of the page" />
<meta name="keywords" content="HTML, Semantic HTML, Beginner Project, Multi-page Website" />
<meta name="author" content="Your Name" />
<title>Page Title</title>
```

---

## ✏️ Form Elements on Contact Page

The `contact.html` page includes a basic contact form using these fields:

* Full Name (`<input type="text">`)
* Email Address (`<input type="email">`)
* Message (`<textarea>`)
* Submit Button (`<button>`)

```html
<form action="#" method="post">
  <label for="name">Full Name:</label>
  <input type="text" id="name" name="name" required />

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required />

  <label for="message">Message:</label>
  <textarea id="message" name="message" rows="5" required></textarea>

  <button type="submit">Send</button>
</form>
```

---

## 🧪 How to Test

1. Clone or download this repository.
2. Open any `.html` file in a modern browser (e.g. Chrome, Firefox).
3. Click through the navigation links to ensure internal linking works.
4. Check if all pages share the same layout and structure.
5. On the contact page, test the form inputs.
6. Check SVG icons show up correctly in the sidebar.

---

## 🧠 What You'll Learn

* Creating multiple HTML pages
* Using semantic HTML tags: `<header>`, `<footer>`, `<main>`, `<section>`, `<article>`, `<aside>`, etc.
* Building a consistent navigation bar
* Structuring HTML for future CSS design
* Embedding simple icons with SVG
* Writing SEO-friendly HTML pages
* Creating a basic HTML form

---

## 📌 Next Steps (For Future Development)

* Add styling with CSS (Flexbox, Grid, Colors, Fonts)
* Make the layout responsive
* Add form validation with JavaScript
* Improve accessibility with ARIA attributes
* Host the site using GitHub Pages or Netlify

---

## 👨‍💻 Author

**Mochamad Rizki**
Full Stack Developer
🌐 [rizkilabs.com](https://rizkilabs.com)
📧 [rizkilabs.dev@gmail.com](mailto:rizkilabs.dev@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/rizkilabs)

---

## 📄 License

This project is open-source and free to use for learning and portfolio purposes.
