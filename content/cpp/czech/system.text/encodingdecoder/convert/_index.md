---
title: Convert()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převádí bajty na znaky.
type: docs
weight: 1
url: /cs/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method

Převádí bajty na znaky.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty k dekódování. |
| byteCount | int | Velikost vstupního bufferu. |
| chars | char_t * | Cílový buffer znaků. |
| charCount | int | Velikost cílového pole. |
| flush | **bool** | Pokud je true, po výpočtu vyčistí interní stav dekodéru. |
| bytesUsed | int\& | Odkaz na proměnnou pro uložení počtu přečtených bajtů. |
| charsUsed | int\& | Odkaz na proměnnou pro uložení počtu zapsaných znaků. |
| completed | **bool**\& | Odkaz na proměnnou, která bude nastavena na true, pokud byl vstupní buffer vyčerpán, a na false jinak. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method

Převádí bajty na znaky.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty k dekódování. |
| byteIndex | int | Offset vstupního bufferu. |
| byteCount | int | Velikost vstupního bufferu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Cílový buffer znaků. |
| charIndex | int | Offset cílového pole. |
| charCount | int | Velikost cílového pole. |
| flush | **bool** | Pokud je true, po výpočtu vyčistí interní stav dekodéru. |
| bytesUsed | int\& | Odkaz na proměnnou pro uložení počtu přečtených bajtů. |
| charsUsed | int\& | Odkaz na proměnnou pro uložení počtu zapsaných znaků. |
| completed | **bool**\& | Odkaz na proměnnou, která bude nastavena na true, pokud byl vstupní buffer vyčerpán, a na false jinak. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [EncodingDecoder](../)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)