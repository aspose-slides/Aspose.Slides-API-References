---
title: categories property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories egenskap
Hämtar de primära kategorierna (eller både primära och sekundära kategorier om [`IChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/use_secondary_categories) egenskap är falsk).
Skrivskyddad [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection).

### Remarks

Om [`IChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/use_secondary_categories) egenskap är falsk så returnerar [`IChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/secondary_categories) egenskap None och data i denna [`IChartData.categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/categories) egenskap används både för primära och sekundära serier.
Om [`IChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/use_secondary_categories) egenskap är sann så används data i [`IChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/secondary_categories) egenskap för sekundära serier och data i denna [`IChartData.categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/categories) egenskap används för primära serier.

### Definition:
```python
@property
def categories(self):
    ...
```

### Se också
* klass [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection)
* klass [`IChartData`](/slides/python-net/sv/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)