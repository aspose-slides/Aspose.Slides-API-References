---
title: MathF
second_title: Aspose.Slides pro C++ referenční příručka API
description: Obsahuje matematické funkce pro hodnoty s jednoduchou přesností floating-point. Jedná se o statický typ bez instančních služeb. Neměli byste jej za žádných okolností vytvářet instance.
type: docs
weight: 1795
url: /cs/system/mathf/
---
## MathF struct

Obsahuje matematické funkce pro hodnoty s jednoduchou přesností floating-point. Jedná se o statický typ bez instančních služeb. Neměli byste jej za žádných okolností vytvářet instance.

```cpp
class MathF
```

## Metody

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | Vrací absolutní hodnotu zadané hodnoty. |
| static **float** [Acos](./acos/)(**float**) | Vypočítá arkuskosinus zadané hodnoty. |
| static **float** [Asin](./asin/)(**float**) | Vypočítá arkussinus zadané hodnoty. |
| static **float** [Atan](./atan/)(**float**) | Vypočítá arkustangens zadané hodnoty. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Vypočítá arkustangens poměru zadaných hodnot. |
| static **float** [Ceiling](./ceiling/)(**float**) | Vrací nejmenší celočíselnou hodnotu, která je větší nebo rovna zadané hodnotě. |
| static **float** [Cos](./cos/)(**float**) | Vypočítá kosinus zadané hodnoty. |
| static **float** [Cosh](./cosh/)(**float**) | Vypočítá hyperbolický kosinus zadané hodnoty. |
| static **float** [Exp](./exp/)(**float**) | Vrací konstantu e umocněnou na zadanou mocninu. |
| static **float** [Floor](./floor/)(**float**) | Vrací největší celočíselnou hodnotu, která je menší nebo rovna zadané hodnotě. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Vrací zbytek vzniklý dělením zadaného čísla jiným zadaným číslem. |
| static **float** [Log](./log/)(**float**) | Vrací přirozený logaritmus zadané hodnoty. |
| static **float** [Log](./log/)(**float**, **float**) | Vrací logaritmus zadané hodnoty v zadaném základu. |
| static **float** [Log10](./log10/)(**float**) | Vrací desítkový logaritmus zadané hodnoty. |
| static **float** [Pow](./pow/)(**float**, **float**) | Vrací zadanou hodnotu umocněnou na zadanou mocninu. |
| static **float** [Round](./round/)(**float**) | Zaokrouhlí zadanou hodnotu na nejbližší celočíselnou hodnotu. |
| static **float** [Round](./round/)(**float**, int) | Zaokrouhlí zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Zaokrouhlí zadanou hodnotu na nejbližší celočíselné číslo. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Zaokrouhlí zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Zaokrouhlí zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Určuje znaménko zadané podepsané celočíselné hodnoty. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Určuje znaménko zadané floating-point hodnoty. |
| static **float** [Sin](./sin/)(**float**) | Vypočítá sinus zadané hodnoty. |
| static **float** [Sinh](./sinh/)(**float**) | Vypočítá hyperbolický sinus zadané hodnoty. |
| static **float** [Sqrt](./sqrt/)(**float**) | Vrací druhou odmocninu zadané hodnoty. |
| static **float** [Tan](./tan/)(**float**) | Vypočítá tangens zadané hodnoty. |
| static **float** [Tanh](./tanh/)(**float**) | Vypočítá hyperbolický tangens zadané hodnoty. |
| static **float** [Truncate](./truncate/)(**float**) | Vrací floating-point hodnotu s přesností float, jejíž celočíselná část je rovna celočíselné části zadané hodnoty se všemi desetinnými místy zahozena. |

## Pole

| Field | Description |
| --- | --- |
| static [E](./e/) | Základ přirozeného logaritmu. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | Konstantní hodnota čísla Pi. |
| static [Tau](./tau/) | Hodnota Tau. |

## Viz také

* jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)