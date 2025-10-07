
# PDF Text Extractor 🧾

A simple Jupyter Notebook that extracts text from PDFs using **PyPDF2**.
Supports both **online PDF downloads** and **local PDF files**.

---

## 🚀 Features

* Extracts text from all pages
* Saves output as UTF-8 `.txt`
* Works with local or remote PDFs
* Auto-creates folders and handles errors

---

## 🧠 Usage

### 1️⃣ Download & Extract

Set a PDF URL and folder path:

```python
pdf_url = "https://example.com/sample.pdf"
folder_path = r"C:\Users\You\Desktop\test"
```

Runs:

* Downloads the PDF
* Extracts all text → `extracted.txt`

### 2️⃣ Extract from Local PDF

```python
pdf_path = r"C:\Users\You\Desktop\test\thesis.pdf"
text_path = r"C:\Users\You\Desktop\test\extracted_pdf.txt"
```

Extracts text → saves to `extracted_pdf.txt`.

---
