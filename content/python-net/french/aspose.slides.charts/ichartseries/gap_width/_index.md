---
title: gap_width property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartseries/gap_width/
weight: 170
---
## gap_width propriété
Specifie l'espace entre les grappes de barres ou de colonnes, exprimé en pourcentage de la largeur de la barre ou de la colonne.
            This is the property not only of this series but of all series of parent series 
            group - this is projection of appropriate group property. And so this property 
            is read-only.
            Use ParentSeriesGroup property for access to parent series group.
            Use ParentSeriesGroup.GapWidth read/write property for change value.
            Lecture seule **int**.

### Remarques

This is the projection of the property ParentSeriesGroup.GapWidth.

### Définition :
```python
@property
def gap_width(self):
    ...
```

### Voir aussi
* classe [`IChartSeries`](/slides/python-net/fr/aspose.slides.charts/ichartseries)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)