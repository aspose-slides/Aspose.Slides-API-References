---
title: InsertClone()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกสำเนาของสไลด์เลเอาท์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเล็กชัน
type: docs
weight: 14
url: /th/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) เมธอด


แทรกสำเนาของสไลด์เลเอาท์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเล็กชัน

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### อากูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของสไลด์ใหม่ |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) ที่จะทำสำเนา |

### ค่าที่ส่งคืน

สไลด์ที่แทรก

## หมายเหตุ

เลเอาท์ใหม่จะถูกเชื่อมโยงกับสไลด์แม่ของพาเรนต์สำหรับคอลเล็กชันสไลด์เลเอาท์นี้ ดังนั้นนี่จึงเป็นการทำงานคล้ายกับการคัดลอก/วางโดยใช้ตัวเลือก "ใช้ธีมปลายทาง" ใน PowerPoint

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [MasterLayoutSlideCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)