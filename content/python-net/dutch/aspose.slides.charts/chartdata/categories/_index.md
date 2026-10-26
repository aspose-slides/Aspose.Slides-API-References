---
title: categories property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdata/categories/
weight: 70
---
## categorieën eigenschap
Verkrijgt de primaire categorieën (of zowel primaire als secundaire categorieën als [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap false is). Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection).

### Opmerkingen

Als [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap false is, dan retourneert [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) eigenschap None en worden gegevens in deze [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) eigenschap zowel voor primaire als voor secundaire series gebruikt.
Als [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap true is, dan worden gegevens in [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) eigenschap gebruikt voor secundaire series en worden gegevens in deze [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) eigenschap gebruikt voor primaire series.

### Definitie:
```python
@property
def categories(self):
    ...
```

### Zie Ook
* klasse [`ChartData`](/slides/python-net/nl/aspose.slides.charts/chartdata)
* klasse [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)