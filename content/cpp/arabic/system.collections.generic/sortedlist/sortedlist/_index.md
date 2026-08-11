---
title: SortedList()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ قائمة فارغة.
type: docs
weight: 1
url: /ar/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() مُنشئ

ينشئ قائمة فارغة.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) مُنشئ

ينشئ قائمة فارغة.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) للاستخدام. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) مُنشئ

منشئ نسخة.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) لنسخ البيانات منها. |

## SortedList::SortedList(const map_t\&) مُنشئ

منشئ نسخة.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | خريطة لنسخ البيانات منها. |

## SortedList::SortedList(int) مُنشئ

ينشئ قائمة فارغة.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | عدد العناصر التي سيتم حجزها. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Class [SortedList](../)
* Class [IComparer](../../icomparer/)
* Class [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)