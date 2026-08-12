---
title: AddModernComment()
second_title: เอกสารอ้างอิง API Aspose.Slides สำหรับ C++
description: เพิ่มคอมเมนต์สมัยใหม่ใหม่ที่ส่วนท้ายของคอลเลกชัน
type: docs
weight: 27
url: /th/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) เมธอด

เพิ่มคอมเมนท์สมัยใหม่ใหม่ที่ส่วนท้ายของคอลเลกชัน

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความธรรมดาของความคิดเห็นสมัยใหม่ใหม่ |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ในงานนำเสนอที่ต้องการเพิ่มความคิดเห็นสมัยใหม่ใหม่ |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) บนสไลด์ที่เชื่อมโยงกับความคิดเห็นสมัยใหม่ใหม่ |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มความคิดเห็นสมัยใหม่ใหม่ |
| creationTime | [System::DateTime](../../../system/datetime/) | เวลาที่สร้างความคิดเห็นสมัยใหม่ |

### ค่าที่ส่งกลับ

ความคิดเห็นสมัยใหม่ที่เพิ่มแล้ว

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

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