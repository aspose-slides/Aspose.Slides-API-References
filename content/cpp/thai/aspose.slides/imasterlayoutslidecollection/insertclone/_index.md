---
title: InsertClone()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทรกสำเนาของสไลด์เค้าโครงที่ระบุลงในตำแหน่งที่กำหนดของคอลเลกชัน.
type: docs
weight: 14
url: /th/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) เมธอด

แทรกสำเนาของสไลด์เค้าโครงที่ระบุลงในตำแหน่งที่กำหนดของคอลเลกชัน.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | Index ของสไลด์ใหม่. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) เพื่อโคลน. |

### ค่าที่ส่งกลับ

สไลด์ที่แทรก.

## หมายเหตุ

เค้าโครงใหม่จะถูกเชื่อมโยงกับสไลด์มาสเตอร์ของพาเรนต์สำหรับคอลเลกชันสไลด์เค้าโครงนี้ ดังนั้นจึงเป็นการทำงานคล้ายกับการคัดลอก/วางโดยใช้ตัวเลือก "Use Destination Theme" ใน PowerPoint. 

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [IMasterLayoutSlideCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)