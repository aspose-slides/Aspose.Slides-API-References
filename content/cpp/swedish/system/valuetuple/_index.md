---
title: ValueTuple
second_title: Aspose.Slides för C++ API-referens
description: Klass som representerar en ValueTuple-datastruktur.
type: docs
weight: 1444
url: /sv/system/valuetuple/
---
## ValueTuple-klass


Klass som representerar en [ValueTuple](./) datastruktur.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Bestämmer om det aktuella och det angivna objektet är identiska. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | Hämtar referensen till värdet av [ValueTuple](./)-objektets komponent. |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | Hämtar värdet av [ValueTuple](./)-objektets komponent. |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Dekonstruerar objektet till detta värde-tuple. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returnerar en referens till [TypeInfo](../typeinfo/)-objektet som representerar [ValueTuple](./)-klasstypinformation. |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) |  |
## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)