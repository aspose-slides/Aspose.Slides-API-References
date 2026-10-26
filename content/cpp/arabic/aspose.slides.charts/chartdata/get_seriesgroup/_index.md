---
title: get_SeriesGroup()
second_title: Aspose.Slides لـ C++ مرجع API
description: 
type: docs
weight: 222
url: /ar/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) طريقة

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) طريقة

يرجع مجموعة السلاسل عند الفهرس المحدد.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## ملاحظات

1) يحتوي كل مجموعة سلاسل على سلاسل ذات أنواع قابلة للجمع. تم تعريف مجموعات الأنواع القابلة للجمع ووصفها بواسطة تعداد CombinableSeriesTypesGroup. كما يحتوي كل مجموعة سلاسل على سلاسل تُرسم إما على المحاور الأساسية أو على المحاور الثانوية (ليس كلا الحالتين في مجموعة واحدة). لذا، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه وحسب نوع الرسم الأساسي/الثانوي. 2) تحتوي مجموعة السلاسل على بعض خصائص السلسلة المشتركة لكل سلسلة في المجموعة ("series group properties"). "Series group properties" في الفئة [ChartSeriesGroup](../../chartseriesgroup/) هو read/write. كل من "series group properties" يمكن أن يكون له إسقاط read-only في الفئة [ChartSeries](../../chartseries/).

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IChartSeriesGroup](../../ichartseriesgroup/)
* الفئة [IChartSeries](../../ichartseries/)
* الفئة [ChartData](../)
* النطاق [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)