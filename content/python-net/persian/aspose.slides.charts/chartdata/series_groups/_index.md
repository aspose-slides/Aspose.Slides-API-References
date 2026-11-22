---
title: series_groups property
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups ویژگی
دسته‌های سری را دریافت می‌کند.
            فقط-خواندنی [`IChartSeriesGroupCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroupcollection).

### توضیحات

1) هر گروهی از سری‌ها شامل سری‌هایی با انواع ترکیبی است. گروه‌های انواع سری‌های ترکیبی با استفاده از شمارنده CombinableSeriesTypesGroup تعریف و توصیف شده‌اند. همچنین هر گروهی از سری‌ها شامل سری‌هایی است که بر روی محورهای اصلی یا بر روی محورهای ثانویه ترسیم می‌شوند (هر دو حالت در یک گروه وجود ندارد). بنابراین، اصل گروه‌بندی سری‌ها، گروه‌بندی بر اساس انواع ذکر شده در بالا و نوع ترسیم اولیه/ثانویه است.

2) گروه سری شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است («ویژگی‌های گروه سری»). «ویژگی‌های گروه سری» در کلاس ChartSeriesGroup قابلیت خواندن/نوشتن است. هر یک از «ویژگی‌های گروه سری» می‌تواند یک پروجکشن فقط-خواندنی در کلاس ChartSeries داشته باشد.

### تعریف:
```python
@property
def series_groups(self):
    ...
```

### موارد مرتبط
* کلاس [`ChartData`](/slides/python-net/fa/aspose.slides.charts/chartdata)
* کلاس [`IChartSeriesGroupCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroupcollection)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)