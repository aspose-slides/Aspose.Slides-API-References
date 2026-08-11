---
title: AddDataPointForMapSeries()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون نوع المخطط لها خريطة.
type: docs
weight: 417
url: /ar/aspose.slides.charts/chartdatapointcollection/adddatapointformapseries/
---
## ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) طريقة

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون نوع المخطط لها خريطة.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | قيمة اللون لنقطة البيانات ColorValue |

### قيمة الإرجاع

نقطة البيانات الجديدة.

## ملاحظات




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartDataPoint](../../ichartdatapoint/)
* فئة [IChartDataCell](../../ichartdatacell/)
* فئة [ChartDataPointCollection](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)