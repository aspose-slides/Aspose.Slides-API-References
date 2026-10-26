---
title: from_known_color method
second_title: Aspose.Slides pour Python via la référence API .NET
description: 
type: docs
url: /fr/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Crée une couleur à partir de la couleur prédéfinie spécifiée.<br/>C'est la seule façon d'obtenir une couleur système (comme `KnownColor.CONTROL`) : les couleurs système ne sont pas exposées comme des attributs `Color` car leurs valeurs dépendent du thème du bureau, elles sont donc lues depuis le runtime de la bibliothèque.

### Valeur de retour

La couleur que cette méthode crée.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| known_color | **KnownColor** | Un élément de l'énumération `KnownColor` (un `IntEnum` reflétant .NET `System.Drawing.KnownColor`) ou sa valeur entière. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | La valeur n'est pas un membre `KnownColor` valide. |



### Voir aussi
* classe [`Color`](/slides/python-net/fr/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)