# Interactive-Dictionary
Create a dictionary in Python which can retrieve definitions for user, ask 'did you mean this instead?' if user made a typo while entering the word, and if the word has more than one definition then retrieve them all.

## 1. Installing dependencies

Installing dependencies is the first thing you want to do.
```
import json
import difflib
```

## 2. Understanding files in the directory

### Data
The data is in .json format. If you are not aware what JSON is and how it works I recommend referring to this [article](https://developers.squarespace.com/what-is-json/).
```
dictionary.json
```
