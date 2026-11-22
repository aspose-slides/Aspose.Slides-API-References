---
title: categories property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdata/categories/
weight: 80
---
## categorieën eigenschap
Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als de [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap false is). Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection).

### Opmerkingen

Als de [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap false is, dan retourneert de [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) eigenschap None en worden de gegevens in deze [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) eigenschap zowel voor primaire als secundaire series gebruikt.
Als de [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap true is, dan worden de gegevens in de [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) eigenschap gebruikt voor secundaire series en de gegevens in deze [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) eigenschap worden gebruikt voor primaire series.

### Definitie:
```python
@property
def categories(self):
    ...
```

### Zie ook
* klasse [`ChartData`](/slides/python-net/nl/aspose.slides.charts/chartdata)
* klasse [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)