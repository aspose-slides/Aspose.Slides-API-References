---
title: SortedSet()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مجموعة فارغة.
type: docs
weight: 1
url: /ar/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() المُنشئ

ينشئ مجموعة فارغة.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) المُنشئ

ينشئ مجموعة فارغة بسعة محددة.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) المُنشئ

ينشئ مجموعة فارغة تستخدم المقارن المتساوي المحدد.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) كائن لربطه بـ [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) المُنشئ

ينشئ [SortedSet](../) استنادًا إلى القيم القابلة للتعداد.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SortedSet](../)
* Class [IComparer](../../icomparer/)
* Class [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)