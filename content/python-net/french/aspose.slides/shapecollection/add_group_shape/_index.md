---
title: add_group_shape method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Crée une nouvelle forme de groupe vide et l'ajoute à la fin de la collection de formes.
Le cadre du groupe s'ajustera automatiquement pour contenir toutes les formes qui y sont ajoutées.

### Retour
Le [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape) nouvellement créé.

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Crée une nouvelle forme de groupe, convertit l'image SVG spécifiée en formes individuelles, et ajoute le groupe résultant à la fin de la collection de formes.
Le cadre du groupe s'ajustera automatiquement pour contenir toutes les formes qui y sont ajoutées.

### Retour
Le [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape) nouvellement créé.

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/fr/aspose.slides/isvgimage) | Le [`ISvgImage`](/slides/python-net/fr/aspose.slides/isvgimage) contenant du contenu vectoriel à convertir en formes. |
| x | **float** | La coordonnée x du cadre du groupe, en points. |
| y | **float** | La coordonnée y du cadre du groupe, en points. |
| width | **float** | La largeur du cadre du groupe, en points. |
| height | **float** | La hauteur du cadre du groupe, en points. |

### Voir aussi
* classe [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape)
* classe [`ISvgImage`](/slides/python-net/fr/aspose.slides/isvgimage)
* classe [`ShapeCollection`](/slides/python-net/fr/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)