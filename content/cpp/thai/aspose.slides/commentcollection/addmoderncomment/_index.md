---
title: AddModernComment()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มคอมเมนต์สมัยใหม่ใหม่ที่ส่วนท้ายของคอลเลกชัน
type: docs
weight: 66
url: /th/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) เมธอด


เพิ่มคอมเมนต์สมัยใหม่ใหม่ที่ส่วนท้ายของคอลเลกชัน

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความธรรมดาของคอมเมนต์สมัยใหม่ใหม่ |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ในงานพรีเซนเทชันที่ต้องการเพิ่มคอมเมนต์สมัยใหม่ใหม่ |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) บนสไลด์ที่คอมเมนต์สมัยใหม่ใหม่เชื่อมโยง |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | ตำแหน่งบนสไลด์ที่ต้องการเพิ่มคอมเมนต์สมัยใหม่ใหม่ |
| creationTime | [System::DateTime](../../../system/datetime/) | เวลาที่สร้างคอมเมนต์สมัยใหม่ |

### ค่ารีเทิร์น

คอมเมนต์สมัยใหม่ที่เพิ่ม

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
* คลาส [CommentCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)