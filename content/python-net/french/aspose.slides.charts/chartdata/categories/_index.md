---
title: categories property
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.charts/chartdata/categories/
weight: 80
---
## propriété catégories
Obtient les catégories primaires (ou les catégories primaires et secondaires si la propriété [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) est fausse). Lecture seule [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection).

### Remarques

Si la propriété [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) est fausse alors la propriété [`ChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/secondary_categories) renvoie None et les données dans cette propriété [`ChartData.categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/categories) sont utilisées à la fois pour les séries primaires et secondaires. Si la propriété [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) est vraie alors les données dans la propriété [`ChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/secondary_categories) sont utilisées pour les séries secondaires et les données dans cette propriété [`ChartData.categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/categories) sont utilisées pour les séries primaires.

### Définition:
```python
@property
def categories(self):
    ...
```

### Voir aussi
* classe [`ChartData`](/slides/python-net/fr/aspose.slides.charts/chartdata)
* classe [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)