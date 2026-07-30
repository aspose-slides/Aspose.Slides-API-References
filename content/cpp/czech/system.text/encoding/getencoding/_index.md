---
title: GetEncoding()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá kódování podle názvu.
type: docs
weight: 508
url: /cs/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) metoda


Získá kódování podle názvu.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) název. |

### Návratová hodnota

[Encoding](../) zadaného názvu.

## Encoding::GetEncoding(int) metoda


Získá kódování podle kódové stránky.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| codepage | int | Číslo kódové stránky. |

### Návratová hodnota

[Encoding](../) zadané kódové stránky.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metoda


Získá kódování podle kódové stránky.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| codepage | int | Číslo kódové stránky. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Záložní mechanismus pro kódování. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Záložní mechanismus pro dekódování. |

### Návratová hodnota

[Encoding](../) zadané kódové stránky.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metoda


Získá kódování podle názvu.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) název. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Záložní mechanismus pro kódování. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Záložní mechanismus pro dekódování. |

### Návratová hodnota

[Encoding](../) zadaného názvu.

## Viz také

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Třída [String](../../../system/string/)
* Třída [Encoding](../)
* Jmenný prostor [System::Text](../../)
* Library [Aspose.Slides](../../../)