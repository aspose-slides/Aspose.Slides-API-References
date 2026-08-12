---
title: GetCellCollection()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: รับชุดของเซลล์.
type: docs
weight: 27
url: /th/aspose.slides.charts/ichartdataworkbook/getcellcollection/
---
## IChartDataWorkbook::GetCellCollection(System::String, bool) เมธอด

รับชุดของเซลล์.

```cpp
virtual System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::IChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) สูตรเช่น "Sheet1!$A$2:$A$5". |
| skipHiddenCells | **bool** | หากเป็น true เมธอดจะคืนค่าชุดโดยไม่มีเซลล์ที่ซ่อนอยู่. |

### ค่าที่ส่งคืน

ชุดของเซลล์ [IChartCellCollection](../../ichartcellcollection/)

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartCellCollection](../../ichartcellcollection/)
* คลาส [String](../../../system/string/)
* คลาส [IChartDataWorkbook](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)