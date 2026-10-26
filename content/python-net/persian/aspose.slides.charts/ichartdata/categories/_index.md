---
title: categories property
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories خصوصیت
دسته‌های اصلی را دریافت می‌کند (یا هر دو دستهٔ اصلی و فرعی اگر [`IChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories) خصوصیت نادرست باشد). فقط-خواندنی [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection).

### ملاحظات
اگر [`IChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories) خصوصیت نادرست باشد، آنگاه [`IChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/secondary_categories) خصوصیت مقدار None را باز می‌گرداند و داده‌های این [`IChartData.categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/categories) خصوصیت برای هر دو سری اصلی و فرعی استفاده می‌شود. اگر [`IChartData.use_secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/use_secondary_categories) خصوصیت درست باشد، داده‌های [`IChartData.secondary_categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/secondary_categories) خصوصیت برای سری‌های فرعی استفاده می‌شود و داده‌های این [`IChartData.categories`](/slides/python-net/fa/aspose.slides.charts/ichartdata/categories) خصوصیت برای سری‌های اصلی استفاده می‌شود.

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