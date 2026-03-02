# Resume
The resume is deliberately kept in text format. The text is laced with latex
directives to have a decent PDF export from it. It has been reviewed and
optimized for AI & ATS parser.


## Generating PDF
I use emacs org-mode to export the raw text to pdf.

- C-c C-e l p : Export using latex
- There are two options for latex, pdflatex and xelatex
- If you are using pdflatex add below latex headers
  - (setq org-latex-compiler "xelatex")
  - LATEX_HEADER: \input{glyphtounicode}
  - LATEX_HEADER: \pdfgentounicode=1
  - LATEX_HEADER: \input{glyphtounicode}
