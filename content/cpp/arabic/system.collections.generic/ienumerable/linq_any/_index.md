---
title: LINQ_Any()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد ما إذا كانت السلسلة تحتوي على أي عناصر.
type: docs
weight: 157
url: /ar/system.collections.generic/ienumerable/linq_any/
---
## IEnumerable::LINQ_Any() طريقة

يحدد ما إذا كانت السلسلة تحتوي على أي عناصر.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any()
```

### قيمة الإرجاع

true إذا كانت سلسلة المصدر تحتوي على أي عناصر؛ وإلا false.

## IEnumerable::LINQ_Any(std::function\<bool(T)>) طريقة

يحدد ما إذا كان أي عنصر من السلسلة موجودًا أو يفي بشرطٍ ما.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any(std::function<bool(T)> predicate)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | دالة لاختبار كل عنصر وفق شرط. |

### قيمة الإرجاع

true إذا كانت سلسلة المصدر تحتوي على أي عناصر؛ وإلا false.

## راجع أيضًا

* الفئة [IEnumerable](../)
* النطاق [System::Collections::Generic](../../)
* المكتبة [Aspose.Slides](../../../)