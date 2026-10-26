---
title: categories property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## propriété categories
Obtient les catégories principales (ou à la fois les catégories principales et secondaires si [`IChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories) propriété est false). Lecture seule [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection).

### Remarques

Si [`IChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories) propriété est false alors [`IChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/secondary_categories) propriété renvoie None et les données dans cette [`IChartData.categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/categories) propriété sont utilisées à la fois pour les séries principales et secondaires. Si [`IChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories) propriété est true alors les données dans [`IChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/secondary_categories) propriété sont utilisées pour les séries secondaires et les données dans cette [`IChartData.categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/categories) propriété sont utilisées pour les séries principales.

### Définition:
```python
@property
def categories(self):
    ...
```

### Voir aussi
* classe [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection)
* classe [`IChartData`](/slides/python-net/fr/aspose.slides.charts/ichartdata)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)