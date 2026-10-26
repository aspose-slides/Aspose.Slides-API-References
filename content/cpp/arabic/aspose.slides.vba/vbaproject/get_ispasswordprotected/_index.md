---
title: get_IsPasswordProtected()
second_title: مرجع API Aspose.Slides للغة C++
description: يشير إلى ما إذا كان VBAProject محميًا بكلمة مرور لعرض خصائص المشروع. قراءة فقط bool.
type: docs
weight: 40
url: /ar/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() طريقة

يشير إلى ما إذا كان VBAProject محميًا بكلمة مرور لعرض خصائص المشروع. قراءة فقط **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## انظر أيضًا

* الفئة [VbaProject](../)
* النطاق [Aspose::Slides::Vba](../../)
* المكتبة [Aspose.Slides](../../../)