---
title: get_LinkPathRelative()
second_title: Aspose.Slides برای C++ مرجع API
description: "مسیر نسبی به فایل پیوست‌شده را در صورت وجود باز می‌گرداند، در غیر این صورت رشتهٔ خالی را باز می‌گرداند. فقط‌خواندنی System::String."
type: docs
weight: 118
url: /fa/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() متد


مسیر نسبی به فایل پیوست‌شده را در صورت وجود باز می‌گرداند، در غیر این صورت رشتهٔ خالی را باز می‌گرداند. فقط‌خواندنی [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## توضیحات


در ارائه‌های Ppt، برخی از لینک‌های شیء Ole ممکن است نمایش نسبی داشته باشند. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## مراجعه کنید

* کلاس [String](../../../system/string/)
* کلاس [IOleObjectFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)