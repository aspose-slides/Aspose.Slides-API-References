---
title: GetChars()
second_title: Aspose.Slides pro C++ – reference API
description: Získá znaky, které vzniknou dekódováním bufferu.
type: docs
weight: 53
url: /cs/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Získá znaky, které vzniknou dekódováním bufferu.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty k dekódování. |
| byteIndex | int | Posun vstupního bufferu. |
| byteCount | int | Velikost vstupního bufferu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Cílový buffer znaků. |
| charIndex | int | Posun cílového pole. |

### Návratová hodnota

Počet zapsaných znaků.

## ICUDecoder::GetCats(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) method

Získá znaky, které vzniknou dekódováním bufferu.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty k dekódování. |
| byteIndex | int | Posun vstupního bufferu. |
| byteCount | int | Velikost vstupního bufferu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Cílový buffer znaků. |
| charIndex | int | Posun cílového pole. |
| flush | **bool** | Pokud je true, vyčistí vnitřní stav dekodéru po výpočtu. |

### Návratová hodnota

Počet zapsaných znaků.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) method

Získá znaky, které vzniknou dekódováním bufferu.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty k dekódování. |
| byteCount | int | Velikost vstupního bufferu. |
| chars | char_t * | Cílový buffer znaků. |
| charCount | int | Velikost cílového pole. |
| flush | **bool** | Pokud je true, vyčistí vnitřní stav dekodéru po výpočtu. |

### Návratová hodnota

Počet zapsaných znaků.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICUDecoder](../)
* Jmenný prostor [System::Text](../../)
* Library [Aspose.Slides](../../../)