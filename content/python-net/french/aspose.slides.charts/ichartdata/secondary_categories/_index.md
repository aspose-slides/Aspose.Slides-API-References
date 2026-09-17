---
title: secondary_categories property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories propriété
Récupère les catégories secondaires si la propriété [`IChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories) est true.
            Lecture seule [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection).

### Remarques

Si la propriété [`IChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories) est false alors cette propriété [`IChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/secondary_categories) 
            renvoie None et les données de la propriété [`IChartData.categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/categories) sont utilisées à la fois pour les séries primaires et secondaires.
            Si la propriété [`IChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories) est true alors les données de cette propriété [`IChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/secondary_categories) sont utilisées pour les séries secondaires et les données de la propriété [`IChartData.categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/categories) sont utilisées pour les séries primaires.

### Définition:
```python
@property
def secondary_categories(self):
    ...
```

### Voir aussi
* classe [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection)
* classe [`IChartData`](/slides/python-net/fr/aspose.slides.charts/ichartdata)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)