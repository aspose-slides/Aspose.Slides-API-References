---
title: InsertModernComment()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกคอมเมนต์สมัยใหม่ใหม่ลงในคอลเลกชันที่ดัชนีที่ระบุ.
type: docs
weight: 92
url: /th/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) เมธอด

แทรกคอมเมนต์สมัยใหม่ใหม่ลงในคอลเลกชันที่ดัชนีที่ระบุ.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีขององค์ประกอบในคอลเลกชันที่ควรแทรกคอมเมนต์สมัยใหม่ |
| text | [System::String](../../../system/string/) | ข้อความทั่วไปของคอมเมนต์สมัยใหม่ใหม่ |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ในงานนำเสนอที่ต้องการเพิ่มคอมเมนต์สมัยใหม่ใหม่ |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) บนสไลด์ที่คอมเมนต์สมัยใหม่ใหม่เชื่อมโยง |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มคอมเมนต์สมัยใหม่ใหม่ |
| creationTime | [System::DateTime](../../../system/datetime/) | เวลาที่คอมเมนต์สมัยใหม่ถูกสร้าง |

### ค่าที่ส่งกลับ

คอมเมนต์สมัยใหม่ที่ถูกแทรก

## ดูเพิ่มเติม

* การนิยามประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IModernComment](../../imoderncomment/)
* คลาส [String](../../../system/string/)
* คลาส [ISlide](../../islide/)
* คลาส [IShape](../../ishape/)
* คลาส [PointF](../../../system.drawing/pointf/)
* คลาส [DateTime](../../../system/datetime/)
* คลาส [CommentCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)