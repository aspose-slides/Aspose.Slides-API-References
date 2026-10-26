---
title: categories property
second_title: مرجع API لـ Aspose.Slides لبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## خاصية الفئات
يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كانت الخاصية [`IChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories) غير صحيحة). غير قابل للتعديل [`IChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcategorycollection).

### ملاحظات
إذا كانت الخاصية [`IChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories) غير صحيحة فإن الخاصية [`IChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/secondary_categories) تعيد None وتُستخدم البيانات في الخاصية [`IChartData.categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/categories) لكل من السلسلة الأساسية والثانوية. إذا كانت الخاصية [`IChartData.use_secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/use_secondary_categories) صحيحة فإن البيانات في الخاصية [`IChartData.secondary_categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/secondary_categories) تُستخدم للسلسلة الثانوية وتُستخدم البيانات في الخاصية [`IChartData.categories`](/slides/python-net/ar/aspose.slides.charts/ichartdata/categories) للسلسلة الأساسية.

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