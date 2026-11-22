---
title: categories property
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chartdata/categories/
weight: 80
---
## ویژگی categories
دسته‌های اصلی را دریافت می‌کند (یا هم دسته‌های اصلی و هم دسته‌های ثانویه اگر ویژگی [`ChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories) برابر false باشد). فقط-خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection).

### توضیحات

اگر ویژگی [`ChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories) برابر false باشد، سپس ویژگی [`ChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/secondary_categories) مقدار None برمی‌گرداند و داده‌های موجود در این ویژگی [`ChartData.categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/categories) هم برای سری‌های اصلی و هم برای سری‌های ثانویه استفاده می‌شود. اگر ویژگی [`ChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/use_secondary_categories) برابر true باشد، داده‌های موجود در ویژگی [`ChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/secondary_categories) برای سری‌های ثانویه و داده‌های موجود در این ویژگی [`ChartData.categories`](/slides/python-net/fa/aspose.slides.charts/chartdata/categories) برای سری‌های اصلی استفاده می‌شود.

### تعریف:
```python
@property
def categories(self):
    ...
```

### موارد مرتبط
* کلاس [`ChartData`](/slides/python-net/fa/aspose.slides.charts/chartdata)
* کلاس [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)