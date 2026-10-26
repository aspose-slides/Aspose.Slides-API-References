---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides للـ C++ مرجع API
description: يقوم بترتيب عناصر التسلسل بترتيب تنازلي وفقًا لقيم المفتاح التي يتم اختيارها بواسطة keySelector.
type: docs
weight: 222
url: /ar/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) طريقة

يقوم بترتيب عناصر تسلسل بترتيب تنازلي وفقاً لقيم المفتاح التي يحددها keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| keySelector | دالة لاستخراج المفتاح من العنصر. |

### Return Value

IOrderedEnumerable الذي تُرتب عنصراته بترتيب تنازلي للمفتاح

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) طريقة

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)