---
title: Fallback()
second_title: Aspose.Slides برای C++ مرجع API
description: عملکرد بازگشت واقعی را پیاده‌سازی می‌کند.
type: docs
weight: 14
url: /fa/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) متد

عملکرد بازگشت واقعی را پیاده‌سازی می‌کند.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | انکودر کاراکتر قادر به رمزگذاری نیست. |
| index | int | [Index](../../../system/index/) کاراکتری که خطا را ایجاد کرد. |

### مقدار بازگشت

درست اگر بافر کاراکترهای ناشناخته را پردازش کند، نادرست اگر آنها را نادیده بگیرد.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) متد

عملکرد بازگشت واقعی را پیاده‌سازی می‌کند.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | بخش بالایی جفت ساجر که باعث خطا شد. |
| charUnknownLow | char_t | بخش پایین جفت ساجر که باعث خطا شد. |
| index | int | [Index](../../../system/index/) کاراکتری که خطا را ایجاد کرد. |

### مقدار بازگشت

درست اگر بافر کاراکترهای ناشناخته را پردازش کند، نادرست اگر آنها را نادیده بگیرد.

## موارد مرتبط

* کلاس [EncoderFallbackBuffer](../)
* فضای نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)