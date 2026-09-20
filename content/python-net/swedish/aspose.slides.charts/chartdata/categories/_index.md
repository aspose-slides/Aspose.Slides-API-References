---
title: categories property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartdata/categories/
weight: 70
---
## categories egenskap
Hämtar de primära kategorierna (eller både primära och sekundära kategorier
om [`ChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories) egenskap är falsk).
Skrivskyddad [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection).

### Anmärkningar

Om [`ChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories) egenskap är falskt då [`ChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/secondary_categories) egenskap return None och data i denna [`ChartData.categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/categories) egenskap används både för primär
och sekundär serier.
Om [`ChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories) egenskap är sant då data i [`ChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/secondary_categories) egenskap används för sekundär serier och data i denna [`ChartData.categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/categories) egenskap används för primär serier.

### Definition:
```python
@property
def categories(self):
    ...
```

### Se även
* klass [`ChartData`](/slides/python-net/sv/aspose.slides.charts/chartdata)
* klass [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)