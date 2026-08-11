---
title: get_IsPasswordProtected()
second_title: مرجع API Aspose.Slides برای C++ 
description: نشان می‌دهد که آیا VBAProject با رمز عبور برای مشاهده ویژگی‌های پروژه محافظت شده است یا خیر. فقط‌خواندنی bool.
type: docs
weight: 40
url: /fa/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() متد


مشخص می‌کند که آیا VBAProject با یک رمز عبور برای مشاهده ویژگی‌های پروژه محافظت شده است یا خیر. فقط-خواندنی **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## مراجع

* کلاس [VbaProject](../)
* فضای نام [Aspose::Slides::Vba](../../)
* کتابخانه [Aspose.Slides](../../../)