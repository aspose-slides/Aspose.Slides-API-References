---
title: HasOperatorEqualsHelper()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: دالة مساعدة لتحديد ما إذا كانت الفئة المحددة تحتوي على المشغل ==.
type: docs
weight: 235
url: /ar/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) دالة

دالة مساعدة لتحديد ما إذا كانت الفئة المحددة تحتوي على المشغل ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع للتحقق منه. |
| Dummy | معامل وهمي لسحر SFINAE. |

### قيمة الإرجاع

قيمة std::true_type إذا كان المشغل == موجودًا وإلا false.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) دالة

دالة مساعدة لتحديد ما إذا كانت الفئة المحددة تحتوي على المشغل ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### قيمة الإرجاع

قيمة std::true_type إذا كان المشغل == موجودًا وإلا false.

## انظر أيضًا

* مساحة الاسم [System::Collections::Generic::Details](../)
* مكتبة [Aspose.Slides](../../)