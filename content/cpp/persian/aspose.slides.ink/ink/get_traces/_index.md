---
title: get_Traces()
second_title: مرجع API Aspose.Slides برای C++
description: تمام ردپاهای موجود در عنصر IInk IInkTrace را به‌دست می‌آورد. فقط-خواندنی.
type: docs
weight: 1
url: /fa/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() متد


تمام ردپاهای موجود در عنصر [IInk](../../iink/) [IInkTrace](../../iinktrace/) را به‌دست می‌آورد. فقط-خواندنی.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## همچنین ببینید

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IInkTrace](../../iinktrace/)
* کلاس [Ink](../)
* فضای‌نام [Aspose::Slides::Ink](../../)
* کتابخانه [Aspose.Slides](../../../)