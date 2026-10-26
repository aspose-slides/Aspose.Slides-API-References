---
title: LastIndexOf()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبحث عن الكائن المحدد ويعيد الفهرس الصفري للظهور الأخير داخل القائمة بالكامل.
type: docs
weight: 469
url: /ar/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const طريقة

يبحث عن الكائن المحدد ويعيد الفهرس الصفري للظهور الأخير داخل القائمة بالكامل.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | الكائن للبحث عنه في القائمة |

### قيمة الإرجاع

الفهرس الصفري للظهور الأخير للعنصر داخل الـ [List](../) بالكامل، إذا وُجد؛ وإلا، -1.

## List::LastIndexOf(const T\&, int32_t) const طريقة

يبحث عن الكائن المحدد ويعيد الفهرس الصفري للظهور الأخير داخل نطاق العناصر في الـ [List](../) الذي يمتد من العنصر الأول إلى الفهرس المحدد.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | الكائن للبحث عنه في القائمة |
| index | **int32_t** | الفهرس الصفري للبداية للبحث العكسي. |

### قيمة الإرجاع

الفهرس الصفري للظهور الأخير للعنصر داخل نطاق العناصر في الـ [List](../) الذي يمتد من العنصر الأول إلى الفهرس، إذا وُجد؛ وإلا، -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const طريقة


يبحث عن الكائن المحدد ويعيد الفهرس الصفري للظهور الأخير داخل نطاق العناصر في الـ [List](../) التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | الكائن للبحث عنه في الـ [List](../) |
| index | **int32_t** | الفهرس الصفري للبداية للبحث العكسي. |
| count | **int32_t** | عدد العناصر في الجزء الذي يتم البحث فيه. |

### قيمة الإرجاع

الفهرس الصفري للظهور الأخير للعنصر داخل نطاق العناصر في الـ [List](../) التي تحتوي على عدد `count` من العناصر وتنتهي عند الفهرس، إذا وُجد؛ وإلا، -1.

## انظر أيضًا

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)