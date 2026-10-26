---
title: AddDataPointForMapSeries()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: สร้างจุดข้อมูลใหม่และเพิ่มลงไปที่ส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ประเภทแผนภูมิเป็นแผนที่
type: docs
weight: 352
url: /th/aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries/
---
## IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) method

สร้างจุดข้อมูลใหม่และเพิ่มลงไปที่ส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ประเภทแผนภูมิเป็นแผนที่

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | จุดข้อมูล ColorValue |

### ค่าที่ส่งกลับ

จุดข้อมูลใหม่.

## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## ดูเพิ่มเติม

* กำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartDataPoint](../../ichartdatapoint/)
* คลาส [IChartDataCell](../../ichartdatacell/)
* คลาส [IChartDataPointCollection](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)