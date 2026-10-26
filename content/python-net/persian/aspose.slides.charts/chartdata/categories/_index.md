---
title: categories property
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chartdata/categories/
weight: 70
---
## categories ویژگی
دریافت دسته‌های اصلی (یا هر دو دسته اصلی و فرعی اگر [`ChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories) ویژگی false باشد). فقط-خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection).

### توضیحات
اگر [`ChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories) ویژگی false باشد، آنگاه [`ChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/secondary_categories) ویژگی None بر می‌گرداند و داده‌های موجود در این [`ChartData.categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/categories) ویژگی هم برای سری‌های اصلی و هم برای سری‌های فرعی استفاده می‌شود.
اگر [`ChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories) ویژگی true باشد، داده‌های موجود در [`ChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/secondary_categories) ویژگی برای سری‌های فرعی استفاده می‌شود و داده‌های موجود در این [`ChartData.categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/categories) ویژگی برای سری‌های اصلی استفاده می‌شود.

### تعریف:
```python
@property
def categories(self):
    ...
```

### همچنین ببینید
* کلاس [`ChartData`](/slides/python-net/fa/aspose.slides.charts/chartdata)
* کلاس [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)