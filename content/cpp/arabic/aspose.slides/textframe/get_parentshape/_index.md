---
title: get_ParentShape()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع الشكل الأصل أو null إذا لم يكن كائن الأصل يطبق واجهة IShape للقراءة فقط IShape.
type: docs
weight: 92
url: /ar/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() طريقة

يرجع الشكل الأصل أو null إذا كان كائن الأصل لا ينفذ واجهة [IShape](../../ishape/) للقراءة فقط [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## ملاحظات

العينة البرمجية التالية توضح
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IShape](../../ishape/)
* فئة [TextFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)