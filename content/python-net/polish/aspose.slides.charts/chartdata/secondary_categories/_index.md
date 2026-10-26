---
title: secondary_categories property
second_title: Aspose.Slides dla Pythona – dokumentacja API .NET
description: 
type: docs
url: /pl/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories właściwość
Gets the secondary categories if [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) property is true.
            Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection).

### Uwagi

If [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) property is false then this [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) 
            property return None and data in [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) property is used both for primary 
            and secondary series.
            If [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) property is true then data in 
            this [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) property is used for secondary series and data 
            in [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) property is used for primary series.

### Definicja:
```python
@property
def secondary_categories(self):
    ...
```

### Zobacz także
* klasa [`ChartData`](/slides/python-net/pl/aspose.slides.charts/chartdata)
* klasa [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)