---
title: ToInt64()
second_title: Aspose.Slides dla C++ - referencja API
description: Konwertuje osiem bajtów z określonej tablicy zaczynając od podanego indeksu na 64-bitową wartość całkowitą.
type: docs
weight: 79
url: /pl/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) metoda


Konwertuje osiem bajtów z określonej tablicy zaczynając od podanego indeksu na wartość całkowitą 64-bitową.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) który zawiera bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego należy rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

64-bitowa wartość całkowita uzyskana w wyniku konwersji

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metoda


Konwertuje osiem bajtów z określonej tablicy zaczynając od podanego indeksu na wartość całkowitą 64-bitową.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView który zawiera bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego należy rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

64-bitowa wartość całkowita uzyskana w wyniku konwersji

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [BitConverter](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)