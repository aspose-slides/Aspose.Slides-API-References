---
title: AddDataPointForMapSeries()
second_title: Aspose.Slides لمرجع API للغة C++
description: يُنشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون نوع المخطط لها هو الخريطة.
type: docs
weight: 352
url: /ar/aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries/
---
## IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) طريقة

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلسلات التي يكون نوع المخطط لها هو الخريطة.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | قيمة ColorValue لنقطة البيانات |

### Return Value

قيمة الإرجاع

نقطة البيانات الجديدة.

## Remarks

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## See Also

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartDataPoint](../../ichartdatapoint/)
* فئة [IChartDataCell](../../ichartdatacell/)
* فئة [IChartDataPointCollection](../)
* مساحة اسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)