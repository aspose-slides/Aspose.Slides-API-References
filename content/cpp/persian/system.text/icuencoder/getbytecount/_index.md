---
title: GetByteCount()
second_title: Aspose.Slides برای C++ مرجع API
description: تعداد بایت‌های مورد نیاز برای رمزگذاری یک بافر را دریافت می‌کند.
type: docs
weight: 40
url: /fa/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) متد

تعداد بایت‌های مورد نیاز برای رمزگذاری یک بافر را دریافت می‌کند.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترها برای رمزگذاری. |
| index | int | [Buffer](../../../system/buffer/) جابجایی. |
| count | int | تعداد کاراکترهای برای رمزگذاری. |
| flush | **bool** | اگر true باشد، وضعیت داخلی انکودر را پس از محاسبه پاک می‌کند. |

### مقدار بازگشتی

تعداد بایت‌های مورد نیاز برای رمزگذاری بافر.

## ICUEncoder::GetByteCount(const char_t *, int, bool) متد

تعداد بایت‌های مورد نیاز برای رمزگذاری یک بافر را دریافت می‌کند.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | کاراکترها برای رمزگذاری. |
| count | int | تعداد کاراکترهای برای رمزگذاری. |
| flush | **bool** | اگر true باشد، وضعیت داخلی انکودر را پس از محاسبه پاک می‌کند. |

### مقدار بازگشتی

تعداد بایت‌های مورد نیاز برای رمزگذاری بافر.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [ICUEncoder](../)
* فضای نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)