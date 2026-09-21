---
title: series_groups property
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups خصوصیت
گروه‌های سری را دریافت می‌کند.
فقط‌خواندنی [`IChartSeriesGroupCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroupcollection).

### توضیحات

۱) هر گروهی از سری شامل سری‌هایی با انواع ترکیبی است. گروه‌های انواع سری‌های ترکیبی با enum CombinableSeriesTypesGroup تعریف و توصیف شده‌اند. همچنین هر گروهی از سری شامل سری‌هایی است که در محورهای اصلی یا محورهای ثانویه رسم می‌شوند (هر دو حالت در یک گروه وجود ندارد). بنابراین، اصل گروه‌بندی سری‌ها بر مبنای گروه‌های نوع ذکر شده در بالا و نوع رسم اصلی/ثانویه است.

۲) گروهی از سری شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است («series group properties»). «Series group properties» در کلاس ChartSeriesGroup خواندنی/نوشتنی است. هر یک از «Series group properties» می‌تواند یک پیش‌نمایش فقط‌خواندنی در کلاس ChartSeries داشته باشد.

### تعریف:
```python
@property
def series_groups(self):
    ...
```

### موارد مرتبط
* کلاس [`IChartData`](/slides/python-net/fa/aspose.slides.charts/ichartdata)
* کلاس [`IChartSeriesGroupCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroupcollection)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)