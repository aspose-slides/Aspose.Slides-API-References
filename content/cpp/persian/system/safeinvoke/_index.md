---
title: SafeInvoke()
second_title: Aspose.Slides برای مرجع API C++
description: پیاده‌سازی ترجمهٔ عملگر '?.'.
type: docs
weight: 2653
url: /fa/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) function

پیاده‌سازی ترجمه‌ی عملگر '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T0 | نوع عبارت. |
| T1 | نوع لامبدا‌ای که عبارت 'WhenTrue' را محصور می‌کند. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| expr | T0\&& | مقدار عبارت. |
| func | T1\&& | عبارت 'WhenTrue' که به فانکتور متصل است. |

### مقدار بازگشتی

اگر مقدار expr نال نباشد، func را با مقدار آن به عنوان اولین آرگومان فراخوانی می‌کند و باز می‌گرداند؛ در غیر این صورت null باز می‌گرداند.

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)