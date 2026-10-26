---
title: Enum
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt methoden die enkele bewerkingen uitvoeren op waarden van enumtype. Dit is een statisch type zonder instantie-services. Je mag nooit exemplaren ervan maken op welke manier dan ook.
type: docs
weight: 1587
url: /nl/system/enum/
---
## Enumstruct

Biedt methoden die enkele bewerkingen uitvoeren op waarden van enumtype. Dit is een statisch type zonder instantie-services. Je mag nooit exemplaren ervan maken op welke manier dan ook.

```cpp
template<class E,class Guard>class Enum
```

### Templateparameters

| Parameter | Beschrijving |
| --- | --- |
| E | Het type enum waarop de klasse werkt |
| Guard | Service-type-argument waarvan het doel is te garanderen dat **E** een enum-type is |
## Methodes

| Methode | Beschrijving |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Voert de rekenkundige vergelijking uit van de waarden van de opgegeven enumeratie-constant(en). |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Geeft de naam terug van de enumeratie-constante die de opgegeven waarde heeft. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Geeft de naam terug van de enumeratie-constante die de opgegeven waarde heeft. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Geeft een array terug met namen van alle leden van enumeratie **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Geeft het onderliggende type van de enumeratie terug. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Geeft een array terug met alle leden van enumeratie **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Bepaalt of de opgegeven bits zijn gezet in een bit-representatie van de opgegeven enumwaarde. |
| static **bool** [IsDefined](./isdefined/)(E) | Bepaalt of de opgegeven waarde een lid is van het enumeratietype **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Bepaalt of de opgegeven waarde een lid is van het enumeratietype **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Bepaalt of de waarde met de opgegeven naam tot de leden van enum **E** behoort. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Converteert de opgegeven string naar een equivalente enum-constante. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Probeert de opgegeven string te converteren naar een equivalente enum-constante. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Probeert de opgegeven string te converteren naar een equivalente enum-constante. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Alias voor het onderliggende type van de enum. |

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)