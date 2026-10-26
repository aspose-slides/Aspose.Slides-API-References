---
title: secondary_categories property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories eigenschap
Gets the secondary categories if [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap is true.
            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection).


### Opmerkingen

Als [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap false is dan deze [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) eigenschap return None en gegevens in [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) eigenschap worden zowel voor primaire als secundaire reeksen gebruikt.
Als [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap true is dan worden gegevens in deze [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) eigenschap gebruikt voor secundaire reeksen en gegevens in [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) eigenschap worden gebruikt voor primaire reeksen.

### Definitie:
```python
@property
def secondary_categories(self):
    ...
```


### Zie ook
* klasse [`ChartData`](/slides/python-net/nl/aspose.slides.charts/chartdata)
* klasse [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)