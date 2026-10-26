---
title: AddComment()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เพิ่มความคิดเห็นใหม่ที่ส่วนท้ายของคอลเลกชัน.
type: docs
weight: 53
url: /th/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) วิธีการ

เพิ่มความคิดเห็นใหม่ที่ส่วนท้ายของคอลเลกชัน.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความธรรมดาของความคิดเห็นใหม่. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ในงานนำเสนอที่ต้องการเพิ่มความคิดเห็นใหม่. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มความคิดเห็นใหม่. |
| creationTime | [System::DateTime](../../../system/datetime/) | เวลาในการสร้างความคิดเห็น. |

### ค่าที่คืนกลับ

ความคิดเห็นที่เพิ่ม.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IComment](../../icomment/)
* คลาส [String](../../../system/string/)
* คลาส [ISlide](../../islide/)
* คลาส [PointF](../../../system.drawing/pointf/)
* คลาส [DateTime](../../../system/datetime/)
* คลาส [CommentCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)