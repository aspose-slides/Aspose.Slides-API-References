---
title: ContainsAnyExcept()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که آیا یک بازهٔ فقط-خواندنی شامل هر عنصری به‌جز سه مقدار مشخص‌شده است یا خیر.
type: docs
weight: 66
url: /fa/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) تابع

بررسی می‌کند که آیا یک بازه فقط-خواندنی شامل هر عنصری به‌جز سه مقدار مشخص‌شده است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| value0 | const T\& | اولین مقداری که باید مستثنی شود |
| value1 | const T\& | دومین مقداری که باید مستثنی شود |
| value2 | const T\& | سومین مقداری که باید مستثنی شود |

### مقدار بازگشت

در صورت یافتن هر عنصری که متفاوت از مقادیر مشخص‌شده باشد، true برمی‌گردد؛ در غیر این صورت false.

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) تابع

بررسی می‌کند که آیا یک بازه قابل تغییر شامل هر عنصری به‌جز سه مقدار مشخص‌شده است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازهٔ قابل تغییری که جستجو در آن انجام می‌شود |
| value0 | const T\& | اولین مقداری که باید مستثنی شود |
| value1 | const T\& | دومین مقداری که باید مستثنی شود |
| value2 | const T\& | سومین مقداری که باید مستثنی شود |

### مقدار بازگشت

در صورت یافتن هر عنصری که متفاوت از مقادیر مشخص‌شده باشد، true برمی‌گردد؛ در غیر این صورت false.

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) تابع

بررسی می‌کند که آیا یک بازه فقط-خواندنی شامل هر عنصری به‌جز دو مقدار مشخص‌شده است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| value0 | const T\& | اولین مقداری که باید مستثنی شود |
| value1 | const T\& | دومین مقداری که باید مستثنی شود |

### مقدار بازگشت

در صورت یافتن هر عنصری که متفاوت از مقادیر مشخص‌شده باشد، true برمی‌گردد؛ در غیر این صورت false.

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) تابع

بررسی می‌کند که آیا یک بازه قابل تغییر شامل هر عنصری به‌جز دو مقدار مشخص‌شده است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازهٔ قابل تغییری که جستجو در آن انجام می‌شود |
| value0 | const T\& | اولین مقداری که باید مستثنی شود |
| value1 | const T\& | دومین مقداری که باید مستثنی شود |

### مقدار بازگشت

در صورت یافتن هر عنصری که متفاوت از مقادیر مشخص‌شده باشد، true برمی‌گردد؛ در غیر این صورت false.

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) تابع

بررسی می‌کند که آیا یک بازه فقط-خواندنی شامل هر عنصری به‌جز یک مقدار مشخص‌شده است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| value | const T\& | مقداری که باید مستثنی شود |

### مقدار بازگشت

در صورت یافتن هر عنصری که متفاوت از مقدار مشخص‌شده باشد، true برمی‌گردد؛ در غیر این صورت false.

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) تابع

بررسی می‌کند که آیا یک بازه قابل تغییر شامل هر عنصری به‌جز یک مقدار مشخص‌شده است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازهٔ قابل تغییری که جستجو در آن انجام می‌شود |
| value | const T\& | مقداری که باید مستثنی شود |

### مقدار بازگشت

در صورت یافتن هر عنصری که متفاوت از مقدار مشخص‌شده باشد، true برمی‌گردد؛ در غیر این صورت false.

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

بررسی می‌کند که آیا یک بازه فقط-خواندنی شامل هر عنصری به‌جز عناصر موجود در بازهٔ دیگر است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه‌ها وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که جستجو در آن انجام می‌شود |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای از مقادیر که باید مستثنی شوند |

### مقدار بازگشت

در صورت یافتن هر عنصری که در values وجود نداشته باشد، true برمی‌گردد؛ در غیر این صورت false.

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) تابع

بررسی می‌کند که آیا یک بازه قابل تغییر شامل هر عنصری به‌جز عناصر موجود در یک بازه فقط-خواندنی است یا خیر.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصری که در بازه‌ها وجود دارند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | بازهٔ قابل تغییری که جستجو در آن انجام می‌شود |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازهٔ فقط-خواندنی از مقادیری که باید مستثنی شوند |

### مقدار بازگشت

در صورت یافتن هر عنصری که در values وجود نداشته باشد، true برمی‌گردد؛ در غیر این صورت false.

## موارد مرتبط

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)