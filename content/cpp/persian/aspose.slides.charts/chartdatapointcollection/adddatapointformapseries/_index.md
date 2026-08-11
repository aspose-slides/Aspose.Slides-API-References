---
title: AddDataPointForMapSeries()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که نوع نمودارشان Map است قابل استفاده است.
type: docs
weight: 417
url: /fa/aspose.slides.charts/chartdatapointcollection/adddatapointformapseries/
---
## ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) متد


یک نقطه داده جدید ایجاد می‌کند و آن را به انتهای مجموعه اضافه می‌نماید. برای سری‌هایی که نوع نمودارشان Map است قابل استفاده است.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | نقطه داده ColorValue |

### مقدار بازگشت

نقطه داده جدید.
## توضیحات




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartDataPoint](../../ichartdatapoint/)
* کلاس [IChartDataCell](../../ichartdatacell/)
* کلاس [ChartDataPointCollection](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)