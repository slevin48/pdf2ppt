# PDF to PowerPoint Converter

A client-side tool that converts PDF files to PowerPoint presentations. Runs entirely in the browser - no server uploads required.

## Usage

1. Open `pdf2ppt.html` in a modern browser
2. Drag & drop a PDF (or click to select)
3. Adjust settings if needed (format, quality, scale)
4. Click **Export to PowerPoint** to download the `.pptx`

## Features

- **PowerPoint Export**: Each PDF page becomes a slide with the image filling the entire slide
- **ZIP Download**: Download all pages as individual images in a ZIP file
- **Individual Downloads**: Download specific pages as images
- **Configurable Output**:
  - Format: PNG, JPEG, or WebP
  - Quality: 10-100%
  - Scale: 1x-4x (72-288 DPI)

## Libraries

- [PDF.js](https://mozilla.github.io/pdf.js/) - PDF parsing and rendering
- [PptxGenJS](https://gitbrent.github.io/PptxGenJS/) - PowerPoint file generation
- [JSZip](https://stuk.github.io/jszip/) - ZIP file creation

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge).

## Inspiration

Inspired by Simon Willison's [OCR tool](https://tools.simonwillison.net/ocr) ([source](https://github.com/simonw/tools/blob/main/ocr.html)), which demonstrates client-side PDF processing using PDF.js.
