---
title: use_cell property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartcategory/use_cell/
weight: 60
---
## propriété use_cell
Si vrai alors la propriété AsCell est effective. En d'autres termes, la feuille de calcul est utilisée pour
            stocker la catégorie (ce cas prend en charge une catégorie à plusieurs niveaux).
            Si faux alors la propriété AsLiteral est effective. En d'autres termes, la feuille de calcul n'est PAS utilisée
            pour stocker la catégorie (et ce cas ne prend pas en charge des catégories à plusieurs niveaux).
            Lecture seule **bool**.

### Remarques

Pour changer la valeur de cette propriété (pour toutes les catégories de la collection) définissez la nouvelle
            valeur sur la propriété ChartCategoryCollection.UseCells.

### Définition:
```python
@property
def use_cell(self):
    ...
```

### Voir aussi
* classe [`IChartCategory`](/slides/python-net/fr/aspose.slides.charts/ichartcategory)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)