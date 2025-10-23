# Stage 1 Task – HNG Frontend Track

This project is part of my **HNG Frontend Internship Stage 1 Task**.  
It includes two main pages — **About Page** and **Contact Page** — both built using **HTML**, **CSS**, and **JavaScript**.  
The goal of this task is to demonstrate an understanding of:
- Semantic HTML
- Accessibility
- Responsive design
- Use of `data-testid` attributes for automated testing

---

## 📄 Pages

### 1️⃣ About Page (`about.html`)
The **About Page** provides personal information, goals, and social links.

#### 🔹 Features:
- Displays biography, goals, confidence, future aspirations, and extra info in well-structured sections.
- Each section is styled as a responsive **card layout** that adjusts automatically:
  - **3 per row** on large screens
  - **2 per row** on medium screens
  - **1 per row** on small screens
- Smooth hover effects for interactivity.
- Social links open safely in new tabs (`target="_blank"` with `rel="noopener noreferrer"`).

#### 🧩 Data Test IDs Used:
Each key section has a unique `data-testid` for easy testing, such as:
data-testid="test-about-bio"
data-testid="test-about-goals"
data-testid="test-about-confidence"
data-testid="test-about-future-note"
data-testid="test-about-extras"

---

### 2️⃣ Contact Page (`contact.html`)
The **Contact Page** allows visitors to reach out through a contact form.

#### 🔹 Features:
- Contains fields for **Name**, **Email**, **Message**, and a **Submit button**.
- All fields are **accessible by keyboard** and properly labeled for screen readers.
- Form validation ensures users cannot submit empty fields.
- Displays a **success message** when the form is submitted.
- Includes navigation links to the other pages.

#### 🧩 Data Test IDs Used:
data-testid="test-contact-form"
data-testid="test-contact-name"
data-testid="test-contact-email"
data-testid="test-contact-message"
data-testid="test-contact-submit"

---

## 🧠 Accessibility
- All interactive elements (links, buttons, inputs) are **keyboard accessible** using `tab` navigation.  
- Proper HTML semantics and ARIA-friendly attributes are used for better screen reader support.  
- Text contrast ensures readability against the background.

---

## 💻 Technologies Used
- **HTML5**
- **CSS3 (Flexbox + Grid for layout)**
- **JavaScript (for form validation and interactivity)**
- **Font Awesome** (for social media icons)

---

## 📱 Responsiveness
The layout automatically adapts for all screen sizes:
- Desktop: multiple cards per row
- Tablet: 2 per row
- Mobile: single column layout

This ensures an optimal viewing experience across devices.

---

## 🚀 How to Run
1. Clone or download the project files.
2. Open `index.html` in your browser (or use a Live Server extension in VS Code).
3. Navigate using the top navigation bar:
   - **Home**
   - **About**
   - **Contact**

---

