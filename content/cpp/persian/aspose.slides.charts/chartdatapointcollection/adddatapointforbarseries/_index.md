---
title: AddDataPointForBarSeries()
second_title: مرجع API Aspose.Slides برای C++
description: "نقطه داده جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی قابل استفاده است که chartType یکی از Column یا Bar زیرنوع‌ها باشد (همچنین به متد ChartTypeCharacterizer::IsChartTypeColumn(ChartType) و ChartTypeCharacterizer::IsChartTypeBar(ChartType) مراجعه کنید)."
type: docs
weight: 261
url: /fa/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) متد

ایجاد نقطه داده جدید و افزودن آن به انتهای مجموعه. برای سری‌هایی که chartType یکی از [Column](../../../aspose.slides/column/) یا زیرنوع Bar است قابل استفاده است (همچنین به [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) و [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) مراجعه کنید).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```

### Arguments

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | مقدار نقطه داده |

### مقدار برگشت

نقطه داده جدید.

## ChartDataPointCollection::AddDataPointForBarSeries(double) متد

ایجاد نقطه داده جدید و افزودن آن به انتهای مجموعه. برای سری‌هایی که chartType یکی از [Column](../../../aspose.slides/column/) یا زیرنوع Bar است قابل استفاده است (همچنین به [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) و [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) مراجعه کنید).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```

### Arguments

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | **double** | مقدار نقطه داده |

### مقدار برگشت

نقطه داده جدید.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartDataPoint](../../ichartdatapoint/)
* کلاس [IChartDataCell](../../ichartdatacell/)
* کلاس [ChartDataPointCollection](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)