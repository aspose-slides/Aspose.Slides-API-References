---
title: GetEncoding()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يحصل على الترميز بالاسم.
type: docs
weight: 508
url: /ar/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) طريقة

Gets encoding by name.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |

### قيمة الإرجاع

[Encoding](../) of specified name.

## Encoding::GetEncoding(int) طريقة

Gets encoding by codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| codepage | int | Codepage number. |

### قيمة الإرجاع

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) طريقة

Gets encoding by codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| codepage | int | Codepage number. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### قيمة الإرجاع

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) طريقة

Gets encoding by name.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### قيمة الإرجاع

[Encoding](../) of specified name.

## انظر أيضًا

* تعريف نوع [EncodingPtr](../../../system/encodingptr/)
* تعريف نوع [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* تعريف نوع [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* فئة [String](../../../system/string/)
* فئة [Encoding](../)
* نطاق [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)