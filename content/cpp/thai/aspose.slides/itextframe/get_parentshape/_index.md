---
title: get_ParentShape()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คืนค่า parent shape หรือ null หาก parent object ไม่ได้ทำตามอินเทอร์เฟซ IShape อ่านอย่างเดียว IShape.
type: docs
weight: 66
url: /th/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() เมธอด


คืนค่า parent shape หรือ null หาก parent object ไม่ได้ทำตามอินเทอร์เฟซ [IShape](../../ishape/) อ่านอย่างเดียว [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
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
* คลาส [ITextFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)