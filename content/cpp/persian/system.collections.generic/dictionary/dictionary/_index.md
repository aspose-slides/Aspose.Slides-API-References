---
title: Dictionary()
second_title: Aspose.Slides برای C++ API مرجع
description: یک دیکشنری خالی ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() سازنده

یک دیکشنری خالی ایجاد می‌کند.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) سازنده

داده‌ها را از map کپی می‌کند.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map برای کپی داده‌ها از. |

## Dictionary::Dictionary(int) سازنده

بارگذاری‌وفری که متناظر با ایجاد دیکشنری از پیش تخصیص‌یافته است؛ در واقع هیچ تخصیصی انجام نمی‌دهد.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| capacity | int | ظرفیت برای تخصیص؛ نادیده گرفته می‌شود. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) سازنده

سازندهٔ کپی.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) برای کپی داده‌ها از. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) سازنده

سازندهٔ کپی.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | دیکشنری منبع. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) شی برای استفاده. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) سازنده

یک دیکشنری خالی ایجاد می‌کند.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) برای استفاده. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) سازنده

یک دیکشنری خالی ایجاد می‌کند.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| capacity | int | [Dictionary](../) ظرفیت پس از ایجاد؛ نادیده گرفته می‌شود. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) برای استفاده. |

## مراجع

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Dictionary](../)
* کلاس [IDictionary](../../idictionary/)
* کلاس [IEqualityComparer](../../iequalitycomparer/)
* فضای‌نام [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)