---
title: categories property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categorieën eigenschap
Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën 
            als [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) eigenschap false is).
            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection).

### Opmerkingen

Als [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) eigenschap false is, dan [`IChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories) 
            eigenschap return None en gegevens in deze [`IChartData.categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories) eigenschap zowel voor primaire 
            en secundaire series worden gebruikt.
            Als [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) eigenschap true is, dan gegevens in [`IChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories) 
            eigenschap worden gebruikt voor secundaire series en gegevens in deze [`IChartData.categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories) eigenschap worden gebruikt 
            voor primaire series.

### Definitie:
```python
@property
def categories(self):
    ...
```

### Zie ook
* klasse [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection)
* klasse [`IChartData`](/slides/python-net/nl/aspose.slides.charts/ichartdata)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)