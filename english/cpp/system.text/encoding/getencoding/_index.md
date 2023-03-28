---
title: GetEncoding()
second_title: Aspose.Slides for C++ API Reference
description: Gets encoding by name.
type: docs
weight: 508
url: /cpp/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const [String](../../../system/string/)\&) method


Gets encoding by name.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |

### Return Value

[Encoding](../) of specified name.

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## Encoding::GetEncoding(int) method


Gets encoding by codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Codepage number. |

### Return Value

[Encoding](../) of specified codepage.

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## Encoding::GetEncoding(int, const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\&) method


Gets encoding by codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Codepage number. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### Return Value

[Encoding](../) of specified codepage.

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## Encoding::GetEncoding(const [String](../../../system/string/)\&, const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\&) method


Gets encoding by name.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### Return Value

[Encoding](../) of specified name.

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
