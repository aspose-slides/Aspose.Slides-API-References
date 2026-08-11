---
title: get_Traces()
second_title: مرجع API Aspose.Slides برای C++
description: تمام ردهای موجود در عنصر IInk به نام IInkTrace را دریافت می‌کند. فقط خواندنی.
type: docs
weight: 1
url: /fa/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() متد

تمام ردهای موجود در عنصر [IInk](../) [IInkTrace](../../iinktrace/) را دریافت می‌کند. فقط خواندنی.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IInkTrace](../../iinktrace/)
* کلاس [IInk](../)
* فضای نام [Aspose::Slides::Ink](../../)
* کتابخانه [Aspose.Slides](../../../)