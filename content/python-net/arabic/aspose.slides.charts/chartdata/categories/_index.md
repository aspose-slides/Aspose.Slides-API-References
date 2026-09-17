---
title: categories property
second_title: Aspose.Slides للـ Python عبر مرجع API .NET
description: 
type: docs
url: /ar/aspose.slides.charts/chartdata/categories/
weight: 70
---
## خاصية الفئات
يسترجع الفئات الأساسية (أو الفئات الأساسية والثانوية إذا كانت خاصية [`ChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories) false).
قراءة فقط [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection).

### ملاحظات

إذا كانت خاصية [`ChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories) false فإن خاصية [`ChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/secondary_categories) تعيد None وتُستخدم البيانات في خاصية [`ChartData.categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/categories) لكل من السلسلة الأساسية والثانوية.
إذا كانت خاصية [`ChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/use_secondary_categories) true فإن البيانات في خاصية [`ChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/secondary_categories) تُستخدم للسلسلة الثانوية والبيانات في خاصية [`ChartData.categories`](/slides/python-net/ar/aspose.slides.charts/chartdata/categories) تُستخدم للسلسلة الأساسية.

### التعريف:
```python
@property
def categories(self):
    ...
```

### انظر أيضًا
* الفئة [`ChartData`](/slides/python-net/ar/aspose.slides.charts/chartdata)
* الفئة [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)