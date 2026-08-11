---
title: get_LinkPathRelative()
second_title: Aspose.Slides برای C++ API Reference
description: "مسیر نسبی به فایلی که لینک شده است را برمی‌گرداند، اگر موجود باشد، در غیر این صورت یک رشته خالی را برمی‌گرداند. Readonly System::String."
type: docs
weight: 131
url: /fa/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() متد


مسیر نسبی به فایلی که لینک شده است را برمی‌گرداند، اگر موجود باشد، در غیر این صورت یک رشتهٔ خالی را برمی‌گرداند. فقط‌خواندنی [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## توضیحات


در ارائه‌های Ppt، ممکن است برخی از پیوندهای شیء Ole نمایش نسبی داشته باشند. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [OleObjectFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)