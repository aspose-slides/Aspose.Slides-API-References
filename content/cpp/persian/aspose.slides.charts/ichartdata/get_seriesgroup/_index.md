---
title: get_SeriesGroup()
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 222
url: /fa/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) متد


```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) متد

Returns the group of series at the specified index.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## توضیحات

1) هر گروهی از سری‌ها شامل سری‌هایی با انواع ترکیبی است. گروه‌های انواع ترکیبی سری‌ها با استفاده از enum CombinableSeriesTypesGroup تعریف و توصیف می‌شوند. همچنین هر گروهی از سری‌ها شامل سری‌هایی است که یا بر روی محورهاى اولیه یا بر روی محورهاى ثانویه (نه هر دو حالت در یک گروه) ترسیم می‌شوند. بنابراین، اصل گروه‌بندی سری‌ها، گروه‌بندی بر اساس گروه‌های نوع ذکر شده در بالا و بر اساس نوع ترسیم اولیه/ثانویه است. 2) Group of series contains some series properies whitch is common for each series in group (\"ویژگی‌های گروه سری\"). \"ویژگی‌های گروه سری\" در کلاس [ChartSeriesGroup](../../chartseriesgroup/) قابلیت خواند و نوشتن دارد. هر یک از \"ویژگی‌های گروه سری\" می‌توانند یک پیش‌نمایش فقط-خواندنی در کلاس [ChartSeries](../../chartseries/) داشته باشند.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartSeriesGroup](../../ichartseriesgroup/)
* کلاس [IChartSeries](../../ichartseries/)
* کلاس [IChartData](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)