---
title: FindIndex()
second_title: مرجع API Aspose.Slides لـ C++
description: يبحث عن العنصر الأول في المصفوفة المحددة الذي يفي بشروط الدالة الشرطية المحددة.
type: docs
weight: 638
url: /ar/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) طريقة

يبحث عن العنصر الأول في المصفوفة المحددة والذي يفي بشروط الدالة الشرطية المحددة.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) للبحث عن عنصر في |
| match | [System::Predicate](../../predicate/)\<T\> | دالة شرطية تحدد الشروط لمطابقة عناصر المصفوفة ضدها |

### قيمة الإرجاع

فهرس العنصر الأول في المصفوفة الذي يفي بالشروط المحددة بواسطة الدالة الشرطية، وإلا -1

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* تعريف نوع [Predicate](../../predicate/)
* فئة [Array](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)