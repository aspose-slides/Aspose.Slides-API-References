---
title: get_SeriesGroup()
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 222
url: /fa/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) متد




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) متد


گروه سری‌ها را در اندیس مشخص شده باز می‌گرداند.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## توضیحات


1) هر گروه سری شامل سری‌هایی با انواع ترکیبی است. گروه‌های انواع سری‌های ترکیبی با enum CombinableSeriesTypesGroup تعریف و توصیف می‌شوند. همچنین هر گروه سری شامل سری‌هایی است که بر روی محورهای اصلی یا محورهای ثانویه رسم می‌شوند (نه هر دو حالت در یک گروه). بنابراین، اصول گروه‌بندی سری‌ها بر پایه گروه‌بندی بر پایه انواع فوق و نوع ترسیم اصلی/ثانویه است. 2) گروه سری شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است (\"ویژگی‌های گروه سری\"). \"ویژگی‌های گروه سری\" در [ChartSeriesGroup](../../chartseriesgroup/) class خواندنی/نوشتنی است. هر یک از \"ویژگی‌های گروه سری\" می‌تواند یک تصویر فقط-خواندنی در [ChartSeries](../../chartseries/) class داشته باشد. 
## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartSeriesGroup](../../ichartseriesgroup/)
* کلاس [IChartSeries](../../ichartseries/)
* کلاس [ChartData](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)