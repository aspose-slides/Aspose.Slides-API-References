---
title: ReadOnlySpan
second_title: Aspose.Slides voor C++ API-referentie
description: Voor gebruik binnen de Span klasse.
type: docs
weight: 1210
url: /nl/system/readonlyspan/
---
## ReadOnlySpan klasse


Voor gebruik binnen [Span](../span/) klasse.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de span. Deze klasse biedt een typeveilige manier om met aaneengesloten reeksen van objecten in een alleen-lezen modus te werken. Het kan worden gebruikt om arrays, stapelarrays of ruwe pointers te omhullen terwijl grenzencontrole behouden blijft. De [ReadOnlySpan](./) bezit het geheugen waarnaar hij wijst niet - het is slechts een weergave van bestaand geheugen. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Construeert een alleen-lezen span vanuit een reguliere span. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Converteert een array naar een [ReadOnlySpan](./). |

## Opmerkingen

Stelt een alleen-lezen aaneengesloten regio van willekeurig geheugen voor.

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)