---
title: Convert()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí bajty na znaky.
type: docs
weight: 66
url: /cs/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) metoda

Převádí bajty na znaky.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty k dekódování. |
| byteIndex | int | Posun vstupního bufferu. |
| byteCount | int | Velikost vstupního bufferu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Cílový buffer znaků. |
| charIndex | int | Posun cílového pole. |
| charCount | int | Velikost cílového pole. |
| flush | **bool** | Pokud je true, vyčistí interní stav dekodéru po výpočtu. |
| bytesUsed | int\& | Reference na proměnnou, do které se uloží počet přečtených bajtů. |
| charsUsed | int\& | Reference na proměnnou, do které se uloží počet zapsaných znaků. |
| completed | **bool**\& | Reference na proměnnou, která se nastaví na true, pokud byl vstupní buffer vyčerpán, a na false v opačném případě. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) metoda

Převádí bajty na znaky.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty k dekódování. |
| byteCount | int | Velikost vstupního bufferu. |
| chars | char_t * | Cílový buffer znaků. |
| charCount | int | Velikost cílového pole. |
| flush | **bool** | Pokud je true, vyčistí interní stav dekodéru po výpočtu. |
| bytesUsed | int\& | Reference na proměnnou, do které se uloží počet přečtených bajtů. |
| charsUsed | int\& | Reference na proměnnou, do které se uloží počet zapsaných znaků. |
| completed | **bool**\& | Reference na proměnnou, která se nastaví na true, pokud byl vstupní buffer vyčerpán, a na false v opačném případě. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICUDecoder](../)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)