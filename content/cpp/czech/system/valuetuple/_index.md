---
title: ValueTuple
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Třída, která představuje datovou strukturu ValueTuple.
type: docs
weight: 1444
url: /cs/system/valuetuple/
---
## ValueTuple třída

Třída, která představuje datovou strukturu [ValueTuple](./).

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Určuje, zda jsou aktuální a zadané objekty identické. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | Získá odkaz na hodnotu komponenty objektu [ValueTuple](./). |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | Získá hodnotu komponenty objektu [ValueTuple](./). |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Rozloží objekt do tohoto value tuple. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Vrátí odkaz na objekt [TypeInfo](../typeinfo/) představující informace o typu třídy [ValueTuple](./). |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Vytvoří objekt tuple. |

## Viz také

* jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)