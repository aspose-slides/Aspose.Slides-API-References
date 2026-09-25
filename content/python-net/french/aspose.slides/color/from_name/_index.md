---
title: from_name method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Crée une couleur à partir du nom spécifié d'une couleur prédéfinie.<br/>La recherche n'est pas sensible à la casse et ignore les traits de soulignement et les espaces : `"LightBlue"`, `"lightblue"` et `"light_blue"` aboutissent toutes à `Color.light_blue`. Voir la page de classe [`Color`](/slides/python-net/fr/aspose.slides/color) pour la liste des couleurs prédéfinies.

### Returns

La couleur nommée.



```python
@staticmethod
def from_name(name):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| name | **str** | Une chaîne qui est le nom d'une couleur prédéfinie. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | Le nom n'est pas celui d'une couleur prédéfinie. |
| **TypeError** | Le nom n'est pas une chaîne. |



### See Also
* classe [`Color`](/slides/python-net/fr/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)