---
title: Add()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: หากหมวดหมู่มีอยู่ในคอลเลกชัน จะส่งกลับมัน มิฉะนั้นสร้างหมวดหมู่แผนภูมิใหม่จาก IChartDataCell และเพิ่มลงในคอลเลกชัน
type: docs
weight: 92
url: /th/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) วิธีการ


หากหมวดหมู่มีอยู่ในคอลเลกชัน จะส่งกลับมัน มิฉะนั้นจะสร้างหมวดหมู่แผนภูมิใหม่จาก [IChartDataCell](../../ichartdatacell/) และเพิ่มลงในคอลเลกชัน

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) ที่ใช้เพื่อสร้างหมวดหมู่แผนภูมิ |

### ค่าที่ส่งกลับ

หมวดหมู่ที่เพิ่มหรือที่มีอยู่แล้ว



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) วิธีการ


สร้าง [ChartCategory](../../chartcategory/) ใหม่จากค่าและเพิ่มลงในคอลเลกชัน

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ค่า |

### ค่าที่ส่งกลับ

เพิ่ม [IChartCategory](../../ichartcategory/).

## หมายเหตุ



วิธีการนี้เพิ่มแผ่นงานที่มีชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดที่นั่น หากคุณใช้ [ChartDataWorkbook](../../chartdataworkbook/) เพื่อเพิ่มหรือแก้ไขค่าเซลล์ ให้แน่ใจว่าคุณไม่ได้ใช้แผ่นงานนี้ จำนวนค่าสูงสุดที่เพิ่มโดยใช้วิธีการนี้ต้องไม่เกิน 16711680



## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartCategory](../../ichartcategory/)
* คลาส [IChartDataCell](../../ichartdatacell/)
* คลาส [ChartCategoryCollection](../)
* คลาส [Object](../../../system/object/)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)