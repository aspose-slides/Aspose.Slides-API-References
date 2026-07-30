---
title: Convert()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí znaky na bajty.
type: docs
weight: 1
url: /cs/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) metoda


Převádí znaky na bajty.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Znaky k zakódování. |
| charCount | int | Velikost vstupního bufferu. |
| bytes | **uint8_t** * | Cílový buffer bajtů. |
| byteCount | int | Velikost cílového pole. |
| flush | **bool** | Pokud je true, vyčistí vnitřní stav enkodéru po výpočtu. |
| charsUsed | int\& | Reference na proměnnou, která ukládá počet přečtených znaků. |
| bytesUsed | int\& | Reference na proměnnou, která ukládá počet zapsaných bajtů. |
| completed | **bool**\& | Reference na proměnnou, která se nastaví na true, pokud byl vstupní buffer vyčerpán, a na false v opačném případě. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) metoda


Převádí znaky na bajty.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaky k zakódování. |
| charIndex | int | Posun ve vstupním bufferu. |
| charCount | int | Velikost vstupního bufferu. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Cílový buffer bajtů. |
| byteIndex | int | Posun v cílovém poli. |
| byteCount | int | Velikost cílového pole. |
| flush | **bool** | Pokud je true, vyčistí vnitřní stav enkodéru po výpočtu. |
| charsUsed | int\& | Reference na proměnnou, která ukládá počet přečtených znaků. |
| bytesUsed | int\& | Reference na proměnnou, která ukládá počet zapsaných bajtů. |
| completed | **bool**\& | Reference na proměnnou, která se nastaví na true, pokud byl vstupní buffer vyčerpán, a na false v opačném případě. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [EncodingEncoder](../)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)