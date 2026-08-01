---
title: MathF
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat wiskundige functies voor enkelprecisie floating-point waarden. Dit is een statisch type zonder instantiediensten. Je mag nooit op welke manier dan ook instanties ervan maken.
type: docs
weight: 1795
url: /nl/system/mathf/
---
## MathF struct

Bevat wiskundige functies voor enkelprecisie floating-point waarden. Dit is een statisch type zonder instantiediensten. Je mag nooit op welke manier dan ook instanties ervan maken.

```cpp
class MathF
```

## Methodes

| Methode | Beschrijving |
| --- | --- |
| static T [Abs](./abs/)(T) | Geeft de absolute waarde van de opgegeven waarde terug. |
| static **float** [Acos](./acos/)(**float**) | Berekent de arccosinus van de opgegeven waarde. |
| static **float** [Asin](./asin/)(**float**) | Berekent de arcsinus van de opgegeven waarde. |
| static **float** [Atan](./atan/)(**float**) | Berekent de arctangens van de opgegeven waarde. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Berekent de arctangens van de verhouding van de opgegeven waarden. |
| static **float** [Ceiling](./ceiling/)(**float**) | Geeft de kleinste gehele waarde terug die groter dan of gelijk aan de opgegeven waarde is. |
| static **float** [Cos](./cos/)(**float**) | Berekent de cosinus van de opgegeven waarde. |
| static **float** [Cosh](./cosh/)(**float**) | Berekent de hyperbolische cosinus van de opgegeven waarde. |
| static **float** [Exp](./exp/)(**float**) | Geeft e-constante tot de opgegeven macht terug. |
| static **float** [Floor](./floor/)(**float**) | Geeft de grootste gehele waarde terug die kleiner dan of gelijk aan de opgegeven waarde is. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Geeft de rest terug die ontstaat bij de deling van een opgegeven getal door een ander opgegeven getal. |
| static **float** [Log](./log/)(**float**) | Bepaalt het teken van de opgegeven ondertekende gehele waarde. |
| static **float** [Log](./log/)(**float**, **float**) | Geeft het logaritme van de opgegeven waarde in de opgegeven basis terug. |
| static **float** [Log10](./log10/)(**float**) | Geeft het logaritme base-10 van de opgegeven waarde terug. |
| static **float** [Pow](./pow/)(**float**, **float**) | Geeft de opgegeven waarde tot de opgegeven macht terug. |
| static **float** [Round](./round/)(**float**) | Rondt de opgegeven waarde af op de dichtstbijzijnde gehele waarde. |
| static **float** [Round](./round/)(**float**, int) | Rondt de opgegeven waarde af op de dichtstbijzijnde waarde met het opgegeven aantal decimale cijfers. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Rondt de opgegeven waarde af op het dichtstbijzijnde gehele getal. Een parameter bepaalt het gedrag van de functie als de opgegeven waarde even dichtbij twee dichtstbijzijnde getallen ligt. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Rondt de opgegeven waarde af op de dichtstbijzijnde waarde met het opgegeven aantal decimale cijfers. Een parameter bepaalt het gedrag van de functie als de opgegeven waarde even dichtbij twee dichtstbijzijnde getallen ligt. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Rondt de opgegeven waarde af op de dichtstbijzijnde waarde met het opgegeven aantal decimale cijfers. Een parameter bepaalt het gedrag van de functie als de opgegeven waarde even dichtbij twee dichtstbijzijnde getallen ligt. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Bepaalt het teken van de opgegeven ondertekende gehele waarde. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Bepaalt het teken van de opgegeven floating-point waarde. |
| static **float** [Sin](./sin/)(**float**) | Berekent de sinus van de opgegeven waarde. |
| static **float** [Sinh](./sinh/)(**float**) | Berekent de hyperbolische sinus van de opgegeven waarde. |
| static **float** [Sqrt](./sqrt/)(**float**) | Geeft de vierkantswortel van de opgegeven waarde terug. |
| static **float** [Tan](./tan/)(**float**) | Berekent de tangens van de opgegeven waarde. |
| static **float** [Tanh](./tanh/)(**float**) | Berekent de hyperbolische tangens van de opgegeven waarde. |
| static **float** [Truncate](./truncate/)(**float**) | Geeft een drijvende-komma waarde met enkele precisie terug waarvan het gehele deel gelijk is aan dat van de opgegeven waarde, waarbij alle decimale cijfers zijn verwijderd. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [E](./e/) | De basis van het natuurlijke logaritme. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | De constante Pi. |
| static [Tau](./tau/) | Tau-waarde. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)