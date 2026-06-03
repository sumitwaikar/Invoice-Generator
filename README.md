# InvoFlow - Premium Minimal Invoice Generator

A high-fidelity, single-page web application for creating, managing, and printing professional invoices. Built entirely using HTML, CSS (Vanilla), and JavaScript.

---

## 🚀 Getting Started

No installation, build process, or server configuration is required.

1. Navigate to the project directory.
2. **Double-click** the `index.html` file to open it instantly in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Ensure the `logo.png` file remains in the same directory to load the default logo.

---

## ✨ Features

- **Default Logo Pre-loaded**: Starts with your custom **SW** logo ready to print.
- **Minimal Blank Default**: Opens as a blank sheet by default, letting you fill in Sender and Client info from scratch (pre-filled with today's date).
- **WYSIWYG Inline Editor**: Fields look like standard text and highlight with border/shadow prompts only when hovered or focused.
- **Center-Aligned Header**: A balanced, symmetrical header layout with the logo on the left, Invoice Title centered, and the Bill Date block on the right.
- **Dynamic Calculations**:
  - Real-time updates for row totals.
  - Overall subtotal calculation.
  - Proportional tax calculations with custom Discount (%) subtractions.
  - Multiple tax options: GST (automatically breaks down into CGST & SGST 50-50), Flat Tax rate, or No Tax.
- **Minimal Black & White Printing**:
  - Implements the classic **booktabs** table typography format (thick top/bottom borders and clean row dividers) during print processes.
  - Outputs in high-contrast monochrome (pure black text on white background) with a grayscale contrast filter applied to the company logo.
- **Data Persistence**:
  - Save current details as a browser cookie/draft using **Save Draft** and restore them using **Load Draft**.
  - **Clear All Fields** button in the sidebar to reset all sheet entries.
- **Theme Controls**: Sidebar tools for changing base themes (Light/Dark mode) and accent highlights (Indigo, Emerald, Ruby, Violet, Amber).

---

## 🖨️ How to Export to PDF / Print

1. Press **Ctrl + P** (or **Cmd + P** on macOS) or click **Print / Save PDF (₹)** in the sidebar.
2. In the browser print dialog:
   - Set the destination to **Save as PDF** or select your local printer.
   - Set Layout to **Portrait**.
   - Set Paper size to **A4**.
   - Check **Background graphics** under More Settings to render table headers and borders correctly.
3. Click **Save** or **Print**. All interactive sidebar components, editor controls, and blank/placeholder sections will be hidden automatically, leaving a pristine invoice document.

---

## 📂 Project Structure

```
Invoice generator/
├── index.html   # Main self-contained web app (HTML, CSS, JS)
├── logo.png     # Default SW company logo image
└── README.md    # Documentation (this file)
```
