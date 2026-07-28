---
title: Math
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Zawiera funkcje matematyczne. Jest to typ statyczny bez usług instancji. Nie powinieneś nigdy tworzyć jego instancji w żaden sposób.
type: docs
weight: 1782
url: /pl/system/math/
---
## Math struct

Zawiera funkcje matematyczne. Jest to typ statyczny bez usług instancji. Nie powinieneś nigdy tworzyć jego instancji w żaden sposób.

```cpp
class Math
```

## Metody

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | Zwraca wartość bezwzględną podanej wartości. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Zwraca wartość bezwzględną wartości reprezentowanej przez określony obiekt [Decimal](../decimal/). |
| static **double** [Acos](./acos/)(**double**) | Oblicza arcus cosinus podanej wartości. |
| static **double** [Asin](./asin/)(**double**) | Oblicza arcus sinus podanej wartości. |
| static **double** [Atan](./atan/)(**double**) | Oblicza arcus tangens podanej wartości. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Oblicza arcus tangens stosunku podanych wartości. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | Zwraca pełny iloczyn dwóch 32-bitowych liczb całkowitych. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Zwraca najmniejszą wartość całkowitą, która jest większa lub równa podanej wartości. |
| static **double** [Ceiling](./ceiling/)(**double**) | Zwraca najmniejszą wartość całkowitą, która jest większa lub równa podanej wartości. |
| static **double** [Cos](./cos/)(**double**) | Oblicza cosinus podanej wartości. |
| static **double** [Cosh](./cosh/)(**double**) | Oblicza cosinus hiperboliczny podanej wartości. |
| static int [DivRem](./divrem/)(int, int, int\&) | Oblicza iloraz dwóch 32-bitowych liczb całkowitych oraz resztę. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | Oblicza iloraz dwóch 64-bitowych liczb całkowitych oraz resztę. |
| static **double** [Exp](./exp/)(**double**) | Zwraca stałą e podniesioną do podanej potęgi. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Zwraca największą wartość całkowitą, która jest mniejsza lub równa podanej wartości. |
| static **double** [Floor](./floor/)(**double**) | Zwraca największą wartość całkowitą, która jest mniejsza lub równa podanej wartości. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Zwraca resztę z dzielenia podanej liczby przez inną podaną liczbę. |
| static **double** [Log](./log/)(**double**) | Zwraca logarytm naturalny podanej wartości. |
| static **double** [Log](./log/)(**double**, **double**) | Zwraca logarytm podanej wartości w podanej podstawie. |
| static **double** [Log10](./log10/)(**double**) | Zwraca logarytm dziesiętny podanej wartości. |
| static auto [Max](./max/)(T0, T1) | Zwraca największą z dwóch podanych wartości numerycznych. |
| static T0 [Max](./max/)(T0, T1) | Zwraca największą z dwóch podanych wartości numerycznych. |
| **float** [Max_](./max_/)(**float**, **float**) | Zwraca największą wartość zmiennoprzecinkową pojedynczej precyzji spośród dwóch podanych. |
| **double** [Max_](./max_/)(**double**, **double**) | Zwraca największą wartość zmiennoprzecinkową podwójnej precyzji spośród dwóch podanych. |
| static auto [Min](./min/)(T0, T1) | Zwraca najmniejszą z dwóch podanych wartości numerycznych. |
| static T0 [Min](./min/)(T0, T1) | Zwraca najmniejszą z dwóch podanych wartości numerycznych. |
| **float** [Min_](./min_/)(**float**, **float**) | Zwraca najmniejszą wartość zmiennoprzecinkową pojedynczej precyzji spośród dwóch podanych. |
| **double** [Min_](./min_/)(**double**, **double**) | Zwraca najmniejszą wartość zmiennoprzecinkową podwójnej precyzji spośród dwóch podanych. |
| static T [Modulus](./modulus/)(T, T) | Oblicza resztę z dzielenia jednej podanej wartości przez inną podaną wartość. |
| static **double** [Pow](./pow/)(**double**, **double**) | Zwraca podaną wartość podniesioną do podanej potęgi. |
| static **double** [Round](./round/)(**double**) | Zaokrągla podaną wartość do najbliższej wartości całkowitej. |
| static **double** [Round](./round/)(**double**, int) | Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr po przecinku. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Zaokrągla podaną wartość do najbliższej liczby całkowitej. Parametr określa zachowanie funkcji, jeśli podana wartość jest tak samo bliska dwóm najbliższym liczbom. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr po przecinku. Parametr określa zachowanie funkcji, jeśli podana wartość jest tak samo bliska dwóm najbliższym liczbom. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Zaokrągla podaną wartość do najbliższej wartości całkowitej. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr po przecinku. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Zaokrągla podaną wartość do najbliższej liczby całkowitej. Parametr określa zachowanie funkcji, jeśli podana wartość jest tak samo bliska dwóm najbliższym liczbom. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr po przecinku. Parametr określa zachowanie funkcji, jeśli podana wartość jest tak samo bliska dwóm najbliższym liczbom. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Określa znak podanej podpisanej wartości całkowitej. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Określa znak podanej wartości zmiennoprzecinkowej. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Określa znak podanej wartości dziesiętnej. |
| static **double** [Sin](./sin/)(**double**) | Oblicza sinus podanej wartości. |
| static **double** [Sinh](./sinh/)(**double**) | Oblicza sinus hiperboliczny podanej wartości. |
| static **double** [Sqrt](./sqrt/)(**double**) | Zwraca pierwiastek kwadratowy podanej wartości. |
| static **double** [Tan](./tan/)(**double**) | Oblicza tangens podanej wartości. |
| static **double** [Tanh](./tanh/)(**double**) | Oblicza tangens hiperboliczny podanej wartości. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Zwraca obiekt [Decimal](../decimal/) reprezentujący wartość, której część całkowita jest równa części całkowitej wartości reprezentowanej przez określony obiekt [Decimal](../decimal/), przy czym wszystkie cyfry ułamkowe są odrzucone. |
| static **double** [Truncate](./truncate/)(**double**) | Zwraca wartość zmiennoprzecinkową podwójnej precyzji, której część całkowita jest równa części całkowitej podanej wartości, a wszystkie cyfry ułamkowe są odrzucone. |

## Pola

| Field | Description |
| --- | --- |
| static [E](./e/) | Podstawa logarytmu naturalnego. |
| static [NaN](./nan/) | Reprezentuje wartość nie-liczbową (NaN). |
| static [NegativeInfinity](./negativeinfinity/) | Reprezentuje minus nieskończoność. |
| static [PI](./pi/) | Stała liczby Pi. |
| static [PositiveInfinity](./positiveinfinity/) | Reprezentuje dodatnią nieskończoność. |

## Uwagi



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Wypisz wartości bezwzględne.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // Wypisz sinus PI/2 oraz cosinus PI.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)