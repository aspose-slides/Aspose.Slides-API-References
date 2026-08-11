---
title: CheckPassword()
second_title: Aspose.Slides لـ C++ مرجع API
description: يتحقق ما إذا كانت كلمة المرور صحيحة لعروض تقديمية محمية بكلمة مرور مفتوحة.
type: docs
weight: 53
url: /ar/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) طريقة


يتحقق مما إذا كانت كلمة المرور صحيحة لعروض تقديمية محمية بكلمة مرور مفتوحة.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | كلمة المرور للتحقق منها. |

### قيمة الإرجاع

True إذا كانت العروض التقديمية محمية بكلمة مرور مفتوحة وكانت كلمة المرور صحيحة وإلا false.

## ملاحظات



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



عند تكون كلمة المرور null أو فارغة، تُعيد هذه الطريقة false. 

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [PresentationInfo](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)