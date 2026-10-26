---
title: get_IsWriteProtected()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على قيمة تشير إلى ما إذا كان العرض التقديمي المرتبط محميًا ضد الكتابة.
type: docs
weight: 27
url: /ar/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() طريقة


يُرجع قيمة تُشير إلى ما إذا كان العرض التقديمي المرتبط محميًا ضد الكتابة.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## ملاحظات



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


إذا كان العرض التقديمي محميًا بكلمة مرور للفتح، فإن قيمة الخاصية تساوي NotDefined. 
## انظر أيضًا

* تعداد [NullableBool](../../nullablebool/)
* فئة [PresentationInfo](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)