---
title: get_SeriesGroups()
second_title: Aspose.Slides برای C++ مرجع API
description: گروه‌های سری را دریافت می‌کند. فقط خواندنی IChartSeriesGroupCollection.
type: docs
weight: 27
url: /fa/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() method

گروه‌های سری را دریافت می‌کند. فقط-خواندنی [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## توضیحات

1) هر گروه از سری‌ها شامل سری‌هایی با انواع ترکیب‌پذیر است. گروه‌های انواع سری‌های ترکیب‌پذیر با شمارنده CombinableSeriesTypesGroup تعریف و توصیف می‌شوند. همچنین هر گروه از سری‌ها شامل سری‌هایی است که بر روی محورهای اصلی یا محورهای ثانویه رسم می‌شوند (نه هر دو مورد در یک گروه). بنابراین، اصل گروه‌بندی سری‌ها بر مبنای گروه‌های نوع مذکور و نوع رسم اصلی/ثانویه است.

2) گروه سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است («ویژگی‌های گروه سری»). «ویژگی‌های گروه سری» در کلاس [ChartSeriesGroup](../../chartseriesgroup/) قابل خواندن/نوشتن است. هر یک از «ویژگی‌های گروه سری» می‌تواند در کلاس [ChartSeries](../../chartseries/) به صورت نمای فقط-خواندنی داشته باشد.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* کلاس [IChartData](../)
* فضای نام [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)