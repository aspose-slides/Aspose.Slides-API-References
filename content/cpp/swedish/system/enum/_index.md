---
title: Enum
second_title: Aspose.Slides för C++ API-Referens
description: Tillhandahåller metoder som utför vissa operationer på värden av enum-typ. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 1587
url: /sv/system/enum/
---
## Enumstruktur

Tillhandahåller metoder som utför vissa operationer på värden av enum-typ. Detta är en statisk typ utan instansservice. Du bör aldrig skapa instanser av den på något sätt.

```cpp
template<class E,class Guard>class Enum
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| E | Typen av enum vars värden klassen hanterar |
| Guard | Tjänsttypargument vars syfte är att säkerställa att **E** är en uppräkningsbar typ |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Utför den aritmetiska jämförelsen av värdena för de angivna uppräkningskonstanterna. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Returnerar namnet på uppräkningskonstanten som har det angivna värdet. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Returnerar namnet på uppräkningskonstanten som har det angivna värdet. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Returnerar en array som innehåller namnen på alla medlemmar av uppräkning **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Returnerar den underliggande typen för uppräkningen. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Returnerar en array som innehåller alla medlemmar av uppräkning **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Avgör om de angivna bitarna är satta i en bitrepresentation av det angivna enum-värdet. |
| static **bool** [IsDefined](./isdefined/)(E) | Avgör om det angivna värdet är en medlem av uppräkningstypen **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Avgör om det angivna värdet är en medlem av uppräkningstypen **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Avgör om värdet med det angivna namnet finns bland medlemmarna i enum **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Konverterar den angivna strängen till motsvarande enum-konstant. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Försöker konvertera den angivna strängen till motsvarande enum-konstant. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Försöker konvertera den angivna strängen till motsvarande enum-konstant. |
## Typdefinitioner

| Typdef | Beskrivning |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Alias för enumens underliggande typ. |

## Se också

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)