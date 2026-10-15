# PDFNest website starter

A responsive, original PDF tools website inspired by the general category of online PDF utilities. 

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser. An internet connection is needed to load the PDF-Lib browser library from its CDN.
3. Try Merge PDF, Split PDF, Rotate PDF, Image to PDF, Add watermark, or Add page numbers.

## Implemented in this starter
- Responsive homepage, search, category filters and tool cards
- Browser-based PDF merge, page-range extraction, 90-degree rotation
- JPG/PNG to PDF conversion
- Text watermark and page numbering
- Download result locally; these operations do not upload files to a server

## Not yet implemented
Compression, password encryption, Office conversions, OCR, PDF-to-Word/Excel/PowerPoint, accounts, payments, cloud storage, analytics and production security controls need additional libraries and/or backend services.

## Production checklist
- Add a backend job queue for CPU-heavy or unsupported operations.
- Validate MIME type and file signatures, cap file sizes, rate-limit requests, and scan uploads where appropriate.
- Use short-lived storage URLs and automatic deletion if files are uploaded.
- Publish a privacy policy, retention policy, terms and support contact.
- Add automated tests, error logging without document contents, accessibility checks and monitoring.
- Use your own domain, branding and reviewed dependency versions before launch.

