---
title: get_Brush()
second_title: مرجع API Aspose.Slides برای C++
description: قلم Brush را برای IInkLine IInkBrush به صورت فقط-خواندنی دریافت می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() متد

قلم را برای IInkLine [IInkBrush](../../iinkbrush/) دریافت می‌کند. فقط-خواندنی.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IInkBrush](../../iinkbrush/)
* کلاس [IInkTrace](../)
* فضای نام [Aspose::Slides::Ink](../../)
* کتابخانه [Aspose.Slides](../../../)