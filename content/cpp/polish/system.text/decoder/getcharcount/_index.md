---
title: GetCharCount()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Pobiera liczbę znaków potrzebnych do dekodowania bufora.
type: docs
weight: 40
url: /pl/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metoda

Pobiera liczbę znaków potrzebnych do dekodowania bufora.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| index | int | [Buffer](../../../system/buffer/) przesunięcie. |
| count | int | Liczba bajtów do dekodowania. |

### Wartość zwracana

Liczba znaków potrzebnych do dekodowania bufora.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) metoda

Pobiera liczbę znaków potrzebnych do dekodowania bufora.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| index | int | [Buffer](../../../system/buffer/) przesunięcie. |
| count | int | Liczba bajtów do dekodowania. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniu. |

### Wartość zwracana

Liczba znaków potrzebnych do dekodowania bufora.

## Decoder::GetCharCount(const uint8_t *, int, bool) metoda

Pobiera liczbę znaków potrzebnych do dekodowania bufora.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty do dekodowania. |
| count | int | Liczba bajtów do dekodowania. |
| flush | **bool** | Jeśli true, czyści wewnętrzny stan dekodera po obliczeniu. |

### Wartość zwracana

Liczba znaków potrzebnych do dekodowania bufora.

## Zobacz też

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [Decoder](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)