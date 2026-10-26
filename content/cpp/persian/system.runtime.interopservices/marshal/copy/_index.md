---
title: Copy()
second_title: مرجع API Aspose.Slides برای C++
description: عملکرد متد public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) را پیاده‌سازی می‌کند.
type: docs
weight: 1
url: /fa/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) متد

عملکرد متد public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) را پیاده‌سازی می‌کند.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| container | نوع container مقصد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | const IntPtr | اشاره‌گر داده منبع. |
| destination | container\&& | Container برای کپی کردن داده‌ها به آن. |
| startIndex | int | اندیس شروع منبع. |
| length | int | تعداد عناصر برای کپی. |

## Marshal::Copy(const void *, container\&&, int, int) متد

عملکرد متد public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) را پیاده‌سازی می‌کند.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| container | نوع container مقصد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | const void * | اشاره‌گر داده منبع. |
| destination | container\&& | Container برای کپی کردن داده‌ها به آن. |
| startIndex | int | اندیس شروع منبع. |
| length | int | تعداد عناصر برای کپی. |

## Marshal::Copy(const container\&, int, void *, int) متد

عملکرد متد public static void Copy(char[] source, int startIndex, IntPtr destination, int length) را پیاده‌سازی می‌کند.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| container | نوع container منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | const container\& | اشاره‌گر داده منبع. |
| startIndex | int | اندیس شروع منبع. |
| destination | void * | اشاره‌گر داده مقصد. |
| length | int | تعداد عناصر برای کپی. |

## Marshal::Copy(const container\&, int, IntPtr, int) متد

عملکرد متد public static void Copy(char[] source, int startIndex, IntPtr destination, int length) را پیاده‌سازی می‌کند.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| container | نوع container منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | const container\& | اشاره‌گر داده منبع. |
| startIndex | int | اندیس شروع منبع. |
| destination | IntPtr | اشاره‌گر داده مقصد. |
| length | int | تعداد عناصر برای کپی. |

## موارد مرتبط

* کلاس [Marshal](../)
* فضای‌نام [System::Runtime::InteropServices](../../)
* کتابخانه [Aspose.Slides](../../../)