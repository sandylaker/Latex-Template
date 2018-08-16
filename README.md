# Latex-Template
a latex template based on TU Design package

---
## Some useful methods and commands in writing Latex.
### define a new command to insert python code inline.
```latex
\newcommand{\py}[1]{\mintinline{python}{#1}}
```
### define a new command for derivative operator
```latex
\newcommand{\deriv}[1]{\mathrm{d}{#1}}
```
### global settings for minted environment 
wrap the codes in a frame so that the codes won't overflow into the left/right/bottom margin.
```latex
setminted[python3]{linenos=true,breaklines=true,bgcolor=bg, xleftmargin=\parindent,frame=single, framesep=2mm}
```
