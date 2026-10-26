---
title: Exchange()
second_title: Aspose.Slides برای C++ مرجع API
description: "مقدار متغیر را جابجا می‌کند: مقدار جدید را ذخیره می‌کند و مقدار متغیر را درست پیش از ذخیره‌سازی برمی‌گرداند."
type: docs
weight: 66
url: /fa/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) متد

مقدار متغیر را جابجا می‌کند: مقدار جدید را ذخیره می‌کند و مقدار متغیر را درست پیش از ذخیره‌سازی برمی‌گرداند.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع متغیر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| location1 | T\& | مرجع متغیر برای تغییر. |
| value | T | مقدار برای ذخیره‌سازی. |

### مقدار بازگشت

مقدار متغیر درست پیش از تغییر آن.

## Interlocked::Exchange(T\&, T) متد

مقدار متغیر را جابجا می‌کند: مقدار جدید را ذخیره می‌کند و مقدار متغیر را درست پیش از ذخیره‌سازی برمی‌گرداند. پیاده‌سازی نشده.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع متغیر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| location1 | T\& | مرجع متغیر برای تغییر. |
| value | T | مقدار برای ذخیره‌سازی. |

### مقدار بازگشت

مقدار متغیر درست پیش از تغییر آن.

## موارد مرتبط

* کلاس [Interlocked](../)
* فضای نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)