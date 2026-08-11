---
title: Convert()
second_title: Aspose.Slides برای C++ مرجع API
description: بایت‌ها را بین دو رمزگذاری تبدیل می‌کند.
type: docs
weight: 378
url: /fa/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) متد

بایت‌ها را بین دو رمزگذاری تبدیل می‌کند.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری منبع. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری مقصد. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | بایت‌های قابل تبدیل. |

### مقدار بازگشت

بایت‌های تبدیل‌شده.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) متد

بایت‌ها را بین دو رمزگذاری تبدیل می‌کند.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری منبع. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری مقصد. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | بایت‌های قابل تبدیل. |
| index | int | شروع برش. |
| count | int | اندازه برش. |

### مقدار بازگشت

بایت‌های تبدیل‌شده.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* کلاس [Encoding](../)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)