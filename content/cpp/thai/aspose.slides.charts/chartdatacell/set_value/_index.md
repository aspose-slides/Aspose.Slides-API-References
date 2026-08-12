---
title: set_Value()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "กำหนดค่าของเซลล์. เขียน System::Object."
type: docs
weight: 40
url: /th/aspose.slides.charts/chartdatacell/set_value/
---
## ChartDataCell::set_Value(System::SharedPtr\<System::Object\>) เมธอด

กำหนดค่าของเซลล์. เขียน [System::Object](../../../system/object/).

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Value(System::SharedPtr<System::Object> value) override
```

## หมายเหตุ

```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [ChartDataCell](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)