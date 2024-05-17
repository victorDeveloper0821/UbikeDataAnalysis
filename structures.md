# Structures

Hi there, this page will introduce the folder structure in this repository. 

In order to illustrate data analysis with visualization, The project is a jupyter-notebook based. 

## What is in my project?
Use `tree myrepo/` to show your structures of directories

```
├── _build
├── _config.yml
├── _toc.yml
├── data
├── intro.md
├── logo.png
├── markdown-notebooks.md
├── notebooks.ipynb
├── references.bib
├── requirements.txt
├── structures.md
└── youBikeAnalytics.ipynb
```
- _config.yml, _toc.yml, generted by jupyter-book command are used to set up layouts of the websites. 
- Introduction is written as markdown format; clips of Python source codes and chart graphs are shown in ipynb. 

- data, which stores csv of sharing bikes with time. 

## Sample Roles and Directives

Roles and directives are two of the most powerful tools in Jupyter Book. They
are kind of like functions, but written in a markup language. They both
serve a similar purpose, but **roles are written in one line**, whereas
**directives span many lines**. They both accept different kinds of inputs,
and what they do with those inputs depends on the specific role or directive
that is being called.

Here is a "note" directive:

```{note}
Here is a note
```

It will be rendered in a special box when you build your book.

Here is an inline directive to refer to a document: {doc}`markdown-notebooks`.


## Learn more

This is just a simple starter to get you started.
You can learn a lot more at [jupyterbook.org](https://jupyterbook.org).
