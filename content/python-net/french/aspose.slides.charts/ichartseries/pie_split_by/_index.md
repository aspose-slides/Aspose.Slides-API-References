---
title: pie_split_by property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by propriété
Spécifie comment déterminer quels points de données se trouvent dans le deuxième secteur ou barre sur un graphique à secteurs imbriqués ou à barres imbriquées.
Cette propriété concerne non seulement cette série mais toutes les séries du groupe de séries parent – il s’agit de la projection de la propriété de groupe appropriée. Ainsi, cette propriété est en lecture seule.
Utilisez la propriété ParentSeriesGroup pour accéder au groupe de séries parent.
Utilisez la propriété en lecture/écriture ParentSeriesGroup.PieSplitBy pour modifier la valeur.
Lecture seule [`PieSplitType`](/slides/python-net/fr/aspose.slides.charts/piesplittype).

### Remarques

1) Il s’agit de la projection de la propriété ParentSeriesGroup.PieSplitBy.
2) Si la valeur de la propriété est PieSplitType.Custom, vous pouvez définir des informations de fractionnement personnalisées avec la propriété ParentSeriesGroup.PieSplitCustomPoints.

### Définition:
```python
@property
def pie_split_by(self):
    ...
```

### Voir aussi
* classe [`IChartSeries`](/slides/python-net/fr/aspose.slides.charts/ichartseries)
* énumération [`PieSplitType`](/slides/python-net/fr/aspose.slides.charts/piesplittype)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)