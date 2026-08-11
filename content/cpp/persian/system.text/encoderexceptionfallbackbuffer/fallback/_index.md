---
title: Fallback()
second_title: Aspose.Slides برای C++ مرجع API
description: خطا در رمزگذاری را مدیریت می‌کند.
type: docs
weight: 27
url: /fa/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) متد

خطا در رمزگذاری را مدیریت می‌کند.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### پارامترها
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| charUnknown | char_t | کاراکترهای ناشناخته؛ نادیده گرفته می‌شود. |
| index | int | جایگاه کاراکترهای ناشناخته؛ نادیده گرفته می‌شود. |

### مقدار بازگشت
هرگز به‌طور واقعی باز نمی‌گردد؛ در عوض استثنا پرتاب می‌شود.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) متد

خطا در رمزگذاری را مدیریت می‌کند.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### پارامترها
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| charUnknownHigh | char_t | بخش بالایی جفت سوروگاتی که باعث خطا شد. |
| charUnknownLow | char_t | بخش پایینی جفت سوروگاتی که باعث خطا شد. |
| index | int | جایگاه کاراکتر ناشناخته؛ نادیده گرفته می‌شود. |

### مقدار بازگشت
هرگز به‌طور واقعی باز نمی‌گردد؛ در عوض استثنا پرتاب می‌شود.

## موارد مرتبط

* کلاس [EncoderExceptionFallbackBuffer](../)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)