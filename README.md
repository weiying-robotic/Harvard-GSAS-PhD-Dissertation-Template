# Harvard GSAS PhD Thesis Template (2024 Spring)

This repository contains a LaTeX template tailored from my PhD thesis in Computer Science on **Communication as a Spatial Sensor for Multi-robot Localization and Mapping** , initially based on the [Dissertate](https://github.com/suchow/Dissertate) template. The template has been updated to meet the latest requirement(2024 Spring) and includes some customizations for a smooth writing experience.



## Getting Started 

### Repository Structure

- **dissertation.tex**: The main LaTeX file that includes all chapters and sections.
- **Dissertate.cls**: The custom class file for the thesis.
- **packages/Harvard**: The style files specific to Harvard University.
- **chapters/**: Directory containing individual chapter files.
- **frontmatter/**: Directory for the title page, abstract, dedication, and acknowledgments.
- **endmatter/**: Directory for references and colophon.

### Customization

- **University-specific customization**: Modify `style.sty` to change the university name, degree details, copyright info, location, and colors.
- **Chapter and section structure**: Adjust the organization of chapters in `dissertation.tex`.
- **Bibliography**: Fill your own references in `references.bib`.

## Usage
It is highly suggested to upload the template to Overleaf for better convenience. 
1. **Edit the front matter**: Update the files in the `frontmatter/` directory with your personal and thesis details.
2. **Write your chapters**: Add content to the files in the `chapters/` directory. Each chapter should be a separate `.tex` file.
3. **Compile**: Run `xelatex`, `bibtex`, `xelatex` x2


