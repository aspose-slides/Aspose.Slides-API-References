---
title: set_Formula()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดสูตรในรูปแบบ A1.
type: docs
weight: 66
url: /th/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) เมธอด


กำหนดสูตรในรูปแบบ A1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## หมายเหตุ



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IChartDataCell](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)