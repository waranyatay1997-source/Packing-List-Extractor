# Packing List Extractor

A browser-only GitHub Pages tool that extracts PL#, REMARK, GROSS WGT and NET WGT from multiple packing-list PDFs and adds the results to one table with automatic totals.

## Deploy to GitHub Pages
1. Create or open a GitHub repository.
2. Upload `index.html` and `styles.css` to the repository root.
3. Go to **Settings → Pages** and choose the `main` branch and `/ (root)`.
4. Save and open the published URL.

PDF.js is loaded from cdnjs, so an internet connection is required. PDFs are processed in the browser; the files are not sent to a server. This tool is tuned for the sample layout and should be checked against other PDF layouts.
