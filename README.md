# SimpleGST

**SimpleGST** is a minimalist, mobile-friendly web interface for quickly fetching GST-related information or bills in India. Designed for ease-of-use and clarity, SimpleGST helps users get their GST info on any device with a streamlined experience.

---

## 🚀 Features

- **Fast, responsive UI** optimized for both desktop and mobile.
- **Minimal input**: Just enter your GSTIN or required details, click, and get results.
- **Demo mode**: Safe to try, with test results (no API keys required for testing).
- **Easy integration**: Ready for production APIs – just plug your credentials.
- **Clear status messages** and error handling.
- **Quick copy** and download features for invoices or status.

---

## 🖼️ Preview

![screenshot](assets/simplegst-preview.png)

---

## 🛠️ Getting Started

1. **Clone the repo**
    ```
    git clone https://github.com/yourusername/SimpleGST.git
    cd SimpleGST
    ```

2. **Open `index.html`**
    - Simply double-click or serve with any web server.

3. **(Optional) Connect to GST API**
    - Replace the demo fetch logic in `script.js` with your GST bill API call.

---

## ⚡ Demo Usage

1. Enter a dummy GSTIN (e.g., `22AAAAA0000A1Z5`) in the field.
2. Click **Fetch Info**.
3. See mock GST details for demonstration.

---

## 🏗️ Code Structure

- `index.html` — The single-page interface
- `style.css` — All styling (mobile-first, minimalist)
- `script.js` — Handles all bill fetch logic (swap demo logic for real API here)
- `assets/` — (Optional) Add your logo/screenshot here

---

## 📦 Example Integration

Replace demo fetch in `script.js` with your own:

