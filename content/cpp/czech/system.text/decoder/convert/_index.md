---
title: Convert()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převádí bajty na znaky.
type: docs
weight: 79
url: /cs/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) metoda

Převádí bajty na znaky.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty k dekódování. |
| byteIndex | int | Posun vstupního bufferu. |
| byteCount | int | Velikost vstupního bufferu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Cílový buffer znaků. |
| charIndex | int | Posun cílového pole. |
| charCount | int | Velikost cílového pole. |
| flush | **bool** | Pokud je true, vyčistí interní stav dekodéru po výpočtu. |
| bytesUsed | int\& | Reference na proměnnou, která ukládá počet přečtených bajtů. |
| charsUsed | int\& | Reference na proměnnou, která ukládá počet zapsaných znaků. |
| completed | **bool**\& | Reference na proměnnou, která se nastaví na true, pokud byl vstupní buffer vyčerpán, jinak na false. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) metoda

Převádí bajty na znaky.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty k dekódování. |
| byteCount | int | Velikost vstupního bufferu. |
| chars | char_t * | Cílový buffer znaků. |
| charCount | int | Velikost cílového pole. |
| flush | **bool** | Pokud je true, vyčistí interní stav dekodéru po výpočtu. |
| bytesUsed | int\& | Reference na proměnnou, která ukládá počet přečtených bajtů. |
| charsUsed | int\& | Reference na proměnnou, která ukládá počet zapsaných znaků. |
| completed | **bool**\& | Reference na proměnnou, která se nastaví na true, pokud byl vstupní buffer vyčerpán, jinak na false. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Decoder](../)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)