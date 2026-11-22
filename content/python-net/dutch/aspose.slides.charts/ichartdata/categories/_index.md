---
title: categories property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## categorieën eigenschap
Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) eigenschap onwaar is). Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection).

### Opmerkingen

Als [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) eigenschap onwaar is, dan geeft [`IChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories) eigenschap None terug en worden gegevens in deze [`IChartData.categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories) eigenschap zowel voor primaire als secundaire series gebruikt. Als [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) eigenschap waar is, dan worden gegevens in [`IChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories) eigenschap voor secundaire series gebruikt en worden gegevens in deze [`IChartData.categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories) eigenschap voor primaire series gebruikt.

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