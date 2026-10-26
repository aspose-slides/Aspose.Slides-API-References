---
title: GetEncoding()
second_title: Aspose.Slides برای C++ مرجع API
description: کدگذاری را بر اساس نام دریافت می‌کند.
type: docs
weight: 508
url: /fa/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) متد

کدگذاری را بر اساس نام دریافت می‌کند.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |

### مقدار بازگشتی

[Encoding](../) of specified name.

## Encoding::GetEncoding(int) متد

کدگذاری را بر اساس کدصفحه دریافت می‌کند.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| codepage | int | Codepage number. |

### مقدار بازگشتی

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) متد

کدگذاری را بر اساس کدصفحه دریافت می‌کند.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| codepage | int | Codepage number. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### مقدار بازگشتی

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) متد

کدگذاری را بر اساس نام دریافت می‌کند.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### مقدار بازگشتی

[Encoding](../) of specified name.

## موارد مرتبط

* نوع‌تعریف [EncodingPtr](../../../system/encodingptr/)
* نوع‌تعریف [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* نوع‌تعریف [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* کلاس [String](../../../system/string/)
* کلاس [Encoding](../)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)