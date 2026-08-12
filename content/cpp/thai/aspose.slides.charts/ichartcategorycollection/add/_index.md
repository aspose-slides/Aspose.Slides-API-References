---
title: Add()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: หากหมวดหมู่มีอยู่ในคอลเลกชัน จะคืนค่ามัน หากไม่มีก็สร้างหมวดหมู่แผนภูมิใหม่จาก IChartDataCell แล้วเพิ่มลงในคอลเลกชัน.
type: docs
weight: 53
url: /th/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) เมธอด

หากหมวดหมู่มีอยู่ในคอลเลกชันแล้วจะคืนค่ามัน. หากไม่มีจะสร้างหมวดหมู่แผนภูมิใหม่จาก [IChartDataCell](../../ichartdatacell/) และเพิ่มลงในคอลเลกชัน.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) ใช้เพื่อสร้างหมวดหมู่แผนภูมิ. |

### ค่าที่ส่งคืน

เพิ่มหรือใช้หมวดหมู่ที่มีอยู่.

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) เมธอด

สร้าง [IChartCategory](../../ichartcategory/) ใหม่จากค่าและเพิ่มลงในคอลเลกชัน.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ค่า. |

### ค่าที่ส่งคืน

เพิ่ม [IChartCategory](../../ichartcategory/).

## หมายเหตุ

วิธีนี้เพิ่มแผ่นงานที่มีชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดที่นั่น. หากคุณใช้ [IChartDataWorkbook](../../ichartdataworkbook/) เพื่อเพิ่มหรือแก้ไขค่าของเซลล์, ควรแน่ใจว่าคุณไม่ได้ใช้แผ่นงานนี้ จำนวนค่าที่เพิ่มโดยใช้วิธีนี้ต้องไม่เกิน 16711680

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)