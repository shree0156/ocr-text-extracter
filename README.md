OCR Text Extractor

A simple Python project that extracts text from images using **Tesseract OCR** and **OpenCV**.  
Built in Google Colab — perfect for quick prototyping and showcasing OCR and CV skills.

---

 Tools & Libraries Used
- Python (via Google Colab)
- OpenCV (for image preprocessing)
- Pytesseract (Python wrapper for Tesseract OCR)
- Tesseract OCR Engine

---

What It Does
- Loads any image that contains text (e.g., printed text, signs)
- Preprocesses the image using grayscale + thresholding for better OCR accuracy
- Extracts text using Tesseract
- Displays the text and saves it to a `.txt` file

---

Files Included
- `ocr_text_extractor.ipynb` → The main notebook
- `sample_image.jpg` → Example input image 
- `README.md` → This file!

---

How to Use (Google Colab)
1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload your image to the Colab environment
3. Run all cells
4. View extracted text in output and/or saved `.txt` file

---

Sample Output
OCR Result:
The quick brown fox
jumped over the 5
lazy dogs!

Text saved to extracted_text.txt

