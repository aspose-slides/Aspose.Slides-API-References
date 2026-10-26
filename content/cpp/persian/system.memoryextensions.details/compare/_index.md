---
title: Compare()
second_title: مرجع API Aspose.Slides برای C++
description: دو اشاره‌گر هوشمند را مقایسه می‌کند.
type: docs
weight: 1
url: /fa/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) تابع

دو اشاره‌گر هوشمند را مقایسه می‌کند.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اولین اشاره‌گر هوشمند |
| U | نوع دومین اشاره‌گر هوشمند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | اولین اشاره‌گر هوشمند |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | دومین اشاره‌گر هوشمند |

### مقدار بازگشتی

[Comparison](../../system/comparison/) نتیجه (0 اگر برابر, -1 اگر a < b, 1 اگر a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) تابع

دو مقدار عددی را مقایسه می‌کند.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عددی |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const T\& | اولین مقدار |
| b | const T\& | دومین مقدار |

### مقدار بازگشتی

[Comparison](../../system/comparison/) نتیجه (0 اگر برابر, -1 اگر a < b, 1 اگر a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) تابع

یک اشاره‌گر هوشمند را با یک مقدار مقایسه می‌کند.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوعی که اشاره‌گر هوشمند به آن اشاره می‌کند |
| U | نوع مقدار |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | اشاره‌گر هوشمند |
| b | const U\& | مقدار |

### مقدار بازگشتی

[Comparison](../../system/comparison/) نتیجه (0 اگر برابر, -1 اگر a < b, 1 اگر a > b)

## موارد مرتبط

* تعریف نوع [SharedPtr](../../system/sharedptr/)
* فضای نام [System::MemoryExtensions::Details](../)
* کتابخانه [Aspose.Slides](../../)