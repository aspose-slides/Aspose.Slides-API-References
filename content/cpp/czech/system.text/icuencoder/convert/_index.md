---
title: Convert()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí znaky na bajty.
type: docs
weight: 66
url: /cs/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) metoda


Převádí znaky na bajty.

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaky k zakódování. |
| charIndex | int | Posun vstupního bufferu. |
| charCount | int | Velikost vstupního bufferu. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Cílový buffer bajtů. |
| byteIndex | int | Posun cílového pole. |
| byteCount | int | Velikost cílového pole. |
| flush | **bool** | Pokud je pravda, vyčistí vnitřní stav enkodéru po výpočtu. |
| charsUsed | int\& | Reference na proměnnou pro uložení počtu přečtených znaků. |
| bytesUsed | int\& | Reference na proměnnou pro uložení počtu zapsaných bajtů. |
| completed | **bool**\& | Reference na proměnnou, která bude nastavena na true, pokud byl vstupní buffer vyčerpán, a na false v opačném případě. |

## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) metoda


Převádí znaky na bajty.

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chars | const char_t * | Znaky k zakódování. |
| charCount | int | Velikost vstupního bufferu. |
| bytes | **uint8_t** * | Cílový buffer bajtů. |
| byteCount | int | Velikost cílového pole. |
| flush | **bool** | Pokud je pravda, vyčistí vnitřní stav enkodéru po výpočtu. |
| charsUsed | int\& | Reference na proměnnou pro uložení počtu přečtených znaků. |
| bytesUsed | int\& | Reference na proměnnou pro uložení počtu zapsaných bajtů. |
| completed | **bool**\& | Reference na proměnnou, která bude nastavena na true, pokud byl vstupní buffer vyčerpán, a na false v opačném případě. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICUEncoder](../)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)