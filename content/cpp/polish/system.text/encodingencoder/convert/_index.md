---
title: Convert()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Konwertuje znaki na bajty.
type: docs
weight: 1
url: /pl/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int&, int&, bool&) metoda


Konwertuje znaki na bajty.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | const char_t * | Znaki do zakodowania. |
| charCount | int | Rozmiar bufora wejściowego. |
| bytes | **uint8_t** * | Bufor docelowy bajtów. |
| byteCount | int | Rozmiar docelowej tablicy. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan enkodera po obliczeniu. |
| charsUsed | int& | Referencja do zmiennej przechowującej liczbę odczytanych znaków. |
| bytesUsed | int& | Referencja do zmiennej przechowującej liczbę zapisanych bajtów. |
| completed | **bool**& | Referencja do zmiennej, która zostanie ustawiona na true, jeśli bufor wejściowy zostanie wyczerpany, oraz na false w przeciwnym razie. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int&, int&, bool&) metoda


Konwertuje znaki na bajty.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaki do zakodowania. |
| charIndex | int | Przesunięcie bufora wejściowego. |
| charCount | int | Rozmiar bufora wejściowego. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor docelowy bajtów. |
| byteIndex | int | Przesunięcie docelowej tablicy. |
| byteCount | int | Rozmiar docelowej tablicy. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan enkodera po obliczeniu. |
| charsUsed | int& | Referencja do zmiennej przechowującej liczbę odczytanych znaków. |
| bytesUsed | int& | Referencja do zmiennej przechowującej liczbę zapisanych bajtów. |
| completed | **bool**& | Referencja do zmiennej, która zostanie ustawiona na true, jeśli bufor wejściowy zostanie wyczerpany, oraz na false w przeciwnym razie. |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [EncodingEncoder](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)