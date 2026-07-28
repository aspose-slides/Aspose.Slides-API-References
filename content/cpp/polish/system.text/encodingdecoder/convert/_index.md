---
title: Convert()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Konwertuje bajty na znaki.
type: docs
weight: 1
url: /pl/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int&, int&, bool&) metoda

Konwertuje bajty na znaki.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty do dekodowania. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | char_t * | Docelowy bufor znaków. |
| charCount | int | Rozmiar docelowej tablicy. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniu. |
| bytesUsed | int\& | Referencja do zmiennej, w której przechowywana jest liczba odczytanych bajtów. |
| charsUsed | int\& | Referencja do zmiennej, w której przechowywana jest liczba zapisanych znaków. |
| completed | **bool**\& | Referencja do zmiennej, która ma być ustawiona na true, jeśli bufor wejściowy został wyczerpany, oraz na false w przeciwnym przypadku. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int&, int&, bool&) metoda

Konwertuje bajty na znaki.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| byteIndex | int | Przesunięcie bufora wejściowego. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Docelowy bufor znaków. |
| charIndex | int | Przesunięcie tablicy docelowej. |
| charCount | int | Rozmiar tablicy docelowej. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniu. |
| bytesUsed | int\& | Referencja do zmiennej, w której przechowywana jest liczba odczytanych bajtów. |
| charsUsed | int\& | Referencja do zmiennej, w której przechowywana jest liczba zapisanych znaków. |
| completed | **bool**\& | Referencja do zmiennej, która ma być ustawiona na true, jeśli bufor wejściowy został wyczerpany, oraz na false w przeciwnym przypadku. |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [EncodingDecoder](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)