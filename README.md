# The Dark Side of Capitalism: The Slave Trade in Britain from the 17th to the 19th Century

This project is a bachelor dissertation titled **"The Dark Side of Capitalism: The Slave Trade in Britain from the 17th to the 19th Century"**. The dissertation explores the connection between capitalism and slavery in Britain during this period, based on Eric Williams' seminal work *Capitalism and Slavery*.

## Description

This LaTeX project contains the complete dissertation written using LaTeX on Visual Studio Code (VS Code). The document examines the historical context and implications of the slave trade in Britain and its intersection with capitalist practices from the 17th to the 19th century.

## Installation

To compile this LaTeX document, you will need LaTeX installed on your system along with the necessary extensions for VS Code.

### Requirements

- **LaTeX Distribution**: TeX Live or MiKTeX.
- **VS Code Extension**: LaTeX Workshop for LaTeX support.
- **Compilation Tool**: `xelatex` and `biber`.

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/samdot07/dissertation.git
2. Navigate to the project directory:
   ```bash
   cd REPOSITORY
4. Install LaTeX packages and ensure you have xelatex and biber installed.
5. Ensure your VS Code settings are configured for LaTeX and biber as specified in the settings.json file.

### Compiling Instructions

1. Open the integrated terminal in VS Code.
2. Compile the document using xelatex:
   ```bash
   xelatex main.tex
3. Run biber to process the bibliography:
   ```bash
   biber main
4. Re-run xelatex to ensure all references are updated:
   ```bash
   xelatex main.tex
   xelatex main.tex

# Project Structure

The project is organized as follows:

- main.tex: The main LaTeX source file for the dissertation.
- bibliography/: Contains the bibliography file.
- fonts: any custom fonts used in the document.
- images/: Directory with images used in the dissertation.
- contents/: Contains the core components of the dissertation:
  - Abstract.tex: The abstract of the dissertation.
  - ResponsibilityDeclaration.tex: The responsibility declaration.
  - statement.tex: The statement.
  - TitlePage.tex: The title page.
  - chapters/: Contains individual chapters of the dissertation.
  - sections/: Contains sections divided by chapters.
### Aknowledgments
The project was built using a template adapted from Luca Modica’s Bachelor Thesis Template on Overleaf.
https://www.overleaf.com/latex/templates/template-bachelors-thesis-in-computer-science-university-of-turin/znktghkynbhw
