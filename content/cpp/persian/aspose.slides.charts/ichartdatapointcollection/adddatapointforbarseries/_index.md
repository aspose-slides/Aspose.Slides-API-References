---
title: AddDataPointForBarSeries()
second_title: مرجع API Aspose.Slides برای C++
description: نقطه داده جدید را ایجاد می‌کند و در انتهای مجموعه اضافه می‌نماید. این متد برای سری‌هایی که chartType یکی از زیرنوع‌های Column یا Bar است کاربرد دارد (همچنین به متدهای ChartTypeCharacterizer.IsChartTypeColumn(ChartType) و ChartTypeCharacterizer.IsChartTypeBar(ChartType) مراجعه کنید).
type: docs
weight: 196
url: /fa/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) متد

نقطهٔ دادهٔ جدید را ایجاد می‌کند و در انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که chartType یکی از [Column](../../../aspose.slides/column/) یا زیرنوع‌های نوار است (همچنین به [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) و [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) متد مراجعه کنید).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | مقدار نقطهٔ داده |

### مقدار بازگشتی

نقطهٔ دادهٔ جدید.

## IChartDataPointCollection::AddDataPointForBarSeries(double) متد

نقطهٔ دادهٔ جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌کند. برای سری‌هایی که chartType یکی از [Column](../../../aspose.slides/column/) یا زیرنوع‌های نوار است (همچنین به [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) و [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) متد مراجعه کنید).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | **double** | مقدار نقطهٔ داده |

### مقدار بازگشتی

نقطهٔ دادهٔ جدید.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartDataPoint](../../ichartdatapoint/)
* کلاس [IChartDataCell](../../ichartdatacell/)
* کلاس [IChartDataPointCollection](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)