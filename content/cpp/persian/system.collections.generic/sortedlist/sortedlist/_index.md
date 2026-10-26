---
title: SortedList()
second_title: مرجع API Aspose.Slides برای C++
description: یک لیست خالی ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() سازنده

یک لیست خالی ایجاد می‌کند.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) سازنده

یک لیست خالی ایجاد می‌کند.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) برای استفاده. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) سازنده

سازنده‌ی کپی.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) برای کپی داده‌ها. |

## SortedList::SortedList(const map_t\&) سازنده

سازنده‌ی کپی.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | نقشه برای کپی داده‌ها. |

## SortedList::SortedList(int) سازنده

یک لیست خالی ایجاد می‌کند.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| capacity | int | تعداد عناصری که باید رزرو شود. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Class [SortedList](../)
* Class [IComparer](../../icomparer/)
* Class [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)