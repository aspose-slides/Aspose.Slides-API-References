---
title: get_ParentShape()
second_title: مرجع API Aspose.Slides برای C++
description: شکل والد را برمی‌گرداند یا null اگر شیء والد رابط IShape را پیاده‌سازی نکند فقط-خواندنی IShape.
type: docs
weight: 66
url: /fa/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() متد


شکل والد را برمی‌گرداند یا null اگر شیء والد رابط [IShape](../../ishape/) را پیاده‌سازی نکند فقط‌خواندنی [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## ملاحظات


نمونه کد زیر نشان می‌دهد 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IShape](../../ishape/)
* کلاس [ITextFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)