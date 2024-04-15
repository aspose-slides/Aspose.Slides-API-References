---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ichartdata/secondary_categories/
weight: 90
---


## secondary_categories property
Gets the secondary categories if [`IChartData.use_secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata#use_secondary_categories) property is true.
            Read-only [`IChartCategoryCollection`](/slides/python-net/aspose.slides.charts/ichartcategorycollection).


### Remarks

If [`IChartData.use_secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata#use_secondary_categories) property is false then this [`IChartData.secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata#secondary_categories) 
            property return null and data in [`IChartData.categories`](/slides/python-net/aspose.slides.charts/ichartdata#categories) property is used both for primary 
            and secondary series.
            If [`IChartData.use_secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata#use_secondary_categories) property is true then data in 
            this [`IChartData.secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata#secondary_categories) property is used for secondary series and data 
            in [`IChartData.categories`](/slides/python-net/aspose.slides.charts/ichartdata#categories) property is used for primary series.

### Definition:
```python
@property
def secondary_categories(self):
    ...
```

### See Also
* class [`IChartCategoryCollection`](/slides/python-net/aspose.slides.charts/ichartcategorycollection)
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
