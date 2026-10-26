---
title: Convert()
second_title: Aspose.Slides dla C++ – Referencja API
description: Konwertuje znaki na bajty.
type: docs
weight: 79
url: /pl/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) metoda

Konwertuje znaki na bajty.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaki do zakodowania. |
| charIndex | int | Przesunięcie bufora wejściowego. |
| charCount | int | Rozmiar bufora wejściowego. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor docelowy bajtów. |
| byteIndex | int | Przesunięcie tablicy docelowej. |
| byteCount | int | Rozmiar tablicy docelowej. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan enkodera po obliczeniu. |
| charsUsed | int\& | Referencja do zmiennej przechowującej liczbę odczytanych znaków. |
| bytesUsed | int\& | Referencja do zmiennej przechowującej liczbę zapisanych bajtów. |
| completed | **bool**\& | Referencja do zmiennej, która ma być ustawiona na true, jeśli bufor wejściowy został wyczerpany, oraz na false w przeciwnym razie. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) metoda

Konwertuje znaki na bajty.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Znaki do zakodowania. |
| charCount | int | Rozmiar bufora wejściowego. |
| bytes | **uint8_t** * | Bufor docelowy bajtów. |
| byteCount | int | Rozmiar tablicy docelowej. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan enkodera po obliczeniu. |
| charsUsed | int\& | Referencja do zmiennej przechowującej liczbę odczytanych znaków. |
| bytesUsed | int\& | Referencja do zmiennej przechowującej liczbę zapisanych bajtów. |
| completed | **bool**\& | Referencja do zmiennej, która ma być ustawiona na true, jeśli bufor wejściowy został wyczerpany, oraz na false w przeciwnym razie. |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Encoder](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)