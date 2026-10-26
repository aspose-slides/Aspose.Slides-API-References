---
title: SortedSet()
second_title: راهنمای API Aspose.Slides برای C++
description: یک مجموعه خالی ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() سازنده

یک مجموعه خالی ایجاد می‌کند.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) سازنده

یک مجموعه خالی با ظرفیت مشخص ایجاد می‌کند.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) سازنده

یک مجموعه خالی ایجاد می‌کند که از مقایسه‌گر برابری مشخص استفاده می‌کند.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) شیء برای ارتباط با [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) سازنده

[SortedSet](../) را بر پایه مقادیر قابل شمارش ایجاد می‌کند.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SortedSet](../)
* Class [IComparer](../../icomparer/)
* Class [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)