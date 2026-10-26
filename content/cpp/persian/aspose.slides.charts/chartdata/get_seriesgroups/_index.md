---
title: get_SeriesGroups()
second_title: مرجع API Aspose.Slides برای C++
description: دسته‌های سری را دریافت می‌کند. فقط‌خواندنی IChartSeriesGroupCollection.
type: docs
weight: 27
url: /fa/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() متد

دسته‌های سری را دریافت می‌کند. فقط‌خواندنی [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## توضیحات

1) هر گروهی از سری شامل سری‌هایی با انواع قابل ترکیب است. گروه‌های انواع سری‌های قابل ترکیب با استفاده از enum CombinableSeriesTypesGroup تعریف و توصیف می‌شوند. همچنین هر گروهی از سری شامل سری‌هایی است که روی محورهای اصلی یا روی محورهای ثانویه (نه هر دو حالت در یک گروه) ترسیم می‌شوند. بنابراین، اصل گروه‌بندی سری‌ها گروه‌بندی بر اساس گروه‌های نوع مذکور و بر اساس نوع ترسیم اصلی/ثانویه است.

2) گروه سری شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است ("ویژگی‌های گروه سری"). "ویژگی‌های گروه سری" در کلاس [ChartSeriesGroup](../../chartseriesgroup/) قابل خواندن/نوشتن است. هر یک از "ویژگی‌های گروه سری" می‌تواند یک نمای فقط-خواندنی در کلاس [ChartSeries](../../chartseries/) داشته باشد.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* کلاس [ChartData](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)