---
title: ValueTuple
second_title: Aspose.Slides voor C++ API-referentie
description: Klasse die een ValueTuple-gegevensstructuur vertegenwoordigt.
type: docs
weight: 1444
url: /nl/system/valuetuple/
---
## ValueTuple klasse

Klasse die een [ValueTuple](./) gegevensstructuur vertegenwoordigt.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Bepaalt of de huidige en de opgegeven objecten identiek zijn. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | Haalt de referentie op naar de waarde van de component van het [ValueTuple](./)-object. |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | Haalt de waarde op van de component van het [ValueTuple](./)-object. |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Deconstrueert het object naar deze waardetuple. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retourneert een referentie naar het [TypeInfo](../typeinfo/)-object dat de type-informatie van de [ValueTuple](./)-klasse vertegenwoordigt. |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Construeert een tuple-object. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)