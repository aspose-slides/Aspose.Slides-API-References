---
title: get_IsPasswordProtected()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على قيمة تُشير إلى ما إذا كان العرض التقديمي المرتبط محميًا بكلمة مرور عند الفتح.
type: docs
weight: 14
url: /ar/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() طريقة

يحصل على قيمة تُشير إلى ما إذا كان العرض التقديمي المرتبط محميًا بكلمة مرور عند الفتح.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## ملاحظات

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## انظر أيضًا

* الصنف [PresentationInfo](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)