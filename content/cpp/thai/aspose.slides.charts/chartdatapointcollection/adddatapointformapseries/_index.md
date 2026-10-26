---
title: AddDataPointForMapSeries()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลคชัน ใช้ได้กับซีรีส์ที่ประเภทแผนภูมิเป็น Map.
type: docs
weight: 417
url: /th/aspose.slides.charts/chartdatapointcollection/adddatapointformapseries/
---
## ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) เมธอด

สร้างจุดข้อมูลใหม่และเพิ่มมันไปยังส่วนท้ายของคอลเลคชัน ใช้ได้กับซีรีส์ที่ประเภทแผนภูมิเป็น Map.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | ColorValue ของจุดข้อมูล |

### Return Value

จุดข้อมูลใหม่.

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

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartDataPoint](../../ichartdatapoint/)
* คลาส [IChartDataCell](../../ichartdatacell/)
* คลาส [ChartDataPointCollection](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)