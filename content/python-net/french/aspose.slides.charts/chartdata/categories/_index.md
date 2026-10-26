---
title: categories property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartdata/categories/
weight: 70
---
## propriété categories
Obtient les catégories primaires (ou à la fois les catégories primaires et secondaires si la propriété [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) est false).
Lecture seule [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection).

### Remarques
Si la propriété [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) est false alors la propriété [`ChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/secondary_categories) renvoie None et les données de la propriété [`ChartData.categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/categories) sont utilisées à la fois pour les séries primaires et secondaires.
Si la propriété [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) est true alors les données de la propriété [`ChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/secondary_categories) sont utilisées pour les séries secondaires et les données de la propriété [`ChartData.categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/categories) sont utilisées pour les séries primaires.

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