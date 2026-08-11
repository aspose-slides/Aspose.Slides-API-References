---
title: Sign()
second_title: مرجع API Aspose.Slides برای C++
description: علامت مقدار صحیح امضاشدهٔ مشخص‌شده را تعیین می‌کند.
type: docs
weight: 274
url: /fa/system/mathf/sign/
---
## MathF::Sign(T) متد

علامت مقدار صحیح امضاشدهٔ مشخص‌شده را تعیین می‌کند.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عدد صحیح امضاشده |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | T | مقداری که علامت آن تعیین می‌شود |

### مقدار برگشتی

- 1 اگر **value** کمتر از 0 باشد؛ 0 اگر **value** برابر با 0 باشد؛ 1 اگر **value** بزرگتر از 0 باشد

## MathF::Sign(T) متد

علامت مقدار عدد شناور مشخص‌شده را تعیین می‌کند.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عدد شناور آرگومان |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | T | مقداری که علامت آن تعیین می‌شود |

### مقدار برگشتی

- 1 اگر **value** کمتر از 0 باشد؛ 0 اگر **value** برابر با 0 باشد؛ 1 اگر **value** بزرگتر از 0 باشد

## موارد مرتبط

* ساختار [MathF](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)