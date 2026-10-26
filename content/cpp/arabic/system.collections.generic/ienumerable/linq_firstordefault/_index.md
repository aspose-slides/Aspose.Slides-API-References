---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides للغة C++ مرجع API
description: يُرجِع العنصر الأول في تسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا.
type: docs
weight: 66
url: /ar/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() طريقة

يُرجِع العنصر الأول في تسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### قيمة الإرجاع

العنصر الأول في التسلسل أو قيمة مُنشأة افتراضيًا إذا كان التسلسل فارغًا.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) طريقة

يُرجِع العنصر الأول في التسلسل الذي يفي بشرط ما أو قيمة افتراضية إذا لم يُعثر على عنصر كهذا.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | دالة لاختبار كل عنصر بالنسبة لpredicate. |

### قيمة الإرجاع

default(T) إذا كان source فارغًا أو إذا لم يجتاز أي عنصر الاختبار المحدد بواسطة predicate؛ وإلا، العنصر الأول في source الذي يجتاز الاختبار المحدد بواسطة predicate.

## انظر أيضًا

* فئة [IEnumerable](../)
* نطاق [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)