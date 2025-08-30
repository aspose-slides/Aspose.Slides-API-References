---
title: categories property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartdata/categories/
weight: 70
---


## categories property
Gets the primary categories (or both primary and secondary categories 
            if [`ChartData.use_secondary_categories`](/slides/python-net/aspose.slides.charts/chartdata/use_secondary_categories) property is false).
            Read-only [`IChartCategoryCollection`](/slides/python-net/aspose.slides.charts/ichartcategorycollection).


### Remarks

If [`ChartData.use_secondary_categories`](/slides/python-net/aspose.slides.charts/chartdata/use_secondary_categories) property is false then [`ChartData.secondary_categories`](/slides/python-net/aspose.slides.charts/chartdata/secondary_categories) 
            property return None and data in this [`ChartData.categories`](/slides/python-net/aspose.slides.charts/chartdata/categories) property is used both for primary 
            and secondary series.
            If [`ChartData.use_secondary_categories`](/slides/python-net/aspose.slides.charts/chartdata/use_secondary_categories) property is true then data in [`ChartData.secondary_categories`](/slides/python-net/aspose.slides.charts/chartdata/secondary_categories) 
            property is used for secondary series and data in this [`ChartData.categories`](/slides/python-net/aspose.slides.charts/chartdata/categories) property is used 
            for primary series.

### Definition:
```python
@property
def categories(self):
    ...
```


### See Also
* class [`ChartData`](/slides/python-net/aspose.slides.charts/chartdata)
* class [`IChartCategoryCollection`](/slides/python-net/aspose.slides.charts/ichartcategorycollection)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

