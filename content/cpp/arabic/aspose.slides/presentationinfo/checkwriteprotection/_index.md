---
title: CheckWriteProtection()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة لعرض محمي من الكتابة.
type: docs
weight: 66
url: /ar/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) طريقة

يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة لعرض محمي من الكتابة.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | كلمة المرور للتحقق منها. |

### قيمة الإرجاع

صحيح إذا كان العرض محمياً من الكتابة وكانت كلمة المرور صحيحة. غير ذلك خطأ.

## ملاحظات

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. يجب عليك التحقق من خاصية [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) قبل استدعاء هذه الطريقة.
1. عندما تكون كلمة المرور null أو فارغة، تُرجع هذه الطريقة false.

## انظر أيضاً

* فئة [String](../../../system/string/)
* فئة [PresentationInfo](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)