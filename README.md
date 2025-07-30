# Python-to-PDF-converter
Convert Python `.py` files into styled PDFs with syntax highlighting, line numbers, and background coloring — mimicking the IDLE editor appearance.

## ✨ Features

- 📌 Converts Python scripts to PDF
- 🌈 IDLE-style syntax highlighting using **Pygments**
- 🧮 Line numbering
- 🎨 Background color support (e.g., off-white, dark mode)
- 📜 PDF rendering via **ReportLab**

## 📂 Usage

1. Place the Python file you want to convert in the same directory as this script.
2. Modify the following lines at the bottom of the script:

```python
input_python_file = "your_script.py"
output_pdf_file = "your_output.pdf"
```

3. Run the script:

```bash
python PyToPdf_30_07_2025.py
```

## 🛠️ Dependencies

Install required libraries:

```bash
pip install reportlab pygments
```

## 📁 Output

- A PDF file with monospaced font, syntax-highlighted tokens, line numbers, and a light background.
- Output file will be saved with the name you provide in `output_pdf_file`.

## 📘 Example

Converts `PyToPdf6_Working.py` to `PDF_Out.pdf` with formatted and color-coded output.

## 🎨 Customization

- Modify the `style_map` dictionary to change token colors.
- Change `canvas.setFillColor()` to customize the background.

---

Created: July 30, 2025
