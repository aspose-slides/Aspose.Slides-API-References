---
title: get_IsPasswordProtected()
second_title: مرجع API Aspose.Slides برای C++
description: نشان می‌دهد که آیا VBAProject توسط رمز عبور برای مشاهده ویژگی‌های پروژه محافظت شده است یا نه. فقط‌خواندنی bool.
type: docs
weight: 40
url: /fa/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() متد


نشان می‌دهد که آیا VBAProject توسط رمز عبور برای مشاهده ویژگی‌های پروژه محافظت شده است یا خیر. فقط‌خواندنی **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## موارد مرتبط

* کلاس [IVbaProject](../)
* فضای‌نام [Aspose::Slides::Vba](../../)
* کتابخانه [Aspose.Slides](../../../)