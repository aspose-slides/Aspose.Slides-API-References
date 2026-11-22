---
title: categories property
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## ویژگی categories
دسته‌بندی‌های اولیه را دریافت می‌کند (یا هر دو دسته‌بندی اولیه و ثانویه اگر ویژگی [`IChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories) false باشد). فقط خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection).

### توضیحات
اگر ویژگی [`IChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories) false باشد، سپس ویژگی [`IChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/secondary_categories) مقدار None را برمی‌گرداند و داده در این ویژگی [`IChartData.categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/categories) هم برای سری‌های اولیه و هم برای سری‌های ثانویه استفاده می‌شود.
اگر ویژگی [`IChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories) true باشد، سپس داده در ویژگی [`IChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/secondary_categories) برای سری‌های ثانویه استفاده می‌شود و داده در این ویژگی [`IChartData.categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/categories) برای سری‌های اولیه استفاده می‌شود.

### تعریف:
```python
@property
def categories(self):
    ...
```

### موارد مرتبط
* کلاس [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection)
* کلاس [`IChartData`](/slides/python-net/fa/aspose.slides.charts/ichartdata)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)