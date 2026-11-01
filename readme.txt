File Organizer

A simple Python script that automatically organizes all PDF files in the current directory into a separate folder named folder.

📌 Features
Automatically identifies all PDF files in the current directory.
Creates a folder named folder if it doesn't already exist.
Moves all PDF files into the newly created folder.
Renames the files sequentially (file1.pdf, file2.pdf, etc.).
Uses Python's built-in libraries (os), so no external dependencies are required.
🛠️ Technologies Used
Python 3
OS Module

💻 How It Works
Retrieves all files from the current working directory using os.listdir().
Filters files that have the .pdf extension.
Creates a directory named folder if it doesn't exist.
Iterates through the PDF files.
Moves and renames each PDF file into the folder directory.