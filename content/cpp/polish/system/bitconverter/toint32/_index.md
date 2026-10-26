---
title: ToInt32()
second_title: Referencja API Aspose.Slides dla C++
description: Konwertuje cztery bajty z określonej tablicy, zaczynając od podanego indeksu, na wartość liczby całkowitej 32-bitowej.
type: docs
weight: 66
url: /pl/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) metoda

Konwertuje cztery bajty z określonej tablicy zaczynając od podanego indeksu na wartość liczby całkowitej 32-bitowej.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) który zawiera bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od której rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

wartość liczby całkowitej 32-bitowej uzyskana w wyniku konwersji

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metoda

Konwertuje cztery bajty z określonej tablicy zaczynając od podanego indeksu na wartość liczby całkowitej 32-bitowej.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView który zawiera bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od której rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

wartość liczby całkowitej 32-bitowej uzyskana w wyniku konwersji

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [BitConverter](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)