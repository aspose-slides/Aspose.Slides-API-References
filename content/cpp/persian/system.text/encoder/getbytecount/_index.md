---
title: GetByteCount()
second_title: Aspose.Slides برای C++ مرجع API
description: تعداد بایت‌های مورد نیاز برای رمزگذاری یک بافر را بر می‌گرداند.
type: docs
weight: 40
url: /fa/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method


تعداد بایت‌های لازم برای رمزگذاری یک بافر را بر می‌گرداند.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهای قابل رمزگذاری. |
| index | int | [Buffer](../../../system/buffer/) آفست. |
| count | int | تعداد کاراکترهای قابل رمزگذاری. |
| flush | **bool** | اگر true باشد، پس از محاسبه، وضعیت داخلی انکودر را پاک می‌کند. |

### مقدار برگشت

تعداد بایت‌های مورد نیاز برای رمزگذاری بافر.

## Encoder::GetByteCount(const char_t *, int, bool) method


تعداد بایت‌های لازم برای رمزگذاری یک بافر را بر می‌گرداند.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | کاراکترهای قابل رمزگذاری. |
| count | int | تعداد کاراکترهای قابل رمزگذاری. |
| flush | **bool** | اگر true باشد، پس از محاسبه، وضعیت داخلی انکودر را پاک می‌کند. |

### مقدار برگشت

تعداد بایت‌های مورد نیاز برای رمزگذاری بافر.

## مراجع

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [Encoder](../)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)