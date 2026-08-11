---
title: CheckWriteProtection()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد ما إذا كان العرض التقديمي محميًا بكلمة مرور للتعديل.
type: docs
weight: 157
url: /ar/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) طريقة

يحدد ما إذا كان عرض تقديمي محميًا بكلمة مرور للتعديل.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | كلمة المرور للتحقق. |

### قيمة الإرجاع

True إذا كانت كلمة المرور صالحة؛ وإلا false.

## ملاحظات

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. يجب عليك فحص الخاصية [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) قبل استدعاء هذه الطريقة.
1. عند كون كلمة المرور null أو فارغة، تُعيد هذه الطريقة false.

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [ProtectionManager](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)