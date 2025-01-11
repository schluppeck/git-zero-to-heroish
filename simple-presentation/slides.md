---
marp: true
size: 4:3
---

# Zero to Hero(ish) with `git / github`

## Denis Schluppeck, 2025-01-14

---
## `markdown` for the win

- markdown syntax is simple
- any texteditor supports
- renders nicely on github (pages)
- version control (!!)

--- 

## online materials + slides

`marp` has a command line tool, but also [a neat little extensions](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) for [VSCode](https://code.visualstudio.com/) - a favourite code / text editor

```
# H1

## H2, etc.

<!-- html comments !-->

--- 
Three dashes for new slide

```

---

## code 

Code examples are easy (+ highlighted)

```bash
git add slides.md
git commit -m 'my message'
```

or `python` 
```python
def hello_world():
    print("Hallo 🌎!")
```

and `r`
```r
library(dplyr)
d <- read_csv('tidy_data.csv')
```

