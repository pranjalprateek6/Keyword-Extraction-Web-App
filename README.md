# Keyword-Extraction-Web-App
The "Keyword Extraction Web App" is a web application created using Streamlit, a Python library for building web-based data applications. This particular app is designed to perform keyword extraction from various types of text files, including PDF, DOCX, PPTX, and plain text (TXT) files.
Here's a brief description of its main features:

1. File Upload: Users can upload text files in different formats, such as PDF, DOCX, PPTX, or TXT.

2. Keyword Extraction: The app employs the Rake-NLTK library to extract keywords from the uploaded files. Rake-NLTK is a natural language processing tool specifically designed for keyword extraction.

3. Keyword Filtering: Keywords extracted from the text are filtered and cleaned to ensure they meet specific criteria:
• Keywords must be more than four characters in length.
• Keywords should contain only alphanumeric characters (no special characters).
• Common stop words (e.g., "the," "and," "is") are removed.

4. Keyword Display: The app displays both the content of the uploaded file and the extracted, filtered keywords in separate sections of the user interface.

5. Keyword Saving: Users have the option to save the extracted keywords to a text file (extracted_keywords.txt) by clicking a "Save Keywords to File" button.
