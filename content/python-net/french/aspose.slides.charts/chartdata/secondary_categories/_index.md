---
title: secondary_categories property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories propriété
Obtient les catégories secondaires si la [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) propriété est vraie.
Lecture seule [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection).


### Remarques

Si la [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) propriété est fausse, alors cette [`ChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/secondary_categories) propriété renvoie None et les données de la [`ChartData.categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/categories) propriété sont utilisées à la fois pour les séries primaires et secondaires.
Si la [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) propriété est vraie, alors les données de cette [`ChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/secondary_categories) propriété sont utilisées pour les séries secondaires et les données de la [`ChartData.categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/categories) propriété sont utilisées pour les séries primaires.

### Définition:
```python
@property
def secondary_categories(self):
    ...
```


### Voir aussi
* classe [`ChartData`](/slides/python-net/fr/aspose.slides.charts/chartdata)
* classe [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)