---
title: HashSet()
second_title: Aspose.Slides برای C++ مرجع API
description: اطلاعات RTTI.
type: docs
weight: 1
url: /fa/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() سازنده

اطلاعات RTTI.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## توضیحات

یک مجموعه خالی ایجاد می‌کند. 

## HashSet::HashSet(int) سازنده

یک مجموعه خالی با ظرفیت مشخص ایجاد می‌کند.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) سازنده

یک مجموعه خالی که از مقایسه‌گر برابری مشخص استفاده می‌کند ایجاد می‌کند.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) شیئی برای ارتباط با hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) سازنده

یک hashset بر اساس مقادیر قابل شمارش ایجاد می‌کند.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## مراجعه کنید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [HashSet](../)
* کلاس [IEqualityComparer](../../iequalitycomparer/)
* کلاس [IEnumerable](../../ienumerable/)
* فضای‌نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)