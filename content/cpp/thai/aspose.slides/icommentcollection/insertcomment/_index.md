---
title: InsertComment()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แทรกความคิดเห็นใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ
type: docs
weight: 40
url: /th/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

แทรกความคิดเห็นใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีขององค์ประกอบในคอลเลกชันที่ควรแทรกความคิดเห็น |
| text | [System::String](../../../system/string/) | ข้อความธรรมดาของความคิดเห็นใหม่ |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ในการนำเสนอที่ต้องการเพิ่มความคิดเห็นใหม่ |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มความคิดเห็นใหม่ |
| creationTime | [System::DateTime](../../../system/datetime/) | เวลาที่สร้างความคิดเห็น |

### ค่าที่ส่งกลับ

ความคิดเห็นที่แทรก

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IComment](../../icomment/)
* คลาส [String](../../../system/string/)
* คลาส [ISlide](../../islide/)
* คลาส [PointF](../../../system.drawing/pointf/)
* คลาส [DateTime](../../../system/datetime/)
* คลาส [ICommentCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)