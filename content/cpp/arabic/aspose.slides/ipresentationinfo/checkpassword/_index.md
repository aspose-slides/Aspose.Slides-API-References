---
title: CheckPassword()
second_title: Aspose.Slides لـ C++ مرجع API
description: يتحقق مما إذا كانت كلمة المرور صحيحة لعرض تقديمي محمي بكلمة مرور مفتوحة.
type: docs
weight: 53
url: /ar/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) طريقة


يتحقق مما إذا كانت كلمة المرور صحيحة لعرض تقديمي محمي بكلمة مرور مفتوحة.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```


### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | كلمة المرور للتحقق منها. |

### قيمة الإرجاع

True إذا كان العرض التقديمي محميًا بكلمة مرور مفتوحة وكانت كلمة المرور صحيحة وإلا false.
## ملاحظات



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



عند كون كلمة المرور فارغة أو ذات قيمة null، تُعيد هذه الطريقة false. 
## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [IPresentationInfo](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)