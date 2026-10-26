---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية Column أو Bar (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeColumn(ChartType) و ChartTypeCharacterizer.IsChartTypeBar(ChartType)).
type: docs
weight: 196
url: /ar/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) طريقة

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد [Column](../../../aspose.slides/column/) أو الأنواع الفرعية للعمود (انظر أيضًا [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) و[ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) طريقة).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | قيمة نقطة البيانات |

### قيمة الإرجاع

نقطة البيانات الجديدة.

## IChartDataPointCollection::AddDataPointForBarSeries(double) طريقة

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد [Column](../../../aspose.slides/column/) أو الأنواع الفرعية للعمود (انظر أيضًا [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) و[ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) طريقة).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **double** | قيمة نقطة البيانات |

### قيمة الإرجاع

نقطة البيانات الجديدة.

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartDataPoint](../../ichartdatapoint/)
* فئة [IChartDataCell](../../ichartdatacell/)
* فئة [IChartDataPointCollection](../)
* فضاء الأسماء [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)