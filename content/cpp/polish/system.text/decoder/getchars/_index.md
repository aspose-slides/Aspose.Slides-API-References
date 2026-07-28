---
title: GetChars()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera znaki powstałe w wyniku dekodowania bufora.
type: docs
weight: 53
url: /pl/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metoda

Pobiera znaki powstałe w wyniku dekodowania bufora.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| byteIndex | int | Offset bufora wejściowego. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Bufor znaków docelowych. |
| charIndex | int | Offset tablicy docelowej. |

### Wartość zwracana

Liczba zapisanych znaków.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) metoda

Pobiera znaki powstałe w wyniku dekodowania bufora.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| byteIndex | int | Offset bufora wejściowego. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Bufor znaków docelowych. |
| charIndex | int | Offset tablicy docelowej. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniach. |

### Wartość zwracana

Liczba zapisanych znaków.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) metoda

Pobiera znaki powstałe w wyniku dekodowania bufora.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty do dekodowania. |
| byteCount | int | Rozmiar bufora wejściowego. |
| chars | char_t * | Bufor znaków docelowych. |
| charCount | int | Rozmiar tablicy docelowej. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniach. |

### Wartość zwracana

Liczba zapisanych znaków.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)