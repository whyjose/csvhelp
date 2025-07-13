# CSV Helper

**CSV Helper** is a lightweight, client-side web tool that allows users to upload CSV files, select a column, and convert its data into various formats like comma-separated, JSON array, newline-separated, and more. It includes support for theme toggling (light/dark mode).

## 🚀 Features

* 📂 Drag-and-drop CSV file support
* 🔠 Column selection from header
* 🔧 Export formats:

  * Comma-separated
  * Space-separated
  * Semicolon-separated
  * Pipe-separated
  * JSON Array
  * Quoted CSV
  * New Line
* 🌗 Dark/Light theme toggle
* 📋 Copy to clipboard and file download (CSV or TXT)

---

## 🛠️ How to Use

1. Open the webpage in a browser.
2. Drag a `.csv` file into the drop zone or click to select one.
3. Choose the desired column from the dropdown.
4. Select the output format.
5. Click **Generate Output**.
6. Copy the result or download it as a file.

---

## 🔒 Security Notes

* CSV injection prevention is recommended before exporting (e.g., escape formulas like `=HYPERLINK(...)`).
* The tool is entirely client-side, so no data is uploaded.

---

## 🧩 Dependencies

* [PapaParse](https://www.papaparse.com/) – Fast, powerful CSV parser for JavaScript

---

## 📄 License

MIT License. Feel free to use and modify.

---

## ✨ Author

Created by José – Contributions welcome!

---

## 📬 Feedback

Have suggestions or issues? Open a GitHub issue or submit a pull request!
