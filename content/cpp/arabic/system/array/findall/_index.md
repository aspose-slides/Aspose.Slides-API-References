---
title: FindAll()
second_title: مرجع API Aspose.Slides للغة C++
description: يسترجع جميع العناصر التي تتطابق مع الشروط المحددة بواسطة الدالة الشرطية المحددة.
type: docs
weight: 664
url: /ar/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) طريقة

يقوم باسترجاع جميع العناصر التي تطابق الشروط المحددة بواسطة الدالة الشرطية المحددة.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) للبحث عن العناصر في |
| match | [System::Predicate](../../predicate/)\<T\> | دالة شرطية تحدد الشروط لمطابقة عناصر المصفوفة |

### قيمة الإرجاع

[Array](../) يحتوي على جميع العناصر التي تطابق الشروط المحددة بواسطة الدالة الشرطية المحددة، إذا وجدت؛ وإلا، [Array](../) فارغ.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* تعريف نوع [Predicate](../../predicate/)
* فئة [Array](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)