# Welcome to your Emobility Exercises

## Techniques used
* Publishing: Jupyter-book 
    * published with Github Pages script ghp-import
* Jupyther Notebook 
* Implementation: NumPy
    * Visualization: Matplotlib


## Build instructions
It is build with following
```none
jb build --path-output _build notebooks/
ghp-import -n -p -f _build/_build/html/
```

## Useful Links

* [Jupyter Book documentation](https://jupyterbook.org) 
* [githubpages Import](https://github.com/c-w/ghp-import)


```{tableofcontents}
```
