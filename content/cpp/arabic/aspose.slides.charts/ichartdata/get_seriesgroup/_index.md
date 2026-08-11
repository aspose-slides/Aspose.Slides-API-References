---
title: get_SeriesGroup()
second_title: Aspose.Slides للـ C++ مرجع API
description: 
type: docs
weight: 222
url: /ar/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) طريقة

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) طريقة

يُعيد مجموعة السلاسل عند الفهرس المحدد.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## ملاحظات

1) كل مجموعة من السلاسل تحتوي على سلاسل بأنواع يمكن دمجها. يتم تعريف مجموعات الأنواع القابلة للدمج وتوضيحها باستخدام عدد ‎CombinableSeriesTypesGroup‎. كما أن كل مجموعة من السلاسل تحتوي على سلاسل تُرسم إما على المحاور الأولية أو على المحاور الثانوية (ليس كلا الحالتين في مجموعة واحدة). لذا، مبدأ تجميع السلاسل هو التجميع بحسب مجموعات الأنواع المذكورة أعلاه وأيضًا بحسب نوع الرسم الأساسي/الثانوي. 2) مجموعة السلاسل تحتوي على بعض خصائص السلاسل التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلاسل"). "خصائص مجموعة السلاسل" في فئة [ChartSeriesGroup](../../chartseriesgroup/) هي قراءة/كتابة. كل واحدة من "خصائص مجموعة السلاسل" يمكن أن يكون لها عرض قراءة-فقط في فئة [ChartSeries](../../chartseries/). 

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartSeriesGroup](../../ichartseriesgroup/)
* فئة [IChartSeries](../../ichartseries/)
* فئة [IChartData](../)
* مساحة أسماء [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)