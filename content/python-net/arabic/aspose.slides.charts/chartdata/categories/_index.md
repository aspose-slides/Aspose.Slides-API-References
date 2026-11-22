---
title: categories property
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartdata/categories/
weight: 80
---
## categories خاصية
Gets the primary categories (or both primary and secondary categories if [`ChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories) خاصية is false).
Read-only [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection).

### ملاحظات

If [`ChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories) خاصية is false then [`ChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/secondary_categories) خاصية return None and data in this [`ChartData.categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/categories) خاصية is used both for primary and secondary series.
If [`ChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories) خاصية is true then data in [`ChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/secondary_categories) خاصية is used for secondary series and data in this [`ChartData.categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/categories) خاصية is used for primary series.

### تعريف:
```python
@property
def categories(self):
    ...
```

### انظر أيضا
* فئة [`ChartData`](/slides/python-net/ar/aspose.slides.charts/chartdata)
* فئة [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)