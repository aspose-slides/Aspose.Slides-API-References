---
title: GetCharCount()
second_title: Aspose.Slides برای C++ مرجع API
description: تعداد کاراکترهای مورد نیاز برای رمزگشای یک بافر را برمی‌گرداند.
type: docs
weight: 40
url: /fa/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

تعداد کاراکترهای مورد نیاز برای رمزگشای یک بافر را برمی‌گرداند.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بایت‌های قابل رمزگشایی. |
| index | int | [Buffer](../../../system/buffer/) افست. |
| count | int | تعداد بایت‌های قابل رمزگشایی. |

### مقدار بازگشت

تعداد کاراکترهای مورد نیاز برای رمزگشای بافر.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method

تعداد کاراکترهای مورد نیاز برای رمزگشای یک بافر را برمی‌گرداند.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بایت‌های قابل رمزگشایی. |
| index | int | [Buffer](../../../system/buffer/) افست. |
| count | int | تعداد بایت‌های قابل رمزگشایی. |
| flush | **bool** | اگر true باشد، وضعیت داخلی رمزگشا را پس از محاسبه پاک می‌کند. |

### مقدار بازگشت

تعداد کاراکترهای مورد نیاز برای رمزگشای بافر.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) method

تعداد کاراکترهای مورد نیاز برای رمزگشای یک بافر را برمی‌گرداند.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const **uint8_t** * | بایت‌های قابل رمزگشایی. |
| count | int | تعداد بایت‌های قابل رمزگشایی. |
| flush | **bool** | اگر true باشد، وضعیت داخلی رمزگشا را پس از محاسبه پاک می‌کند. |

### مقدار بازگشت

تعداد کاراکترهای مورد نیاز برای رمزگشای بافر.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [ICUDecoder](../)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)