---
title: categories property
second_title: مرجع API لـ Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## خاصية الفئات
Gets the primary categories (or both primary and secondary categories 
            if [`IChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories) خاصية is false).
            Read-only [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection).

### ملاحظات

If [`IChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories) خاصية is false then [`IChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/secondary_categories) 
            خاصية return None and data in this [`IChartData.categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/categories) خاصية is used both for primary 
            and secondary series.
            If [`IChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories) خاصية is true then data in [`IChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/secondary_categories) 
            خاصية is used for secondary series and data in this [`IChartData.categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/categories) خاصية is used 
            for primary series.

### التعريف:
```python
@property
def categories(self):
    ...
```

### انظر أيضًا
* فئة [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection)
* فئة [`IChartData`](/slides/python-net/ar/aspose.slides.charts/ichartdata)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)