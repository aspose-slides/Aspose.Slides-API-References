---
title: categories property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ichartdata/categories/
weight: 50
---


## categories property
Gets the primary categories (or both primary and secondary categories 
            if [`IChartData.use_secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata/use_secondary_categories) property is false).
            Read-only [`IChartCategoryCollection`](/slides/python-net/aspose.slides.charts/ichartcategorycollection).


### Remarks

If [`IChartData.use_secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata/use_secondary_categories) property is false then [`IChartData.secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata/secondary_categories) 
            property return null and data in this [`IChartData.categories`](/slides/python-net/aspose.slides.charts/ichartdata/categories) property is used both for primary 
            and secondary series.
            If [`IChartData.use_secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata/use_secondary_categories) property is true then data in [`IChartData.secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata/secondary_categories) 
            property is used for secondary series and data in this [`IChartData.categories`](/slides/python-net/aspose.slides.charts/ichartdata/categories) property is used 
            for primary series.

### Definition:
```python
@property
def categories(self):
    ...
```


### See Also
* class [`IChartCategoryCollection`](/slides/python-net/aspose.slides.charts/ichartcategorycollection)
* class [`IChartData`](/slides/python-net/aspose.slides.charts/ichartdata)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

