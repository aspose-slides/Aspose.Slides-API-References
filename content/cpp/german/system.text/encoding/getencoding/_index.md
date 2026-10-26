---
title: GetEncoding()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Kodierung nach Name.
type: docs
weight: 508
url: /de/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) Methode

Ermittelt die Kodierung nach Name.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) Name. |

### Rückgabewert

[Encoding](../) von angegebenem Namen.

## Encoding::GetEncoding(int) Methode

Ermittelt die Kodierung nach Codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| codepage | int | Codepage-Nummer. |

### Rückgabewert

[Encoding](../) von angegebener Codepage.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) Methode

Ermittelt die Kodierung nach Codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| codepage | int | Codepage-Nummer. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback, das für die Kodierung verwendet wird. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback, das für die Dekodierung verwendet wird. |

### Rückgabewert

[Encoding](../) von angegebener Codepage.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) Methode

Ermittelt die Kodierung nach Name.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) Name. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback, das für die Kodierung verwendet wird. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback, das für die Dekodierung verwendet wird. |

### Rückgabewert

[Encoding](../) von angegebenem Namen.

## Siehe auch

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Klasse [String](../../../system/string/)
* Klasse [Encoding](../)
* Namensraum [System::Text](../../)
* Library [Aspose.Slides](../../../)