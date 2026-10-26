---
title: Math
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Obsahuje matematické funkce. Jedná se o statický typ bez služeb instance. Nikdy byste neměli vytvářet jeho instance žádným způsobem.
type: docs
weight: 1782
url: /cs/system/math/
---
## Math struktura

Obsahuje matematické funkce. Jedná se o statický typ bez služeb instance. Nikdy byste neměli vytvářet jeho instance žádným způsobem.

```cpp
class Math
```

## Metody

| Metoda | Popis |
| --- | --- |
| static T [Abs](./abs/)(T) | Vrací absolutní hodnotu zadané hodnoty. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Vrací absolutní hodnotu hodnoty reprezentované zadaným objektem [Decimal](../decimal/). |
| static **double** [Acos](./acos/)(**double**) | Vypočítá arkuskosinus zadané hodnoty. |
| static **double** [Asin](./asin/)(**double**) | Vypočítá arkussinus zadané hodnoty. |
| static **double** [Atan](./atan/)(**double**) | Vypočítá arkustangens zadané hodnoty. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Vypočítá arkustangens poměru zadaných hodnot. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | Vrací plný součin dvou 32bitových celých čísel. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Vrací nejmenší celočíselnou hodnotu, která je větší nebo rovna zadané hodnotě. |
| static **double** [Ceiling](./ceiling/)(**double**) | Vrací nejmenší celočíselnou hodnotu, která je větší nebo rovna zadané hodnotě. |
| static **double** [Cos](./cos/)(**double**) | Vypočítá kosinus zadané hodnoty. |
| static **double** [Cosh](./cosh/)(**double**) | Vypočítá hyperbolický kosinus zadané hodnoty. |
| static int [DivRem](./divrem/)(int, int, int\&) | Vypočítá podíl dvou 32bitových celých čísel a zbytek. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | Vypočítá podíl dvou 64bitových celých čísel a zbytek. |
| static **double** [Exp](./exp/)(**double**) | Vrací konstantu e umocněnou na zadanou mocninu. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Vrací největší celočíselnou hodnotu, která je menší nebo rovna zadané hodnotě. |
| static **double** [Floor](./floor/)(**double**) | Vrací největší celočíselnou hodnotu, která je menší nebo rovna zadané hodnotě. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Vrací zbytek vzniklý dělením zadaného čísla jiným zadaným číslem. |
| static **double** [Log](./log/)(**double**) | Vrací přirozený logaritmus zadané hodnoty. |
| static **double** [Log](./log/)(**double**, **double**) | Vrací logaritmus zadané hodnoty v zadaném základu. |
| static **double** [Log10](./log10/)(**double**) | Vrací desítkový logaritmus zadané hodnoty. |
| static auto [Max](./max/)(T0, T1) | Vrací největší hodnotu ze dvou zadaných číselných hodnot. |
| static T0 [Max](./max/)(T0, T1) | Vrací největší hodnotu ze dvou zadaných číselných hodnot. |
| **float** [Max_](./max_/)(**float**, **float**) | Vrací největší hodnotu typu float ze dvou zadaných. |
| **double** [Max_](./max_/)(**double**, **double**) | Vrací největší hodnotu typu double ze dvou zadaných. |
| static auto [Min](./min/)(T0, T1) | Vrací nejmenší hodnotu ze dvou zadaných číselných hodnot. |
| static T0 [Min](./min/)(T0, T1) | Vrací nejmenší hodnotu ze dvou zadaných číselných hodnot. |
| **float** [Min_](./min_/)(**float**, **float**) | Vrací nejmenší hodnotu typu float ze dvou zadaných. |
| **double** [Min_](./min_/)(**double**, **double**) | Vrací nejmenší hodnotu typu double ze dvou zadaných. |
| static T [Modulus](./modulus/)(T, T) | Vypočítá zbytek vzniklý dělením jedné zadané hodnoty druhou zadanou hodnotou. |
| static **double** [Pow](./pow/)(**double**, **double**) | Vrací zadanou hodnotu umocněnou na zadanou mocninu. |
| static **double** [Round](./round/)(**double**) | Zaokrouhlí zadanou hodnotu na nejbližší celočíselnou hodnotu. |
| static **double** [Round](./round/)(**double**, int) | Zaokrouhlí zadanou hodnotu na nejbližší hodnotu s určeným počtem desetinných míst. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Zaokrouhlí zadanou hodnotu na nejbližší celočíselné číslo. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Zaokrouhlí zadanou hodnotu na nejbližší hodnotu s určeným počtem desetinných míst. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Zaokrouhlí zadanou hodnotu na nejbližší celočíselnou hodnotu. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Zaokrouhlí zadanou hodnotu na nejbližší hodnotu s určeným počtem desetinných míst. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Zaokrouhlí zadanou hodnotu na nejbližší celočíselné číslo. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Zaokrouhlí zadanou hodnotu na nejbližší hodnotu s určeným počtem desetinných míst. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Určuje znaménko zadané podepsané celočíselné hodnoty. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Určuje znaménko zadané hodnoty s plovoucí desetinnou čárkou. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Určuje znaménko zadané desetinné hodnoty. |
| static **double** [Sin](./sin/)(**double**) | Vypočítá sinus zadané hodnoty. |
| static **double** [Sinh](./sinh/)(**double**) | Vypočítá hyperbolický sinus zadané hodnoty. |
| static **double** [Sqrt](./sqrt/)(**double**) | Vrací druhou odmocninu zadané hodnoty. |
| static **double** [Tan](./tan/)(**double**) | Vypočítá tangens zadané hodnoty. |
| static **double** [Tanh](./tanh/)(**double**) | Vypočítá hyperbolický tangens zadané hodnoty. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Vrací objekt [Decimal](../decimal/) představující hodnotu, jejíž celočíselná část je stejná jako celočíselná část hodnoty reprezentované zadaným objektem [Decimal](../decimal/), přičemž jsou odstraněny všechny desetinné číslice. |
| static **double** [Truncate](./truncate/)(**double**) | Vrací hodnotu typu double, jejíž celočíselná část je stejná jako celočíselná část zadané hodnoty, přičemž jsou odstraněny všechny desetinné číslice. |

## Pole

| Pole | Popis |
| --- | --- |
| static [E](./e/) | Základ přirozeného logaritmu. |
| static [NaN](./nan/) | Reprezentuje hodnotu NaN (not-a-number). |
| static [NegativeInfinity](./negativeinfinity/) | Reprezentuje zápornou nekonečno. |
| static [PI](./pi/) | Konstantа čísla Pi. |
| static [PositiveInfinity](./positiveinfinity/) | Reprezentuje kladnou nekonečno. |

## Poznámky



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Vytiskne absolutní hodnoty.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // Vytiskne sinus PI/2 a kosinus PI.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
Tento ukázkový kód produkuje následující výstup:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)