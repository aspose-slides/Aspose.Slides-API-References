---
title: ToDouble()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Konwertuje osiem bajtów z podanej tablicy, zaczynając od określonego indeksu, na wartość zmiennoprzecinkową podwójnej precyzji.
type: docs
weight: 144
url: /pl/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) metoda


Konwertuje osiem bajtów z określonej tablicy, zaczynając od określonego indeksu, na wartość zmiennoprzecinkową podwójnej precyzji.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od której rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

Wartość zmiennoprzecinkowa podwójnej precyzji uzyskana w wyniku konwersji

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) metoda


Konwertuje osiem bajtów z określonej tablicy, zaczynając od określonego indeksu, na wartość zmiennoprzecinkową podwójnej precyzji.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView zawierający bajty do konwersji |
| startIndex | int | [Index](../../index/) w tablicy, od której rozpocząć pobieranie bajtów do konwersji |

### Wartość zwracana

Wartość zmiennoprzecinkowa podwójnej precyzji uzyskana w wyniku konwersji

## Zobacz również

* Definicja typu [ArrayPtr](../../arrayptr/)
* Klasa [BitConverter](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)