---
title: Sort()
second_title: مرجع API برای Aspose.Slides به زبان C++
description: عناصر را در آرایهٔ مشخص‌شده با استفاده از مقایسه‌گر پیش‌فرض مرتب می‌کند.
type: docs
weight: 742
url: /fa/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) متد

عناصر را در آرایه مشخص‌شده با استفاده از مقایسه‌گر پیش‌فرض مرتب می‌کند.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | آرایه هدف |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) متد

بخشی از عناصر را در آرایه مشخص‌شده با استفاده از مقایسه‌گر پیش‌فرض مرتب می‌کند.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | آرایه هدف |
| startIndex | int | شاخصی که آغاز بازه‌ای از عناصر برای مرتب‌سازی را مشخص می‌کند |
| count | int | اندازه بازه‌ای از عناصر برای مرتب‌سازی |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) متد

عناصر را در آرایه مشخص‌شده با استفاده از مقایسه‌گر مشخص‌شده مرتب می‌کند.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | آرایه هدف |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | شیء IComparer<T> که برای مقایسهٔ عناصر آرایه استفاده می‌شود |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) متد

پیاده‌سازی نشده.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) متد

عناصر را در آرایه مشخص‌شده با استفاده از مقایسهٔ مشخص‌شده مرتب می‌کند.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) متد

دو آرایه را که یکی شامل کلیدها و دیگری شامل آیتم‌های متناظر است، بر اساس مقادیر آرایه **keys**، که عناصر آن با استفاده از عملگر < مقایسه می‌شوند، مرتب می‌کند.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع عناصر موجود در آرایه **keys** |
| TValue | نوع عناصر موجود در آرایه **items** |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) که مقادیر کلید را شامل می‌شود |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) که مواردی را شامل می‌شود که به مقادیر کلید در آرایه **keys** نگاشته شده‌اند |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) متد

دو آرایه را که یکی شامل کلیدها و دیگری شامل آیتم‌های متناظر است، بر اساس مقادیر آرایه **keys**، که عناصر آن با استفاده از مقایسه‌گر پیش‌فرض مقایسه می‌شوند، مرتب می‌کند.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع عناصر موجود در آرایه **keys** |
| TValue | نوع عناصر موجود در آرایه **items** |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) که مقادیر کلید را شامل می‌شود |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) که مواردی را شامل می‌شود که به مقادیر کلید در آرایه **keys** نگاشته شده‌اند |
| index | int | شاخصی که آغاز بازهٔ مورد نظر برای مرتب‌سازی را نشان می‌دهد |
| length | int | تعداد عناصر در بازهٔ مورد نظر برای مرتب‌سازی |

## مراجع

* تعریف نوع [ArrayPtr](../../arrayptr/)
* تعریف نوع [SharedPtr](../../sharedptr/)
* متد [Type](../../object/type/)
* کلاس [Array](../)
* کلاس [IComparer](../../../system.collections.generic/icomparer/)
* کلاس [Comparison](../../comparison/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)