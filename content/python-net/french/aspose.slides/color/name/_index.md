---
title: name property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/color/name/
weight: 190
---
## name propriété
Obtient le nom de cette couleur.<br/>            Pour une couleur nommée (une constante nommée telle que `Color.red`, ou une couleur créée avec [`from_name`](/slides/python-net/fr/aspose.slides/color/from_name/)) le nom .NET est renvoyé, par ex. `"Red"` ou `"LightBlue"`.<br/>            Pour toute autre couleur la valeur ARGB est renvoyée en hexadécimal minuscule sans remplissage de zéros, par ex. `"ffff0000"`. `Color.empty.name` est `"0"`.
            Lecture seule **str**.

### Définition:
```python
@property
def name(self):
    ...
```


### Voir aussi
* classe [`Color`](/slides/python-net/fr/aspose.slides/color)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)