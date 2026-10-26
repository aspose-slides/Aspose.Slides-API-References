---
title: get_ParentShape()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يرجع الشكل الأب أو null إذا كان كائن الأب لا ينفذ واجهة IShape للقراءة فقط IShape.
type: docs
weight: 66
url: /ar/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() طريقة


يرجع الشكل الأب أو null إذا كان كائن الأب لا ينفذ الواجهة [IShape](../../ishape/) للقراءة فقط [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## ملاحظات


العينة البرمجية التالية تظهر 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IShape](../../ishape/)
* فئة [ITextFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)