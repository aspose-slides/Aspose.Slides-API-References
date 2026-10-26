---
title: ToUInt32()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Konwertuje cztery bajty z określonej tablicy, zaczynając od podanego indeksu, na wartość 32-bitową bez znaku.
type: docs
weight: 105
url: /pl/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) metoda

Konwertuje cztery bajty z określonej tablicy, zaczynając od podanego indeksu, na wartość całkowitą 32-bitową bez znaku.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) który zawiera bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od której rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

Wartość całkowita 32-bitowa bez znaku uzyskana w wyniku konwersji

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metoda

Konwertuje cztery bajty z określonej tablicy, zaczynając od podanego indeksu, na wartość całkowitą 32-bitową bez znaku.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, który zawiera bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od której rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

Wartość całkowita 32-bitowa bez znaku uzyskana w wyniku konwersji

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)