---
title: Sign()
second_title: Aspose.Slides برای C++ مرجع API
description: علامت مقدار صحیح امضاشدهٔ مشخص‌شده را تعیین می‌کند.
type: docs
weight: 274
url: /fa/system/math/sign/
---
## Math::Sign(T) متد


علامت مقدار صحیح امضاشدهٔ مشخص‌شده را تعیین می‌کند.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع صحیح امضاشده |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | T | مقداری که علامت آن تعیین می‌شود |

### مقدار بازگشت

- 1 اگر **value** کمتر از 0 باشد؛ 0 اگر **value** برابر 0 باشد؛ 1 اگر **value** بزرگتر از 0 باشد

## Math::Sign(T) متد


علامت مقدار عدد شناورٔ مشخص‌شده را تعیین می‌کند.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عدد شناور آرگومان |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | T | مقداری که علامت آن تعیین می‌شود |

### مقدار بازگشت

- 1 اگر **value** کمتر از 0 باشد؛ 0 اگر **value** برابر 0 باشد؛ 1 اگر **value** بزرگتر از 0 باشد

## Math::Sign(const Decimal\&) متد


علامت مقدار اعشاریٔ (دسیما) مشخص‌شده را تعیین می‌کند.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | مقداری که علامت آن تعیین می‌شود |

### مقدار بازگشت

- 1 اگر **value** کمتر از 0 باشد؛ 0 اگر **value** برابر 0 باشد؛ 1 اگر **value** بزرگتر از 0 باشد

## همچنین ببینید

* کلاس [Decimal](../../decimal/)
* ساختار [Math](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)