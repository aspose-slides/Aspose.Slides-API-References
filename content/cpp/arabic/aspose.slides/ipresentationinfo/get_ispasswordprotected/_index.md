---
title: get_IsPasswordProtected()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحصل على قيمة تشير إلى ما إذا كان العرض التقديمي المرتبط محميًا بكلمة مرور للفتح.
type: docs
weight: 14
url: /ar/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() طريقة

يحصل على قيمة تشير إلى ما إذا كان عرض تقديمي مرتبط محميًا بكلمة مرور للفتح.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## ملاحظات



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## انظر أيضًا

* فئة [IPresentationInfo](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)