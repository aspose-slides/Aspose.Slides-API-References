---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: แสดงรูปแบบเส้นนำของป้ายข้อมูล. อ่านอย่างเดียว IChartLinesFormat.
type: docs
weight: 66
url: /th/aspose.slides.charts/datalabelcollection/get_leaderlinesformat/
---
## DataLabelCollection::get_LeaderLinesFormat() เมธอด

แสดงรูปแบบเส้นนำของป้ายข้อมูล. อ่านอย่างเดียว [IChartLinesFormat](../../ichartlinesformat/).

```cpp
System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::DataLabelCollection::get_LeaderLinesFormat() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartLinesFormat](../../ichartlinesformat/)
* คลาส [DataLabelCollection](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)