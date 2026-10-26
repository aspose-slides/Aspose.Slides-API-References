---
title: GetCharCount()
second_title: مرجع API Aspose.Slides برای C++
description: تعداد کاراکترهای مورد نیاز برای رمزگشایی یک بافر را بر می‌گرداند.
type: docs
weight: 40
url: /fa/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) متد

تعداد کاراکترهای لازم برای رمزگشایی یک بافر را باز می‌گرداند.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بایت‌های برای رمزگشایی. |
| index | int | [Buffer](../../../system/buffer/) انحراف. |
| count | int | تعداد بایت‌ها برای رمزگشایی. |

### مقدار بازگشت

تعداد کاراکترهای مورد نیاز برای رمزگشایی بافر.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) متد

تعداد کاراکترهای لازم برای رمزگشایی یک بافر را باز می‌گرداند.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بایت‌های برای رمزگشایی. |
| index | int | [Buffer](../../../system/buffer/) انحراف. |
| count | int | تعداد بایت‌ها برای رمزگشایی. |
| flush | **bool** | اگر true باشد، وضعیت داخلی رمزگشا پس از محاسبه پاک می‌شود. |

### مقدار بازگشت

تعداد کاراکترهای مورد نیاز برای رمزگشایی بافر.

## Decoder::GetCharCount(const uint8_t *, int, bool) متد

تعداد کاراکترهای لازم برای رمزگشایی یک بافر را باز می‌گرداند.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const **uint8_t** * | بایت‌های برای رمزگشایی. |
| count | int | تعداد بایت‌ها برای رمزگشایی. |
| flush | **bool** | اگر true باشد، وضعیت داخلی رمزگشا پس از محاسبه پاک می‌شود. |

### مقدار بازگشت

تعداد کاراکترهای مورد نیاز برای رمزگشایی بافر.

## مراجع

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [Decoder](../)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)