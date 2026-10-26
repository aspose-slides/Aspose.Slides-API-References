---
title: BitConverter
second_title: Referencja API Aspose.Slides dla C++
description: Zawiera metody, które wykonują konwersje sekwencji bajtów na typ wartości oraz odwrotnie. Jest to typ statyczny bez usług instancji. Nie należy nigdy tworzyć jego instancji w żaden sposób.
type: docs
weight: 66
url: /pl/system/bitconverter/
---
## Klasa BitConverter


Zawiera metody, które wykonują konwersje sekwencji bajtów na typ wartości oraz odwrotnie. Jest to typ statyczny bez usług instancji. Nie należy nigdy tworzyć jego instancji w żaden sposób.

```cpp
class BitConverter
```

## Metody

| Metoda | Opis |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Wskazuje kolejność bajtów bieżącej architektury. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Zwraca 64-bitową wartość całkowitą, której reprezentacja binarna jest równa reprezentacji binarnej określonej podwójnej precyzji liczby zmiennoprzecinkowej. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Konwertuje określoną wartość logiczną na tablicę bajtów. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Konwertuje określoną wartość char_t na tablicę bajtów. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Konwertuje określoną 16-bitową wartość całkowitą na tablicę bajtów. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Konwertuje określoną 32-bitową wartość całkowitą na tablicę bajtów. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Konwertuje określoną 64-bitową wartość całkowitą na tablicę bajtów. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Konwertuje określoną 16-bitową wartość całkowitą bez znaku na tablicę bajtów. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Konwertuje określoną 32-bitową wartość całkowitą bez znaku na tablicę bajtów. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Konwertuje określoną 64-bitową wartość całkowitą bez znaku na tablicę bajtów. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Konwertuje określoną jednoprzecinkową wartość zmiennoprzecinkową na tablicę bajtów. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Konwertuje określoną podwójną precyzję liczby zmiennoprzecinkowej na tablicę bajtów. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Zwraca wartość zmiennoprzecinkową podwójnej precyzji, której wartość jest równoważna podanej wartości. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konwertuje jeden bajt z określonej tablicy zaczynając od podanego indeksu na wartość logiczną. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konwertuje jeden bajt z określonej tablicy zaczynając od podanego indeksu na wartość logiczną. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konwertuje dwa bajty z określonej tablicy zaczynając od podanego indeksu na wartość char_t. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konwertuje dwa bajty z określonej tablicy zaczynając od podanego indeksu na wartość char_t. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konwertuje osiem bajtów z określonej tablicy zaczynając od podanego indeksu na wartość zmiennoprzecinkową podwójnej precyzji. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konwertuje osiem bajtów z określonej tablicy zaczynając od podanego indeksu na wartość zmiennoprzecinkową podwójnej precyzji. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konwertuje dwa bajty z określonej tablicy zaczynając od podanego indeksu na 16-bitową wartość całkowitą. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konwertuje dwa bajty z określonej tablicy zaczynając od podanego indeksu na 16-bitową wartość całkowitą. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konwertuje cztery bajty z określonej tablicy zaczynając od podanego indeksu na 32-bitową wartość całkowitą. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konwertuje cztery bajty z określonej tablicy zaczynając od podanego indeksu na 32-bitową wartość całkowitą. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konwertuje osiem bajtów z określonej tablicy zaczynając od podanego indeksu na 64-bitową wartość całkowitą. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konwertuje osiem bajtów z określonej tablicy zaczynając od podanego indeksu na 64-bitową wartość całkowitą. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konwertuje cztery bajty z określonej tablicy zaczynając od podanego indeksu na jednoprzecinkową wartość zmiennoprzecinkową. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konwertuje cztery bajty z określonej tablicy zaczynając od podanego indeksu na jednoprzecinkową wartość zmiennoprzecinkową. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Konwertuje wszystkie wartości określonej tablicy bajtów na ich szesnastkową reprezentację w postaci łańcucha znaków. Wielkość liter używanych w notacji szesnastkowej oraz separator wstawiany pomiędzy kolejnymi parami są określane za pomocą odpowiednich argumentów. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konwertuje wartości określonej tablicy bajtów na ich szesnastkową reprezentację w postaci łańcucha znaków, zaczynając od podanego indeksu. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Konwertuje zakres wartości określonej tablicy bajtów na ich szesnastkową reprezentację w postaci łańcucha znaków. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konwertuje dwa bajty z określonej tablicy zaczynając od podanego indeksu na 16-bitową wartość całkowitą bez znaku. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konwertuje dwa bajty z określonej tablicy zaczynając od podanego indeksu na 16-bitową wartość całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konwertuje cztery bajty z określonej tablicy zaczynając od podanego indeksu na 32-bitową wartość całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konwertuje cztery bajty z określonej tablicy zaczynając od podanego indeksu na 32-bitową wartość całkowitą bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konwertuje osiem bajtów z określonej tablicy zaczynając od podanego indeksu na 64-bitową wartość całkowitą bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konwertuje osiem bajtów z określonej tablicy zaczynając od podanego indeksu na 64-bitową wartość całkowitą bez znaku. |

## Pola

| Pole | Opis |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Wskazuje kolejność bajtów bieżącej architektury. true jeśli architektura jest little endian, false w przeciwnym razie. |

## Uwagi



```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // Utwórz wartości do wypisania.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Wypisz wartość i jej bajty.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Ten przykład kodu generuje następujące wyjście:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)