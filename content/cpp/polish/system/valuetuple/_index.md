---
title: ValueTuple
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Klasa reprezentująca strukturę danych ValueTuple.
type: docs
weight: 1444
url: /pl/system/valuetuple/
---
## ValueTuple klasa

Klasa reprezentująca strukturę danych [ValueTuple](./).

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Określa, czy bieżący i określony obiekt są identyczne. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | Zwraca referencję do wartości komponentu obiektu [ValueTuple](./). |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | Zwraca wartość komponentu obiektu [ValueTuple](./). |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Dekonstruktuje obiekt do tej krotki wartości. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Zwraca referencję do obiektu [TypeInfo](../typeinfo/) reprezentującego informacje o typie klasy [ValueTuple](./). |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Tworzy obiekt krotki. |
## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)