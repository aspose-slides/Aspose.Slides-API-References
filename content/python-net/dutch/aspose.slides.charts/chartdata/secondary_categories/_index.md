---
title: secondary_categories property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories eigenschap
Verkrijgt de secundaire categorieën als [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap waar is.
            Alleen-lezen [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection).

### Opmerkingen

Als [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap onwaar is dan deze [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) 
            eigenschap geeft None terug en gegevens in [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) eigenschap worden zowel voor primaire 
            en secundaire reeksen.
            Als [`ChartData.use_secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/use_secondary_categories) eigenschap waar is dan gegevens in 
            deze [`ChartData.secondary_categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/secondary_categories) eigenschap wordt gebruikt voor secundaire reeksen en gegevens 
            in [`ChartData.categories`](/slides/python-net/nl/aspose.slides.charts/chartdata/categories) eigenschap wordt gebruikt voor primaire reeksen.

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