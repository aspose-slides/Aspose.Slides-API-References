---
title: secondary_categories property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories eigenschap
Haalt de secundaire categorieën op als [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) eigenschap true is.
            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection).


### Opmerkingen

Als [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) eigenschap false is dan deze [`IChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories) eigenschap None retourneert en gegevens in [`IChartData.categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories) eigenschap worden gebruikt voor zowel primaire als secundaire series.
            Als [`IChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/use_secondary_categories) eigenschap true is dan gegevens in deze [`IChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/secondary_categories) eigenschap worden gebruikt voor secundaire series en gegevens in [`IChartData.categories`](/slides/python-net/nl/aspose.slides.charts/ichartdata/categories) eigenschap worden gebruikt voor primaire series.

### Definitie:
```python
@property
def secondary_categories(self):
    ...
```


### Zie ook
* klasse [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection)
* klasse [`IChartData`](/slides/python-net/nl/aspose.slides.charts/ichartdata)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)