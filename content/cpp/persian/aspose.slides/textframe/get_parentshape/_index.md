---
title: get_ParentShape()
second_title: مرجع API Aspose.Slides برای C++
description: شکل والد را بازمی‌گرداند یا null اگر شیء والد رابط IShape را پیاده‌سازی نکند فقط-خواندنی IShape.
type: docs
weight: 92
url: /fa/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() متد

شیپ والد را بازمی‌گرداند یا null اگر شیء والد رابط [IShape](../../ishape/) را پیاده‌سازی نکند فقط-خواندنی [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## توضیحات

نمونه کد زیر را نشان می‌دهد 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IShape](../../ishape/)
* کلاس [TextFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)