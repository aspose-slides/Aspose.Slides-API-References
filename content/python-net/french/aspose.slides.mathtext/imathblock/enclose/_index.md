---
title: enclose method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/imathblock/enclose/
weight: 90
---
## enclose(self) {#}



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| beginning_character | **char** |  |
| ending_character | **char** |  |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Encapsule les éléments enfants de ce bloc dans des caractères spécifiés tels que des parenthèses ou d'autres comme encadrement et les délimite avec un caractère séparateur

### Valeur retournée

L'élément mathématique de type [`IMathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter) qui inclut les caractères spécifiés comme encadrement et délimiteur



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| beginning_character | **char** | Caractère de début (généralement une parenthèse ouvrante) |
| ending_character | **char** | Caractère de fin (généralement une parenthèse fermante) |
| separator_character | **char** | Caractère séparateur |



### Voir aussi
* classe [`IMathBlock`](/slides/python-net/fr/aspose.slides.mathtext/imathblock)
* classe [`IMathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)