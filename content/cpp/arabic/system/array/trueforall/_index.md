---
title: TrueForAll()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد ما إذا كانت جميع العناصر في المصفوفة المحددة تستوفي الشروط التي يحددها الدالة الشرطية المحددة.
type: docs
weight: 677
url: /ar/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) طريقة

تحديد ما إذا كانت جميع العناصر في المصفوفة المحددة تستوفي الشروط المحددة بواسطة الدالة الشرطية المحددة.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) عناصر يجب مطابقتها مع الشروط |
| match | [System::Predicate](../../predicate/)\<T\> | دالة شرطية تحدد الشروط لمطابقة عناصر المصفوفة |

### قيمة الإرجاع

true إذا كانت جميع عناصر المصفوفة arr تستوفي الشروط المعرفة بواسطة الدالة الشرطية match، وإلا false

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* تعريف نوع [Predicate](../../predicate/)
* فئة [Array](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)