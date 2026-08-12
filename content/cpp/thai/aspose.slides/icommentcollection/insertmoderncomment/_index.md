---
title: InsertModernComment()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แทรกคอมเมนต์สมัยใหม่ใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ
type: docs
weight: 53
url: /th/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) เมธอด

แทรกคอมเมนต์สมัยใหม่ใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีขององค์ประกอบในคอลเลกชันที่คอมเมนต์สมัยใหม่จะถูกแทรก |
| text | [System::String](../../../system/string/) | ข้อความธรรมดาของคอมเมนต์สมัยใหม่ใหม่ |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ในงานนำเสนอที่ต้องการเพิ่มคอมเมนต์สมัยใหม่ใหม่ |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) บนสไลด์ที่คอมเมนต์สมัยใหม่ใหม่เชื่อมโยง |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มคอมเมนต์สมัยใหม่ใหม่ |
| creationTime | [System::DateTime](../../../system/datetime/) | เวลาในการสร้างคอมเมนต์สมัยใหม่ |

### ค่าที่ส่งกลับ

คอมเมนต์สมัยใหม่ที่แทรกแล้ว

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IModernComment](../../imoderncomment/)
* คลาส [String](../../../system/string/)
* คลาส [ISlide](../../islide/)
* คลาส [IShape](../../ishape/)
* คลาส [PointF](../../../system.drawing/pointf/)
* คลาส [DateTime](../../../system/datetime/)
* คลาส [ICommentCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)