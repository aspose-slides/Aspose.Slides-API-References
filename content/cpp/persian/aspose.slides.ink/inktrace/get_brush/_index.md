---
title: get_Brush()
second_title: Aspose.Slides برای C++ مرجع API
description: Brush را برای IInkLine IInkBrush دریافت می‌کند. فقط خواندنی.
type: docs
weight: 1
url: /fa/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() متد

Brush را برای IInkLine [IInkBrush](../../iinkbrush/) دریافت می‌کند. فقط خواندنی.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IInkBrush](../../iinkbrush/)
* کلاس [InkTrace](../)
* فضای‌نام [Aspose::Slides::Ink](../../)
* کتابخانه [Aspose.Slides](../../../)