---
title: GetBytes()
second_title: Aspose.Slides dla C++ Referencja API
description: Uzyskaj bajty powstałe w wyniku kodowania bufora.
type: docs
weight: 53
url: /pl/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) metoda


Uzyskaj bajty powstałe w wyniku kodowania bufora.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Znaki do zakodowania. |
| charIndex | int | Offset tablicy źródłowej. |
| charCount | int | Długość podtablicy źródłowej. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor bajtów docelowych. |
| byteIndex | int | Offset bufora docelowego. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan enkodera po obliczeniach. |

### Wartość zwracana

Liczba zapisanych bajtów.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) metoda


Uzyskaj bajty powstałe w wyniku kodowania bufora.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| chars | const char_t * | Znaki do zakodowania. |
| charCount | int | Długość tablicy źródłowej. |
| bytes | **uint8_t** * | Bufor bajtów docelowych. |
| byteCount | int | Rozmiar bufora docelowego. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan enkodera po obliczeniach. |

### Wartość zwracana

Liczba zapisanych bajtów.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Encoder](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)