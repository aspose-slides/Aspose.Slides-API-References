---
title: series_groups property
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## ویژگی series_groups
دسته‌های سری را برمی‌گرداند.
            فقط-خواندنی [`IChartSeriesGroupCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriesgroupcollection).

### توضیحات

1) هر دسته از سری‌ها شامل سری‌هایی با انواع ترکیبی‌پذیر است. گروه‌های 
            انواع سری‌های ترکیبی‌پذیر با استفاده از enum CombinableSeriesTypesGroup 
            تعریف و توصیف شده‌اند.
            همچنین هر دسته از سری‌ها شامل سری‌هایی است که بر روی محور اصلی یا 
            محور ثانویه ترسیم می‌شوند (نه هر دو در یک دسته).
            بنابراین، اصل گروه‌بندی سری‌ها، گروه‌بندی بر اساس دسته‌های نوع مذکور 
            و بر اساس نوع ترسیم اصلی/ثانویه است.
            
            2) دستهٔ سری شامل برخی خصوصیات سری است که برای هر سری در دسته مشترک است ("خصوصیات گروه سری").
            "خصوصیات گروه سری" در کلاس ChartSeriesGroup قابل خواند و نوشتن است.
            هر یک از "خصوصیات گروه سری" می‌تواند یک تصویر فقط-خواندنی در کلاس ChartSeries داشته باشد.

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