---
title: GetEncoding()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt codering op op basis van naam.
type: docs
weight: 508
url: /nl/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) methode

Haalt codering op op basis van naam.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) naam. |

### Retourwaarde

[Encoding](../) van opgegeven naam.

## Encoding::GetEncoding(int) methode

Haalt codering op op basis van codepagina.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codepage | int | Codepaginummer. |

### Retourwaarde

[Encoding](../) van opgegeven codepagina.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) methode

Haalt codering op op basis van codepagina.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codepage | int | Codepaginummer. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback die gebruikt wordt voor codering. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback die gebruikt wordt voor decodering. |

### Retourwaarde

[Encoding](../) van opgegeven codepagina.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) methode

Haalt codering op op basis van naam.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) naam. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback die gebruikt wordt voor codering. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback die gebruikt wordt voor decodering. |

### Retourwaarde

[Encoding](../) van opgegeven naam.

## Zie ook

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Klasse [String](../../../system/string/)
* Klasse [Encoding](../)
* Naamruimte [System::Text](../../)
* Library [Aspose.Slides](../../../)