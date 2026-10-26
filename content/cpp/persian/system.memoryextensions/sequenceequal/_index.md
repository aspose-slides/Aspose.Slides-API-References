---
title: SequenceEqual()
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند که آیا دو ReadOnlySpan عناصر یکسانی را به ترتیب یکسان دارند.
type: docs
weight: 326
url: /fa/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

مشخص می‌کند که آیا دو ReadOnlySpan عناصر یکسانی را به ترتیب یکسان دارند یا نه.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span‌ها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | اولین span برای مقایسه |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | دومین span برای مقایسه |

### مقدار بازگشت

true اگر span‌ها طول یکسان داشته باشند و تمام عناصر برابر باشند، در غیر این صورت false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

مشخص می‌کند که آیا یک [Span](../../system/span/) و [ReadOnlySpan](../../system/readonlyspan/) عناصر یکسانی را به ترتیب یکسان دارند یا نه.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span‌ها |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) برای مقایسه |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) برای مقایسه |

### مقدار بازگشت

true اگر span‌ها طول یکسان داشته باشند و تمام عناصر برابر باشند، در غیر این صورت false

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function

مشخص می‌کند که آیا دو ReadOnlySpan عناصر مساوی را با استفاده از یک مقایسه‌کننده سفارشی دارند.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span‌ها |
| TComparer | نوع شیء مقایسه‌کننده |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | اولین span برای مقایسه |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | دومین span برای مقایسه |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer به شیء مقایسه‌کننده برای مقایسه عناصر |

### مقدار بازگشت

true اگر span‌ها طول یکسان داشته باشند و مقایسه‌کننده تمام عناصر را برابر در نظر بگیرد، در غیر این صورت false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function

مشخص می‌کند که آیا یک [Span](../../system/span/) و [ReadOnlySpan](../../system/readonlyspan/) عناصر مساوی را با استفاده از یک مقایسه‌کننده سفارشی دارند.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در span‌ها |
| TComparer | نوع شیء مقایسه‌کننده |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) برای مقایسه |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) برای مقایسه |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer به شیء مقایسه‌کننده برای مقایسه عناصر |

### مقدار بازگشت

true اگر span‌ها طول یکسان داشته باشند و مقایسه‌کننده تمام عناصر را برابر در نظر بگیرد، در غیر این صورت false

## موارد مرتبط

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)