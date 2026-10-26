---
title: Sort()
second_title: Aspose.Slides برای مرجع API C++
description: یک Span را با استفاده از یک مقایسه‌گر سفارشی مرتب می‌کند.
type: docs
weight: 339
url: /fa/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) تابع

یک [Span](../../system/span/) را با استفاده از یک مقایسه‌گر سفارشی مرتب می‌کند.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |
| TComparer | نوع شیء مقایسه‌گر |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span برای مرتب‌سازی |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer به شیء مقایسه‌گر برای مقایسه عناصر |

## System::MemoryExtensions::Sort(Span\<T\>\&) تابع

یک [Span](../../system/span/) را با مقایسه پیش‌فرض مرتب می‌کند.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | span برای مرتب‌سازی |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) تابع

جفت‌های کلید-مقدار را با استفاده از یک مقایسه‌گر سفارشی مرتب می‌کند (کلیدها و مقادیر به‌صورت مشترک مرتب می‌شوند)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع کلیدها |
| TValue | نوع مقادیر |
| TComparer | نوع شیء مقایسه‌گر |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | span کلیدها برای مرتب‌سازی |
| values | [Span](../../system/span/)\<TValue\>\& | span مقادیر برای مرتب‌سازی (همزمانی با کلیدها حفظ می‌شود) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer به شیء مقایسه‌گر برای مقایسه کلیدها |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) تابع

جفت‌های کلید-مقدار را با استفاده از یک Delegate مقایسه‌ای مرتب می‌کند.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع کلیدها |
| TValue | نوع مقادیر |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | span کلیدها برای مرتب‌سازی |
| values | [Span](../../system/span/)\<TValue\>\& | span مقادیر برای مرتب‌سازی |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegate برای مقایسه کلید |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) تابع

جفت‌های کلید-مقدار را با مقایسه پیش‌فرض مرتب می‌کند.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TKey | نوع کلیدها |
| TValue | نوع مقادیر |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | span کلیدها برای مرتب‌سازی |
| values | [Span](../../system/span/)\<TValue\>\& | span مقادیر برای مرتب‌سازی |

## موارد مرتبط

* Typedef [SharedPtr](../../system/sharedptr/)
* کلاس [Span](../../system/span/)
* کلاس [Comparison](../../system/comparison/)
* فضای‌نام [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)