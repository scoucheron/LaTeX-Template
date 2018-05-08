# LaTeX-Template
My personal LaTeX-Template based on the [IEEE conference.](https://www.ieee.org/conferences/publishing/templates.html)

## Add more Sections
- Create a new file with the name of the section (FILENAME)
- In main.tex write
```
\begin{abstract}
\input{sections/FILENAME.tex}
\end{abstract}
```

## Folders
### Images
All images that is to be imported in main.tex

### Sections
Each section is written individually and in a .tex file, and then imported in main.tex.
