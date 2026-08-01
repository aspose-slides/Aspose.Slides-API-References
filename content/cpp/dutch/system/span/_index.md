---
title: Span
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een aaneengesloten regio van willekeurig geheugen voor, vergelijkbaar met C++20's std::span."
type: docs
weight: 1262
url: /nl/system/span/
---
## Span klasse

Stelt een aaneengesloten regio van willekeurig geheugen voor, vergelijkbaar met C++20's std::span.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen in de span. Deze klasse biedt een type-veilige manier om te werken met aaneengesloten reeksen van objecten. Het kan worden gebruikt om arrays, stack-arrays of ruwe pointers te omhullen, terwijl de bounds-controle behouden blijft. De [Span](./) bezit het geheugen waarnaar het wijst niet - het is slechts een weergave van bestaand geheugen. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Clear](./clear/)() const | Wis de inhoud van de span door alle elementen op de standaardwaarde in te stellen. |
| void [Fill](./fill/)(const T\&) const | Vult de span met de opgegeven waarde. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Converteert een array naar een [Span](./). |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)