---
title: Add()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มเซลล์ใหม่เข้าสู่คอลเลกชัน.
type: docs
weight: 53
url: /th/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) เมธอด


เพิ่มเซลล์ใหม่เข้าในคอลเลกชัน

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | เซลล์ใหม่ที่จะเพิ่ม |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) เมธอด


สร้าง [IChartDataCell](../../ichartdatacell/) จากค่าที่ระบุและเพิ่มลงในคอลเลกชัน

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ค่า |

## หมายเหตุ



เมธอดนี้เพิ่มเวิร์กชีตที่มีชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดลงในนั้น หากคุณใช้ [IChartDataWorkbook](../../ichartdataworkbook/) เพื่อเพิ่มหรือแก้ไขค่า [Cell](../../../aspose.slides/cell/) ให้แน่ใจว่าคุณไม่ได้ใช้เวิร์กชีตนี้ จำนวนค่าสูงสุดที่เพิ่มโดยใช้เมธอดนี้ต้องไม่เกิน 16711680



## ดูเพิ่มเติม

* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartDataCell](../../ichartdatacell/)
* คลาส [IChartCellCollection](../)
* คลาส [Object](../../../system/object/)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)