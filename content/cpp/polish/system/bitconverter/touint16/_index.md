---
title: ToUInt16()
second_title: Aspose.Slides for C++ – odniesienie API
description: Konwertuje dwa bajty z podanej tablicy zaczynając od określonego indeksu na wartość bez znaku 16-bitową.
type: docs
weight: 92
url: /pl/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) metoda

Konwertuje dwa bajty z podanej tablicy rozpoczynając od określonego indeksu na wartość bez znaku 16-bitową.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

Wartość bez znaku 16-bitowa będąca wynikiem konwersji

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) metoda

Konwertuje dwa bajty z podanej tablicy rozpoczynając od określonego indeksu na wartość bez znaku 16-bitową.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

Wartość bez znaku 16-bitowa będąca wynikiem konwersji

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [BitConverter](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)