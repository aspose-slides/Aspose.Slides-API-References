---
title: GetCharCount()
second_title: Odwołanie API Aspose.Slides dla C++
description: Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów.
type: docs
weight: 261
url: /pl/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| index | int | Początek fragmentu. |
| count | int | Rozmiar fragmentu. |

### Wartość zwracana

Liczba znaków.

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) method


Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |

### Wartość zwracana

Liczba znaków.

## Encoding::GetCharCount(const uint8_t *, int) method


Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty do dekodowania. |
| count | int | Liczba bajtów. |

### Wartość zwracana

Liczba znaków.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Encoding](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)