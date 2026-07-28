---
title: ToSingle()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Konwertuje cztery bajty z określonej tablicy, zaczynając od podanego indeksu, na wartość zmiennoprzecinkową pojedynczej precyzji.
type: docs
weight: 131
url: /pl/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) metoda

Konwertuje cztery bajty z określonej tablicy, zaczynając od podanego indeksu, na wartość zmiennoprzecinkową pojedynczej precyzji.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) który zawiera bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

Wartość zmiennoprzecinkowa pojedynczej precyzji otrzymana w wyniku konwersji

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) metoda

Konwertuje cztery bajty z określonej tablicy, zaczynając od podanego indeksu, na wartość zmiennoprzecinkową pojedynczej precyzji.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView który zawiera bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od którego rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

Wartość zmiennoprzecinkowa pojedynczej precyzji otrzymana w wyniku konwersji

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [BitConverter](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)