---
title: CheckWriteProtection()
second_title: مرجع API Aspose.Slides للـ C++
description: يحدد ما إذا كان العرض التقديمي محميًا بكلمة مرور لتعديل.
type: docs
weight: 157
url: /ar/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) طريقة

يحدد ما إذا كان عرض تقديمي محميًا بكلمة مرور للتعديل.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | كلمة المرور للتحقق. |

### قيمة الإرجاع

True إذا كانت كلمة المرور صالحة؛ وإلا، false.

## ملاحظات

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. يجب عليك التحقق من خاصية [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) قبل استدعاء هذه الطريقة.
1. عندما تكون كلمة المرور فارغة (null) أو خالية، تُعيد هذه الطريقة false.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [IProtectionManager](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)