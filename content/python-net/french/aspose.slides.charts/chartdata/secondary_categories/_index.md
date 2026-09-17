---
title: secondary_categories property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories propriété
Obtient les catégories secondaires si la propriété [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) est vraie.
            Lecture seule [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection).

### Remarques

Si la propriété [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) est fausse, alors cette [`ChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/secondary_categories) 
            propriété renvoie None et les données de la propriété [`ChartData.categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/categories) sont utilisées à la fois pour les séries primaires 
            et secondaires.
            Si la propriété [`ChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/use_secondary_categories) est vraie, alors les données de 
            cette [`ChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/secondary_categories) propriété sont utilisées pour les séries secondaires et les données 
            de la propriété [`ChartData.categories`](/slides/python-net/fr/aspose.slides.charts/chartdata/categories) sont utilisées pour les séries primaires.

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