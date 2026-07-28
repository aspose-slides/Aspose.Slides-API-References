---
title: GetChars()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Pobiera znaki powstałe w wyniku dekodowania bufora.
type: docs
weight: 53
url: /pl/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metoda


Pobiera znaki powstałe w wyniku dekodowania bufora.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| byteIndex | int | Przesunięcie bufora wejściowego. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Bufor znaków docelowy. |
| charIndex | int | Przesunięcie tablicy docelowej. |

### Wartość zwracana

Liczba zapisanych znaków.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) metoda


Pobiera znaki powstałe w wyniku dekodowania bufora.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| byteIndex | int | Przesunięcie bufora wejściowego. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Bufor znaków docelowy. |
| charIndex | int | Przesunięcie tablicy docelowej. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniach. |

### Wartość zwracana

Liczba zapisanych znaków.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) metoda


Pobiera znaki powstałe w wyniku dekodowania bufora.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty do dekodowania. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | char_t * | Bufor znaków docelowy. |
| charCount | int | Rozmiar tablicy docelowej. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniach. |

### Wartość zwracana

Liczba zapisanych znaków.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICUDecoder](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)