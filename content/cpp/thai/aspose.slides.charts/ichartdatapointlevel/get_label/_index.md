---
title: get_Label()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แสดงป้ายข้อมูลของระดับจุดข้อมูล. ใช้กับประเภท Treemap และ Sunburst sereis. อ่านอย่างเดียว IDataLabel.
type: docs
weight: 14
url: /th/aspose.slides.charts/ichartdatapointlevel/get_label/
---
## IChartDataPointLevel::get_Label() เมธอด


แสดงป้ายข้อมูลของระดับจุดข้อมูล. ใช้กับประเภท Treemap และ Sunburst sereis. อ่านอย่างเดียว [IDataLabel](../../idatalabel/).

```cpp
virtual System::SharedPtr<IDataLabel> Aspose::Slides::Charts::IChartDataPointLevel::get_Label()=0
```

## หมายเหตุ



```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Sunburst, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPointLevel = series->get_DataPoints()->idx_get(0)->get_DataPointLevels()->idx_get(1);

dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowCategoryName(false);
dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowValue(true);
dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowSeriesName(true);

dataPointLevel = series->get_DataPoints()->idx_get(12)->get_DataPointLevels()->idx_get(1);
dataPointLevel->get_Label()->get_TextFormat()->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
dataPointLevel->get_Label()->get_TextFormat()->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDataLabel](../../idatalabel/)
* คลาส [IChartDataPointLevel](../)
* เนมส페ซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)