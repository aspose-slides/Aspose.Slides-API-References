---
title: GetCharCount()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca liczbę znaków potrzebnych do zdekodowania bufora.
type: docs
weight: 40
url: /pl/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metoda

Zwraca liczbę znaków potrzebnych do zdekodowania bufora.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| index | int | [Buffer](../../../system/buffer/) przesunięcie. |
| count | int | Liczba bajtów do dekodowania. |

### Wartość zwracana

Liczba znaków wymagana do zdekodowania bufora.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) metoda

Zwraca liczbę znaków potrzebnych do zdekodowania bufora.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| index | int | [Buffer](../../../system/buffer/) przesunięcie. |
| count | int | Liczba bajtów do dekodowania. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniu. |

### Wartość zwracana

Liczba znaków wymagana do zdekodowania bufora.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) metoda

Zwraca liczbę znaków potrzebnych do zdekodowania bufora.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty do dekodowania. |
| count | int | Liczba bajtów do dekodowania. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniu. |

### Wartość zwracana

Liczba znaków wymagana do zdekodowania bufora.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICUDecoder](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)