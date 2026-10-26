---
title: enclose method
second_title: Aspose.Slides pour Python via l'API de référence .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Enveloppe un élément mathématique entre parenthèses

### Retour
L'élément mathématique de type [`IMathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter) qui inclut les parenthèses



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Enveloppe un élément mathématique dans des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement

### Retour
Si `beginning_character` et `ending_character` sont None, 
            les propriétés correspondantes ne reçoivent que des valeurs et aucun nouvel objet n'est créé (renvoie cette instance).
            Sinon, renvoie un nouvel élément mathématique de type Delimiter qui inclut les caractères spécifiés comme encadrement 
            et cette instance de [`MathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter) encadrée à l'intérieur.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| beginning_character | **char** | Caractère de début (généralement crochet ouvrant) |
| ending_character | **char** | Caractère de fin (généralement crochet fermant) |



### Voir aussi
* classe [`IMathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter)
* classe [`MathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)