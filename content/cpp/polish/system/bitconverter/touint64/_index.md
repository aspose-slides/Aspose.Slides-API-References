---
title: ToUInt64()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Konwertuje osiem bajtów z określonej tablicy zaczynając od określonego indeksu na 64-bitową liczbę całkowitą bez znaku.
type: docs
weight: 118
url: /pl/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) metoda


Konwertuje osiem bajtów z określonej tablicy zaczynając od określonego indeksu na 64-bitową liczbę całkowitą bez znaku.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

64-bitowa liczba całkowita bez znaku będąca wynikiem konwersji

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metoda


Konwertuje osiem bajtów z określonej tablicy zaczynając od określonego indeksu na 64-bitową liczbę całkowitą bez znaku.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

64-bitowa liczba całkowita bez znaku będąca wynikiem konwersji

## Zobacz także

* Definicja typu [ArrayPtr](../../arrayptr/)
* Klasa [BitConverter](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)