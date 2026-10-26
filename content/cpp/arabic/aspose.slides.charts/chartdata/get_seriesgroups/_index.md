---
title: get_SeriesGroups()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على مجموعات السلاسل. للقراءة فقط IChartSeriesGroupCollection.
type: docs
weight: 27
url: /ar/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() طريقة

يحصل على مجموعات السلاسل. للقراءة فقط [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## ملاحظات

1) كل مجموعة من السلاسل تحتوي على سلاسل بأنواع يمكن دمجها. يتم تعريف مجموعات الأنواع القابلة للدمج ووصفها باستخدام التعداد CombinableSeriesTypesGroup. كذلك كل مجموعة من السلاسل تحتوي على سلسلة تُرسم إما على المحاور الأولية أو على المحاور الثانوية (ليس كلا الحالتين في مجموعة واحدة). لذلك، مبدأ تجميع السلاسل هو التجميع حسب مجموعات الأنواع المذكورة أعلاه وحسب نوع الرسم الأساسي/الثانوي.

2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي تكون مشتركة لكل سلسلة في المجموعة ("series group properties"). "Series group properties" في الفئة [ChartSeriesGroup](../../chartseriesgroup/) هي قراءة/كتابة. كل واحدة من "series group properties" يمكن أن يكون لها توقع للقراءة فقط في الفئة [ChartSeries](../../chartseries/).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* فئة [ChartData](../)
* مجال الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)