---
title: AddComment()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มคอมเมนต์ใหม่ที่ส่วนท้ายของคอลเลกชัน.
type: docs
weight: 14
url: /th/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method


เพิ่มคอมเมนต์ใหม่ที่ส่วนท้ายของคอลเลกชัน.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความธรรมดาของคอมเมนต์ใหม่. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ในพรีเซนเทชั่นที่ต้องการเพิ่มคอมเมนต์ใหม่. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มคอมเมนต์ใหม่. |
| creationTime | [System::DateTime](../../../system/datetime/) | เวลาในการสร้างคอมเมนต์. |

### Return Value

คอมเมนต์ที่เพิ่ม.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [DateTime](../../../system/datetime/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)