---
title: Nullable
second_title: Aspose.Slides voor C++ API-referentie
description: Voorwaartse declaratie.
type: docs
weight: 1106
url: /nl/system/nullable/
---
## Nullable klasse

Forward declaration.

```cpp
template<typename T>class Nullable
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het onderliggende waardetype dat wordt uitgebreid door de [Nullable](./) klasse |

## Methoden

| Methode | Beschrijving |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object gelijk is aan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](./) object. |
| **bool** [get_HasValue](./get_hasvalue/)() const | Bepaalt of het huidige object een waarde vertegenwoordigt. |
| T [get_Value](./get_value/)() const | Retourneert een kopie van de waarde die wordt vertegenwoordigd door het huidige object. |
| int [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor het huidige object. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Retourneert de waarde die wordt vertegenwoordigd door het huidige object of de opgegeven waarde als de waarde die wordt vertegenwoordigd door het huidige object null is. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Bepaalt of het huidige object een null-waarde vertegenwoordigt. |
|  [Nullable](./nullable/)() | Construeert een instantie die een null-waarde vertegenwoordigt. |
|  [Nullable](./nullable/)(std::nullptr_t) | Construeert een instantie die null vertegenwoordigt. |
|  [Nullable](./nullable/)(const T1\&) | Construeert een instantie van de [Nullable](./) klasse die de opgegeven waarde voorstelt, geconverteerd (indien nodig) naar de onderliggende type T. |
|  [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Construeert een instantie die een waarde vertegenwoordigt die wordt vertegenwoordigd door het opgegeven [Nullable](./) object. Het opgegeven nullable object kan een waarde van een ander type vertegenwoordigen dan het onderliggende type van de geconstrueerde instantie; in dat geval wordt de vertegenwoordigde waarde geconverteerd naar een waarde van type T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Helperfunctie om te controleren of deze en **other** beide geen null zijn en een lambda aan te roepen als dat het geval is. Wordt gebruikt in implementaties. |
|  [operator const T &](./operator_const_t__and/)() const | Retourneert een constante referentie naar de waarde die wordt vertegenwoordigd door het huidige object. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object niet null is. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object niet gelijk is aan de opgegeven waarde. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object niet gelijk is aan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](./) object. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Past [operator&=()](./operator_and_equal/) toe op de waarde die wordt vertegenwoordigd door het huidige object met de opgegeven waarde als rechterargument. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Retourneert een standaard geconstrueerde instantie van de Nullable<T> klasse. |
| auto [operator+](./operator_plus/)(const T1\&) const | Somt nullable en niet-nullable waarden op. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Somt nullable waarden op. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Reset het huidige object zodat het een null-waarde vertegenwoordigt. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Past [operator+=()](./operator_plus_equal/) toe op de waarde die wordt vertegenwoordigd door het huidige object met de opgegeven waarde als rechterargument. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Past [operator+=()](./operator_plus_equal/) toe op de waarde die wordt vertegenwoordigd door het huidige object met de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](./) object als rechterargument. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Trek nullable en null-gerichte waarden af. |
| auto [operator-](./operator_minus/)(const T1\&) const | Trek nullable en niet-nullable waarden af. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Trek nullable waarden af. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Retourneert een instantie van de [Nullable](./) klasse die een null-waarde vertegenwoordigt. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Past [operator-=()](./operator_minus_equal/) toe op de waarde die wordt vertegenwoordigd door het huidige object met de opgegeven waarde als rechterargument. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Past [operator-=()](./operator_minus_equal/) toe op de waarde die wordt vertegenwoordigd door het huidige object met de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](./) object als rechterargument. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Retourneert altijd false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object kleiner is dan de opgegeven waarde door [operator<()](./operator_less/) op deze waarden toe te passen. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object kleiner is dan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](./) object door [operator<()](./operator_less/) op deze waarden toe te passen. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Retourneert altijd false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object kleiner dan of gelijk is aan de opgegeven waarde door [operator<=()](./operator_less_equal/) op deze waarden toe te passen. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object kleiner dan of gelijk is aan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](./) object door [operator<=()](./operator_less_equal/) op deze waarden toe te passen. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Kent een null toe aan het huidige object. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Vervangt de momenteel vertegenwoordigde waarde van het object door de opgegeven. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Vervangt de momenteel vertegenwoordigde waarde van het object door de opgegeven. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object null is. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object gelijk is aan de opgegeven waarde. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object gelijk is aan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](./) object. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Retourneert altijd false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object groter is dan de opgegeven waarde door [operator>()](./operator_greater/) op deze waarden toe te passen. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Bepaalt of de waarde die wordt gedragen door het huidige object groter is dan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](./) object door [operator>()](./operator_greater/) op deze waarden toe te passen. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Retourneert altijd false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object groter dan of gelijk is aan de waarde die wordt vertegenwoordigd door het opgegeven object door [operator>=()](./operator_greater_equal/) op deze waarden toe te passen. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Bepaalt of de waarde die wordt vertegenwoordigd door het huidige object groter dan of gelijk is aan de waarde die wordt vertegenwoordigd door het opgegeven [Nullable](./) object door [operator>=()](./operator_greater_equal/) op deze waarden toe te passen. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Past [operator|=()](./operator_or_equal/) toe op de waarde die wordt vertegenwoordigd door het huidige object met de opgegeven waarde als rechterargument. |
| void [reset](./reset/)() | Stelt de momenteel vertegenwoordigde waarde in op null. |
| void [set_Value](./set_value/)(const T\&) | Stelt een nieuwe waarde in voor het nullable object. |
| [String](../string/) [ToString](./tostring/)() const | Converteert de waarde die wordt vertegenwoordigd door het huidige object naar een string. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [ValueType](./valuetype/) | Een alias voor een type van de waarde die wordt vertegenwoordigd door deze klasse. |

## Opmerkingen

Stelt een waarde van het opgegeven type voor die null kan worden toegewezen. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)