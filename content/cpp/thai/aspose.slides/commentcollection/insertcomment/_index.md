---
title: InsertComment()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทรกคอมเมนต์ใหม่ลงในคอลเลกชัน ณ ดัชนีที่ระบุ.
type: docs
weight: 79
url: /th/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

แทรกคอมเมนต์ใหม่ลงในคอลเลกชัน ณ ดัชนีที่ระบุ.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### พารามิเตอร์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของรายการในคอลเลกชันที่ต้องการแทรกคอมเมนต์ |
| text | [System::String](../../../system/string/) | ข้อความธรรมดาของคอมเมนต์ใหม่ |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ในงานนำเสนอที่ต้องการเพิ่มคอมเมนต์ใหม่ |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มคอมเมนต์ใหม่ |
| creationTime | [System::DateTime](../../../system/datetime/) | เวลาที่คอมเมนต์ถูกสร้างขึ้น |

### ค่าที่ส่งกลับ

คอมเมนต์ที่ถูกแทรก

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)