---
title: GetEncoding()
second_title: Aspose.Slides C++ API-referencia
description: Lekéri a kódolást név alapján.
type: docs
weight: 508
url: /hu/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) metódus

Lekéri a kódolást név alapján.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) név. |

### Return Value

[Encoding](../) a megadott névhez.

## Encoding::GetEncoding(int) metódus

Lekéri a kódolást kódlap alapján.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| codepage | int | Kódlapszám. |

### Return Value

[Encoding](../) a megadott kódlaphoz.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metódus

Lekéri a kódolást kódlap alapján.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| codepage | int | Kódlapszám. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | A kódoláshoz használandó fallback. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | A dekódoláshoz használandó fallback. |

### Return Value

[Encoding](../) a megadott kódlaphoz.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metódus

Lekéri a kódolást név alapján.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) név. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | A kódoláshoz használandó fallback. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | A dekódoláshoz használandó fallback. |

### Return Value

[Encoding](../) a megadott névhez.

## Lásd még

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Osztály [String](../../../system/string/)
* Osztály [Encoding](../)
* Névterület [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)