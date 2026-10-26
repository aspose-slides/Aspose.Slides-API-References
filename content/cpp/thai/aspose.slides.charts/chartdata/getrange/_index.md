---
title: GetRange()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: รับช่วงข้อมูลแผนภูมิ.
type: docs
weight: 157
url: /th/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() เมธอด

รับช่วงข้อมูลแผนภูมิ.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```

### ค่าที่ส่งกลับ

สูตรช่วงข้อมูลของเซลล์ ตัวอย่าง: \"Sheet1!$A$1:$C$4\"

## หมายเหตุ

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [ChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)