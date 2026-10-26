---
title: enclose method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
Enferme un élément mathématique entre parenthèses

### Returns

L'élément mathématique de type [`IMathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter) qui comprend les parenthèses


```python
def enclose(self):
    ...
```


## enclose(self, beginning_character, ending_character) {#char-char}
Enveloppe les éléments enfants de ce bloc dans les caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement

### Returns

L'élément mathématique de type [`IMathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter) qui comprend les caractères spécifiés comme encadrement


```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| beginning_character | **char** | Caractère de début (généralement un crochet ouvrant) |
| ending_character | **char** | Caractère de fin (généralement un crochet fermant) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Enveloppe les éléments enfants de ce bloc dans les caractères spécifiés tels que des parenthèses ou d'autres comme encadrement et les délimite avec un caractère séparateur

### Returns

L'élément mathématique de type [`IMathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter) qui comprend les caractères spécifiés comme encadrement et délimiteur


```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| beginning_character | **char** | Caractère de début (généralement un crochet ouvrant) |
| ending_character | **char** | Caractère de fin (généralement un crochet fermant) |
| separator_character | **char** | Caractère séparateur |


### Voir aussi
* classe [`IMathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter)
* classe [`MathBlock`](/slides/python-net/fr/aspose.slides.mathtext/mathblock)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)