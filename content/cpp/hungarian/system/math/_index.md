---
title: Math
second_title: Aspose.Slides for C++ API-referencia
description: Matematikai függvényeket tartalmaz. Ez egy statikus típus, amely nem rendelkezik példányosítható szolgáltatáskkal. Soha ne hozzon létre példányt ebből semmilyen módon.
type: docs
weight: 1782
url: /hu/system/math/
---
## Matematikai struktúra

Tartalmaz matematikai függvényeket. Ez egy statikus típus, amely nem rendelkezik példányosítható szolgáltatásokkal. Soha ne hozzon létre példányokat ebből semmilyen módon.

```cpp
class Math
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static T [Abs](./abs/)(T) | Visszaadja a megadott érték abszolút értékét. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Visszaadja a megadott [Decimal](../decimal/) objektum által képviselt érték abszolút értékét. |
| static **double** [Acos](./acos/)(**double**) | Kiszámítja a megadott érték arkusz koszinusát. |
| static **double** [Asin](./asin/)(**double**) | Kiszámítja a megadott érték arkusz szinuszát. |
| static **double** [Atan](./atan/)(**double**) | Kiszámítja a megadott érték arkusz tangensát. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Kiszámítja a megadott értékek arányának arkusz tangensát. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | Visszaadja két 32 bites egész szám teljes szorzatát. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Visszaadja a legkisebb egész értéket, amely nagyobb vagy egyenlő a megadott értéknél. |
| static **double** [Ceiling](./ceiling/)(**double**) | Visszaadja a legkisebb egész értéket, amely nagyobb vagy egyenlő a megadott értéknél. |
| static **double** [Cos](./cos/)(**double**) | Kiszámítja a megadott érték koszinusát. |
| static **double** [Cosh](./cosh/)(**double**) | Kiszámítja a megadott érték hiperbolikus koszinusát. |
| static int [DivRem](./divrem/)(int, int, int\&) | Kiszámítja két 32 bites egész szám hányadosát és a maradékot. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | Kiszámítja két 64 bites egész szám hányadosát és a maradékot. |
| static **double** [Exp](./exp/)(**double**) | Visszaadja az e állandó megadott hatványra emelt értékét. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Visszaadja a legnagyobb egész értéket, amely kisebb vagy egyenlő a megadott értéknél. |
| static **double** [Floor](./floor/)(**double**) | Visszaadja a legnagyobb egész értéket, amely kisebb vagy egyenlő a megadott értéknél. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Visszaadja a maradékot, amely egy megadott szám egy másik megadott számmal való osztásakor keletkezik. |
| static **double** [Log](./log/)(**double**) | Visszaadja a megadott érték természetes logaritmusát. |
| static **double** [Log](./log/)(**double**, **double**) | Visszaadja a megadott érték logaritmusát a megadott alapon. |
| static **double** [Log10](./log10/)(**double**) | Visszaadja a megadott érték 10-es alapú logaritmusát. |
| static auto [Max](./max/)(T0, T1) | Visszaadja a megadott két numerikus érték közül a legnagyobbat. |
| static T0 [Max](./max/)(T0, T1) | Visszaadja a megadott két numerikus érték közül a legnagyobbat. |
| **float** [Max_](./max_/)(**float**, **float**) | Visszaadja a megadott két egyszeres pontosságú lebegőpontos érték közül a legnagyobbat. |
| **double** [Max_](./max_/)(**double**, **double**) | Visszaadja a megadott két dupla pontosságú lebegőpontos érték közül a legnagyobbat. |
| static auto [Min](./min/)(T0, T1) | Visszaadja a megadott két numerikus érték közül a legkisebbet. |
| static T0 [Min](./min/)(T0, T1) | Visszaadja a megadott két numerikus érték közül a legkisebbet. |
| **float** [Min_](./min_/)(**float**, **float**) | Visszaadja a megadott két egyszeres pontosságú lebegőpontos érték közül a legkisebbet. |
| **double** [Min_](./min_/)(**double**, **double**) | Visszaadja a megadott két dupla pontosságú lebegőpontos érték közül a legkisebbet. |
| static T [Modulus](./modulus/)(T, T) | Kiszámítja a maradékot, amely egy megadott érték egy másik megadott értékkel való osztásakor keletkezik. |
| static **double** [Pow](./pow/)(**double**, **double**) | Visszaadja a megadott értéket a megadott hatványra emelve. |
| static **double** [Round](./round/)(**double**) | Kerekíti a megadott értéket a legközelebbi egész értékre. |
| static **double** [Round](./round/)(**double**, int) | Kerekíti a megadott értéket a megadott számú tizedesjegyű legközelebbi értékre. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Kerekíti a megadott értéket a legközelebbi egész számra. Egy paraméter meghatározza a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Kerekíti a megadott értéket a megadott számú tizedesjegyű legközelebbi értékre. Egy paraméter meghatározza a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Kerekíti a megadott értéket a legközelebbi egész értékre. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Kerekíti a megadott értéket a megadott számú tizedesjegyű legközelebbi értékre. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Kerekíti a megadott értéket a legközelebbi egész számra. Egy paraméter meghatározza a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Kerekíti a megadott értéket a megadott számú tizedesjegyű legközelebbi értékre. Egy paraméter meghatározza a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Meghatározza a megadott előjeles egész érték előjelét. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Meghatározza a megadott lebegőpontos érték előjelét. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Meghatározza a megadott decimális érték előjelét. |
| static **double** [Sin](./sin/)(**double**) | Kiszámítja a megadott érték szinuszát. |
| static **double** [Sinh](./sinh/)(**double**) | Kiszámítja a megadott érték hiperbolikus szinuszát. |
| static **double** [Sqrt](./sqrt/)(**double**) | Visszaadja a megadott érték négyzetgyökét. |
| static **double** [Tan](./tan/)(**double**) | Kiszámítja a megadott érték tangensét. |
| static **double** [Tanh](./tanh/)(**double**) | Kiszámítja a megadott érték hiperbolikus tangensét. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Visszaadja a(z) [Decimal](../decimal/) objektumot, amely egy olyan értéket reprezentál, amelynek egész része megegyezik a megadott [Decimal](../decimal/) objektummal reprezentált érték egész részével, miután az összes törtrész el lett dobva. |
| static **double** [Truncate](./truncate/)(**double**) | Visszaadja a dupla pontosságú lebegőpontos értéket, amelynek egész része megegyezik a megadott érték egész részével, miután az összes törtrész el lett dobva. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [E](./e/) | A természetes logaritmus alapja. |
| static [NaN](./nan/) | Nem-szám (NaN) értéket képvisel. |
| static [NegativeInfinity](./negativeinfinity/) | Negatív végtelent képvisel. |
| static [PI](./pi/) | A Pi (π) állandó. |
| static [PositiveInfinity](./positiveinfinity/) | Pozitív végtelent képvisel. |

## Megjegyzések



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Kiírja a abszolút értékeket.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // Kiírja a PI/2 szinuszát és a PI koszinuszát.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
Ez a kódpélda a következő kimenetet állítja elő:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## Kapcsolódó

* Namespace [System](../)
* Library [Aspose.Slides](../../)