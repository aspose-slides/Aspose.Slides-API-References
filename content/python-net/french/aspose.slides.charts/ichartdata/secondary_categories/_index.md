---
title: secondary_categories property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartdata/secondary_categories/
weight: 130
---
## propriété secondary_categories
Obtient les catégories secondaires si la propriété [`IChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories) est vraie.
            Lecture seule [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection).


### Remarques

Si la propriété [`IChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories) est fausse alors cette [`IChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/secondary_categories) 
            propriété renvoie None et les données de la propriété [`IChartData.categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/categories) sont utilisées à la fois pour les séries principales 
            et les séries secondaires.
            Si la propriété [`IChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories) est vraie alors les données de 
            cette [`IChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/secondary_categories) propriété est utilisée pour les séries secondaires et les données 
            de la propriété [`IChartData.categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/categories) sont utilisées pour les séries principales.

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