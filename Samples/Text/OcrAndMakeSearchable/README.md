# OCR PDF and convert to searchable document
This sample shows how to create searchable PDF document from a non-searchable (image-based) document using Docotic.Pdf library and [Tesseract OCR Engine](https://github.com/charlesw/tesseract).

Follow these steps to do OCR when PDF page does not contain searchable text:
1. Save the page as high-resolution image using Docotic.Pdf. Higher resolution leads to better recognition quality.
2. Recognize the image using Tesseract OCR engine. 
3. Insert recognized text chunks back to PDF using Docotic.Pdf.

If your documents contain text in language(s) other than English, then make sure to provide [Language Data Files for Tesseract 3.04/3.05](https://github.com/tesseract-ocr/tessdata/tree/3.04.00) for the language(s) of your document.

Also ensure that you have [Visual Studio 2015 x86 & x64 runtimes](https://www.microsoft.com/en-us/download/details.aspx?id=48145) installed.