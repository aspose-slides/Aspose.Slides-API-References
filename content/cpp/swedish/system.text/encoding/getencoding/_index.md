---
title: GetEncoding()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar kodning efter namn.
type: docs
weight: 508
url: /sv/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) metod

Hämtar kodning efter namn.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) namn. |

### Returvärde

[Encoding](../) av specificerat namn.

## Encoding::GetEncoding(int) metod

Hämtar kodning efter kodsida.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codepage | int | Kodsidnummer. |

### Returvärde

[Encoding](../) av specificerad kodsida.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metod

Hämtar kodning efter kodsida.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codepage | int | Kodsidnummer. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback att använda för kodning. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback att använda för avkodning. |

### Returvärde

[Encoding](../) av specificerad kodsida.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metod

Hämtar kodning efter namn.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) namn. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback att använda för kodning. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback att använda för avkodning. |

### Returvärde

[Encoding](../) av specificerat namn.

## Se även

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)