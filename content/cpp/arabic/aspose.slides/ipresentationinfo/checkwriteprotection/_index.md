---
title: CheckWriteProtection()
second_title: Aspose.Slides لـ C++ مرجع API
description: يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة لعرض محمي من الكتابة.
type: docs
weight: 66
url: /ar/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) طريقة

يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة لعرض محمي من الكتابة.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | كلمة المرور للتحقق منها. |

### قيمة الإرجاع

True إذا كان العرض محميًا من الكتابة وكانت كلمة المرور صحيحة. False بخلاف ذلك.

## ملاحظات

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. يجب عليك التحقق من الخاصية [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) قبل استدعاء هذه الطريقة.
1. عندما تكون كلمة المرور فارغة أو null، تُرجع هذه الطريقة False.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [IPresentationInfo](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)