---
title: series_groups property
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups ویژگی
گروه‌های سری را دریافت می‌کند.
فقط‌خواندنی [`IChartSeriesGroupCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroupcollection).


### ملاحظات

1) هر گروهی از سری شامل سری‌هایی با انواع ترکیبی است. گروه‌های انواع سری‌های ترکیبی با استفاده از CombinableSeriesTypesGroup enum تعریف و توضیح داده می‌شوند. همچنین هر گروهی از سری شامل سری‌هایی است که بر روی محورهای اصلی یا محورهای ثانویه رسم می‌شوند (نه هر دو حالت در یک گروه). بنابراین، اصل گروه‌بندی سری‌ها، گروه‌بندی بر اساس گروه‌های نوع ذکر شده در بالا و بر پایه نوع نمودار کشی اصلی/ثانویه است.

2) گروهی از سری شامل برخی خصوصیات سری است که برای هر سری در گروه مشترک هستند ("series group properties").
"Series group properties" در کلاس ChartSeriesGroup دارای قابلیت خواندن/نوشتن است.
هر یک از "series group properties" می‌تواند یک پیش‌نمایش فقط‌خواندنی در کلاس ChartSeries داشته باشد.

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