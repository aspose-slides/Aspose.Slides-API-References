---
title: MathF
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene funzioni matematiche per valori a virgola mobile a precisione singola. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 1795
url: /it/system/mathf/
---
## MathF struct

Contiene funzioni matematiche per valori a virgola mobile a precisione singola. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class MathF
```

## Metodi

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | Restituisce il valore assoluto del valore specificato. |
| static **float** [Acos](./acos/)(**float**) | Calcola l'arcoseno del valore specificato. |
| static **float** [Asin](./asin/)(**float**) | Calcola l'arcseno del valore specificato. |
| static **float** [Atan](./atan/)(**float**) | Calcola l'arctangente del valore specificato. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Calcola l'arctangente del rapporto dei valori specificati. |
| static **float** [Ceiling](./ceiling/)(**float**) | Restituisce il più piccolo valore intero maggiore o uguale al valore specificato. |
| static **float** [Cos](./cos/)(**float**) | Calcola il coseno del valore specificato. |
| static **float** [Cosh](./cosh/)(**float**) | Calcola il coseno iperbolico del valore specificato. |
| static **float** [Exp](./exp/)(**float**) | Restituisce la costante e elevata alla potenza specificata. |
| static **float** [Floor](./floor/)(**float**) | Restituisce il più grande valore intero minore o uguale al valore specificato. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Restituisce il resto risultante dalla divisione di un numero specificato per un altro numero specificato. |
| static **float** [Log](./log/)(**float**) | Restituisce il logaritmo naturale del valore specificato. |
| static **float** [Log](./log/)(**float**, **float**) | Restituisce il logaritmo del valore specificato nella base specificata. |
| static **float** [Log10](./log10/)(**float**) | Restituisce il logaritmo in base 10 del valore specificato. |
| static **float** [Pow](./pow/)(**float**, **float**) | Restituisce il valore specificato elevato alla potenza specificata. |
| static **float** [Round](./round/)(**float**) | Arrotonda il valore specificato al valore intero più vicino. |
| static **float** [Round](./round/)(**float**, int) | Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre frazionarie. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Arrotonda il valore specificato al numero intero più vicino. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due numeri più prossimi. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre frazionarie. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due numeri più prossimi. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre frazionarie. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due numeri più prossimi. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina il segno del valore intero con segno specificato. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina il segno del valore a virgola mobile specificato. |
| static **float** [Sin](./sin/)(**float**) | Calcola il seno del valore specificato. |
| static **float** [Sinh](./sinh/)(**float**) | Calcola il seno iperbolico del valore specificato. |
| static **float** [Sqrt](./sqrt/)(**float**) | Restituisce la radice quadrata del valore specificato. |
| static **float** [Tan](./tan/)(**float**) | Calcola la tangente del valore specificato. |
| static **float** [Tanh](./tanh/)(**float**) | Calcola la tangente iperbolica del valore specificato. |
| static **float** [Truncate](./truncate/)(**float**) | Restituisce un valore a virgola mobile a precisione float che ha la parte intera uguale a quella del valore specificato, con tutte le cifre frazionarie scartate. |

## Campi

| Field | Description |
| --- | --- |
| static [E](./e/) | Base del logaritmo naturale. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | La costante numerica Pi. |
| static [Tau](./tau/) | Valore di Tau. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)