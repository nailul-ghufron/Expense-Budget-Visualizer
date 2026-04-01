# 💰 Expense & Budget Visualizer

> A mobile-friendly web app to track daily spending, visualize category distribution, and stay on top of your budget — no sign-up required.

🔗 **[Live Demo →](https://ghufron99119.github.io/Expense_And_Budget_Visualizer-Project)**

---

## 📌 Project Overview

**Expense & Budget Visualizer** is a lightweight, client-side web application that helps users manage their daily finances with ease. It provides a clean interface to log expenses, monitor a running total balance, and understand spending habits through an interactive pie chart — all without needing an account or internet connection after the first load.

All data is stored locally in the browser using the **LocalStorage API**, meaning your transactions persist across page refreshes without any backend or database.

---

## ✨ Key Features

### MVP Features
| Feature | Description |
|---|---|
| 📝 Input Form | Add transactions with Item Name, Amount, and Category (Food, Transport, Fun) |
| ✅ Form Validation | All fields are required — clear error messages guide the user |
| 📋 Transaction List | Scrollable list showing name, amount, category, and date |
| 🗑️ Delete Transaction | Remove any transaction instantly with a single click |
| 💵 Total Balance | Auto-updates at the top whenever transactions are added or removed |
| 🥧 Pie Chart | Dynamic Chart.js pie chart showing spending distribution by category |

### ⚡ Optional Challenges Completed
| Challenge | Description |
|---|---|
| 🌙 Dark / Light Mode | Toggle between themes — preference saved to LocalStorage |
| 🔃 Sort Transactions | Sort by newest, oldest, amount (high/low), or category A–Z |
| 🚨 Spending Limit Highlight | Set a per-item limit — transactions exceeding it are highlighted in red |

---

## 🛠️ Tech Stack

| Technology | Role |
|---|---|
| **HTML5** | Semantic page structure |
| **CSS3** | Styling, CSS Variables for theming, responsive layout |
| **Vanilla JavaScript** | DOM manipulation, form validation, LocalStorage, sorting logic |
| **[Chart.js v4](https://www.chartjs.org/)** | Pie chart rendering (loaded via CDN) |

> ⚠️ No frameworks (React, Vue, Angular, etc.) were used. This project intentionally relies on pure browser APIs only.

---

## 📁 Folder Structure

```
Expense_And_Budget_Visualizer-Project/
│
├── index.html          # Main HTML entry point
│
├── css/
│   └── style.css       # All styles — layout, theme variables, components
│
├── js/
│   └── script.js       # All logic — CRUD, validation, sorting, chart, theme
│
└── README.md
```

> Per project rules: only **1 CSS file** inside `css/` and only **1 JS file** inside `js/`.

---

## 🚀 How to Use

### Run Locally

No build tools or installations needed.

1. Clone the repository:
   ```bash
   git clone https://github.com/ghufron99119/Expense_And_Budget_Visualizer-Project.git
   ```
2. Open the project folder and launch `index.html` in any modern browser:
   ```
   Double-click index.html
   — or —
   Right-click → Open with → Chrome / Firefox / Edge
   ```
3. Start adding transactions. Your data is saved automatically.

### Using the App

1. Fill in the **Item Name**, **Amount**, and **Category** fields, then click **Add Transaction**.
2. View your **Total Balance** update at the top.
3. Use the **Sort** dropdown to reorder your transaction list.
4. Set a **Spending Limit** to highlight any item that exceeds your budget.
5. Toggle **🌙 / ☀️** in the header to switch between dark and light mode.
6. Click **✕** on any transaction to delete it.

---

## 🌐 Browser Compatibility

| Browser | Supported |
|---|---|
| Google Chrome | ✅ |
| Mozilla Firefox | ✅ |
| Microsoft Edge | ✅ |
| Safari | ✅ |

---

## 👤 Author

**Nailul Ghufron**
🔗 [github.com/ghufron99119](https://github.com/nailul-ghufron)

---

*Built as part of the RevoU Frontend Development assignment.*
#
