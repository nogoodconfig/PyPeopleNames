# PyPeopleNames
A python package to extract full western 'people' names from a string

## Prerequisites
Requires NLTK and various word sets. These are downloaded automatically from the internet when the function is run to fetch the full sets or updated sets.

## Installing
Package is part of the Python Package Index:
```
pip install pypeoplenames
```
## Using
Takes a string as an input and returns a list of people names:

```
names = pypeoplenames(text)
```

## Built With
* [NLTK](https://www.nltk.org/) - The awesome natural language toolkit for understanding word types
* [Enchant](https://github.com/rfk/pyenchant) - A spellchecking library for Python, used for it's English dictionary