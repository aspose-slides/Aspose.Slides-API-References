---
title: Math
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene funzioni matematiche. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 1782
url: /it/system/math/
---
## Math struct

Contiene funzioni matematiche. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class Math
```

## Methods

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | Restituisce il valore assoluto del valore specificato. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Restituisce il valore assoluto di un valore rappresentato dall'oggetto [Decimal](../decimal/) specificato. |
| static **double** [Acos](./acos/)(**double**) | Calcola l'arccoseno del valore specificato. |
| static **double** [Asin](./asin/)(**double**) | Calcola l'arcseno del valore specificato. |
| static **double** [Atan](./atan/)(**double**) | Calcola l'arctangente del valore specificato. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Calcola l'arctangente del rapporto dei valori specificati. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | Restituisce il prodotto completo di due interi a 32 bit. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Restituisce il valore intero più piccolo che è maggiore o uguale al valore specificato. |
| static **double** [Ceiling](./ceiling/)(**double**) | Restituisce il valore intero più piccolo che è maggiore o uguale al valore specificato. |
| static **double** [Cos](./cos/)(**double**) | Calcola il coseno del valore specificato. |
| static **double** [Cosh](./cosh/)(**double**) | Calcola il coseno iperbolico del valore specificato. |
| static int [DivRem](./divrem/)(int, int, int\&) | Calcola il quoziente di due interi a 32 bit e il resto. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | Calcola il quoziente di due interi a 64 bit e il resto. |
| static **double** [Exp](./exp/)(**double**) | Restituisce la costante e elevata alla potenza specificata. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Restituisce il valore intero più grande che è minore o uguale al valore specificato. |
| static **double** [Floor](./floor/)(**double**) | Restituisce il valore intero più grande che è minore o uguale al valore specificato. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Restituisce il resto risultante dalla divisione di un numero specificato per un altro numero specificato. |
| static **double** [Log](./log/)(**double**) | Restituisce il logaritmo naturale del valore specificato. |
| static **double** [Log](./log/)(**double**, **double**) | Restituisce il logaritmo del valore specificato nella base specificata. |
| static **double** [Log10](./log10/)(**double**) | Restituisce il logaritmo in base 10 del valore specificato. |
| static auto [Max](./max/)(T0, T1) | Restituisce il valore più grande tra i due valori numerici specificati. |
| static T0 [Max](./max/)(T0, T1) | Restituisce il valore più grande tra i due valori numerici specificati. |
| **float** [Max_](./max_/)(**float**, **float**) | Restituisce il valore a virgola mobile a precisione singola più grande tra i due specificati. |
| **double** [Max_](./max_/)(**double**, **double**) | Restituisce il valore a virgola mobile a doppia precisione più grande tra i due specificati. |
| static auto [Min](./min/)(T0, T1) | Restituisce il valore più piccolo tra i due valori numerici specificati. |
| static T0 [Min](./min/)(T0, T1) | Restituisce il valore più piccolo tra i due valori numerici specificati. |
| **float** [Min_](./min_/)(**float**, **float**) | Restituisce il valore a virgola mobile a precisione singola più piccolo tra i due specificati. |
| **double** [Min_](./min_/)(**double**, **double**) | Restituisce il valore a virgola mobile a doppia precisione più piccolo tra i due specificati. |
| static T [Modulus](./modulus/)(T, T) | Calcola il resto risultante dalla divisione di un valore specificato per un altro valore specificato. |
| static **double** [Pow](./pow/)(**double**, **double**) | Restituisce il valore specificato elevato alla potenza specificata. |
| static **double** [Round](./round/)(**double**) | Arrotonda il valore specificato al valore intero più vicino. |
| static **double** [Round](./round/)(**double**, int) | Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre frazionali. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Arrotonda il valore specificato al numero intero più vicino. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due numeri più vicini. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre frazionali. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due numeri più vicini. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Arrotonda il valore specificato al valore intero più vicino. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre frazionali. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Arrotonda il valore specificato al numero intero più vicino. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due numeri più vicini. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre frazionali. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due numeri più vicini. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina il segno del valore intero con segno specificato. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina il segno del valore a virgola mobile specificato. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Determina il segno del valore decimale specificato. |
| static **double** [Sin](./sin/)(**double**) | Calcola il seno del valore specificato. |
| static **double** [Sinh](./sinh/)(**double**) | Calcola il seno iperbolico del valore specificato. |
| static **double** [Sqrt](./sqrt/)(**double**) | Restituisce la radice quadrata del valore specificato. |
| static **double** [Tan](./tan/)(**double**) | Calcola la tangente del valore specificato. |
| static **double** [Tanh](./tanh/)(**double**) | Calcola la tangente iperbolica del valore specificato. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Restituisce l'oggetto [Decimal](../decimal/) che rappresenta un valore il cui parte intera è uguale a quella del valore rappresentato dall'oggetto [Decimal](../decimal/) specificato, con tutte le cifre frazionali scartate. |
| static **double** [Truncate](./truncate/)(**double**) | Restituisce un valore a virgola mobile a doppia precisione il cui parte intera è uguale a quella del valore specificato, con tutte le cifre frazionali scartate. |

## Fields

| Field | Description |
| --- | --- |
| static [E](./e/) | Base del logaritmo naturale. |
| static [NaN](./nan/) | Rappresenta un valore non numerico. |
| static [NegativeInfinity](./negativeinfinity/) | Rappresenta l'infinito negativo. |
| static [PI](./pi/) | La costante Pi. |
| static [PositiveInfinity](./positiveinfinity/) | Rappresenta l'infinito positivo. |

## Remarks



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Stampa i valori assoluti.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // Stampa il seno di PI/2 e il coseno di PI.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## See Also

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)