---
title: Convert()
second_title: Aspose.Slides dla C++ referencja API
description: Konwertuje bajty na znaki.
type: docs
weight: 66
url: /pl/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) metoda


Konwertuje bajty na znaki.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do zdekodowania. |
| byteIndex | int | Offset bufora wejściowego. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Bufor znaków docelowy. |
| charIndex | int | Offset tablicy docelowej. |
| charCount | int | Rozmiar tablicy docelowej. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniu. |
| bytesUsed | int\& | Referencja do zmiennej przechowującej liczbę odczytanych bajtów. |
| charsUsed | int\& | Referencja do zmiennej przechowującej liczbę zapisanych znaków. |
| completed | **bool**\& | Referencja do zmiennej, która ma być ustawiona na true, jeśli bufor wejściowy został wyczerpany, oraz na false w przeciwnym razie. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) metoda


Konwertuje bajty na znaki.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty do zdekodowania. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | char_t * | Bufor znaków docelowy. |
| charCount | int | Rozmiar tablicy docelowej. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniu. |
| bytesUsed | int\& | Referencja do zmiennej przechowującej liczbę odczytanych bajtów. |
| charsUsed | int\& | Referencja do zmiennej przechowującej liczbę zapisanych znaków. |
| completed | **bool**\& | Referencja do zmiennej, która ma być ustawiona na true, jeśli bufor wejściowy został wyczerpany, oraz na false w przeciwnym razie. |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICUDecoder](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)