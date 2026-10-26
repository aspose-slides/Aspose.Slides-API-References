---
title: Fallback()
second_title: Aspose.Slides برای C++ مرجع API
description: خطاهای رمزگذاری را مدیریت می‌کند.
type: docs
weight: 27
url: /fa/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) متد

خطاهای رمزگذاری را مدیریت می‌کند.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| charUnknown | char_t | کاراکتر نامشخص؛ نادیده گرفته می‌شود. |
| index | int | موقعیت کاراکتر نامشخص؛ نادیده گرفته می‌شود. |

### مقدار بازگشت

True اگر رشته جایگزین ارائه شده باشد و خالی نباشد، در غیر این صورت false.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) متد

خطاهای رمزگذاری را مدیریت می‌کند.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| charUnknownHigh | char_t | بخش بالا از جفت سورگیت که خطا را ایجاد کرده است. |
| charUnknownLow | char_t | بخش پایین از جفت سورگیت که خطا را ایجاد کرده است. |
| index | int | موقعیت کاراکتر نامشخص؛ نادیده گرفته می‌شود. |

### مقدار بازگشت

True اگر رشته جایگزین ارائه شده باشد و خالی نباشد، در غیر این صورت false.

## موارد مرتبط

* کلاس [EncoderReplacementFallbackBuffer](../)
* فضای نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)