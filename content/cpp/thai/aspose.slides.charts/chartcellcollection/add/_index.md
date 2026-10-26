---
title: Add()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: เพิ่มเซลล์ใหม่ไปยังคอลเลกชัน.
type: docs
weight: 53
url: /th/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) เมธอด

เพิ่มเซลล์ใหม่ไปยังคอลเลกชัน.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | เซลล์ใหม่ที่จะเพิ่ม |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) เมธอด

สร้าง [ChartDataCell](../../chartdatacell/) จากค่าที่ระบุและเพิ่มลงในคอลเลกชัน.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ค่า |

## หมายเหตุ

เมธอดนี้เพิ่มเวิร์กชีตที่มีชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดลงในนั้น หากคุณใช้ [ChartDataWorkbook](../../chartdataworkbook/) เพื่อเพิ่มหรือแก้ไขค่า [Cell](../../../aspose.slides/cell/) ให้แน่ใจว่าคุณไม่ได้ใช้เวิร์กชีตนี้ จำนวนค่าสูงสุดที่สามารถเพิ่มโดยใช้เมธอดนี้ต้องไม่เกิน 16711680

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartDataCell](../../ichartdatacell/)
* คลาส [ChartCellCollection](../)
* คลาส [Object](../../../system/object/)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)