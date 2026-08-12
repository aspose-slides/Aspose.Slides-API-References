---
title: get_ParentShape()
second_title: Aspose.Slides สำหรับ API อ้างอิงของ C++
description: คืนค่า shape พาเรนท์หรือ null หากอ็อบเจกต์พาเรนท์ไม่ได้ทำตามอินเทอร์เฟซ IShape ซึ่งเป็นแบบอ่านอย่างเดียว IShape.
type: docs
weight: 92
url: /th/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() เมธอด

คืนค่า รูปทรงแม่ หรือ null หากอ็อบเจกต์แม่ไม่ได้ทำตามอินเทอร์เฟซ [IShape](../../ishape/) อ่านอย่างเดียว [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## หมายเหตุ

ตัวอย่างโค้ดต่อไปนี้แสดง 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShape](../../ishape/)
* คลาส [TextFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)