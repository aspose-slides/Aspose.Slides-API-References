---
title: GetEncoding()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera kodowanie po nazwie.
type: docs
weight: 508
url: /pl/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) metoda

Pobiera kodowanie po nazwie.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |

### Wartość zwracana

[Encoding](../) o podanej nazwie.

## Encoding::GetEncoding(int) metoda

Pobiera kodowanie na podstawie kodowej strony.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| codepage | int | Numer strony kodowej. |

### Wartość zwracana

[Encoding](../) o podanej stronie kodowej.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metoda

Pobiera kodowanie na podstawie kodowej strony.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| codepage | int | Numer strony kodowej. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Zapasowy mechanizm używany przy kodowaniu. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Zapasowy mechanizm używany przy dekodowaniu. |

### Wartość zwracana

[Encoding](../) o podanej stronie kodowej.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metoda

Pobiera kodowanie po nazwie.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Zapasowy mechanizm używany przy kodowaniu. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Zapasowy mechanizm używany przy dekodowaniu. |

### Wartość zwracana

[Encoding](../) o podanej nazwie.

## Zobacz także

* Definicja typu [EncodingPtr](../../../system/encodingptr/)
* Definicja typu [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Definicja typu [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Klasa [String](../../../system/string/)
* Klasa [Encoding](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)