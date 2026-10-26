---
title: LINQ_All()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد ما إذا كان جميع عناصر التسلسل تستوفي شرطًا.
type: docs
weight: 144
url: /ar/system.collections.generic/ienumerable/linq_all/
---
## IEnumerable::LINQ_All(std::function\<bool(T)>) طريقة

يحدد ما إذا كانت جميع عناصر التسلسل تستوفي شرطًا.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_All(std::function<bool(T)> predicate)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | دالة لاختبار كل عنصر وفق شرط. |

### قيمة الإرجاع

true إذا كان كل عنصر من عناصر التسلسل المصدر يمر بالاختبار في الدالة المحددة، أو إذا كان التسلسل فارغًا؛ وإلا false.

## انظر أيضًا

* الفئة [IEnumerable](../)
* النطاق [System::Collections::Generic](../../)
* المكتبة [Aspose.Slides](../../../)