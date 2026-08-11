---
title: get_IsPasswordProtected()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يشير إلى ما إذا كان VBAProject محمياً بكلمة مرور لعرض خصائص المشروع. للقراءة فقط bool.
type: docs
weight: 40
url: /ar/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() طريقة

يشير إلى ما إذا كان VBAProject محمياً بكلمة مرور لعرض خصائص المشروع. للقراءة فقط **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## أنظر أيضًا

* الفئة [IVbaProject](../)
* مساحة الاسم [Aspose::Slides::Vba](../../)
* المكتبة [Aspose.Slides](../../../)