---
title: Convert()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Konwertuje bajty na znaki.
type: docs
weight: 79
url: /pl/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) metoda


Konwertuje bajty na znaki.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| byteIndex | int | Przesunięcie bufora wejściowego. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Bufor znaków docelowych. |
| charIndex | int | Przesunięcie tablicy docelowej. |
| charCount | int | Rozmiar tablicy docelowej. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniu. |
| bytesUsed | int\& | Referencja do zmiennej przechowującej liczbę odczytanych bajtów. |
| charsUsed | int\& | Referencja do zmiennej przechowującej liczbę zapisanych znaków. |
| completed | **bool**\& | Referencja do zmiennej, która ma być ustawiona na true, jeśli bufor wejściowy został wyczerpany, oraz na false w przeciwnym razie. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) metoda


Konwertuje bajty na znaki.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty do dekodowania. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | char_t * | Bufor znaków docelowych. |
| charCount | int | Rozmiar tablicy docelowej. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniu. |
| bytesUsed | int\& | Referencja do zmiennej przechowującej liczbę odczytanych bajtów. |
| charsUsed | int\& | Referencja do zmiennej przechowującej liczbę zapisanych znaków. |
| completed | **bool**\& | Referencja do zmiennej, która ma być ustawiona na true, jeśli bufor wejściowy został wyczerpany, oraz na false w przeciwnym razie. |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Decoder](../)
* Przestrzeń nazw [System::Text](../../)
* Library [Aspose.Slides](../../../)