---
title: secondary_categories property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories egenskap
Gets the secondary categories if [`ChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories) egenskap is true.
            Skrivskyddad [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection).

### Anmärkningar

If [`ChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories) egenskap is false then this [`ChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/secondary_categories) 
            egenskap return None and data in [`ChartData.categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/categories) 
            egenskap is used both for primära and sekundära series.
            If [`ChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories) egenskap is true then data in 
            this [`ChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/secondary_categories) egenskap is used for sekundära series and data 
            in [`ChartData.categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/categories) egenskap is used for primära series.

### Definition:
```python
@property
def secondary_categories(self):
    ...
```

### Se även
* klass [`ChartData`](/slides/python-net/sv/aspose.slides.charts/chartdata)
* klass [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)