---
title: get_SeriesGroups()
second_title: مرجع API Aspose.Slides للغة C++
description: يحصل على مجموعات السلاسل. للقراءة فقط IChartSeriesGroupCollection.
type: docs
weight: 27
url: /ar/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() طريقة

يحصل على مجموعات السلاسل. للقراءة فقط [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## ملاحظات

1) كل مجموعة من السلاسل تحتوي على سلاسل بأنواع قابلة للجمع. يتم تعريف مجموعات الأنواع القابلة للجمع للسلاسل وتوضيحها باستخدام تعداد CombinableSeriesTypesGroup enum. كما أن كل مجموعة من السلاسل تحتوي على سلاسل تُرسم إما على المحاور الأساسية أو على المحاور الثانوية (ليس كلا الحالتين في مجموعة واحدة). وبالتالي، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه وحسب نوع الرسم الأساسي/الثانوي.

2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي تكون مشتركة لكل سلسلة في المجموعة (\"series group properties\"). \"Series group properties\" في الفئة [ChartSeriesGroup](../../chartseriesgroup/) قابلة للقراءة والكتابة. يمكن لكل من \"series group properties\" أن يكون له تجسيد للقراءة فقط في الفئة [ChartSeries](../../chartseries/).

## راجع أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* الفئة [IChartData](../)
* مجال [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)