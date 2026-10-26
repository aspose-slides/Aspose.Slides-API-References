---
title: ValueTuple
second_title: Aspose.Slides C++ API-referencia
description: Osztály, amely egy ValueTuple adatstruktúrát képvisel.
type: docs
weight: 1444
url: /hu/system/valuetuple/
---
## ValueTuple osztály

Osztály, amely egy [ValueTuple](./) adatstruktúrát képvisel.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Megállapítja, hogy a jelenlegi és a megadott objektumok azonosak-e. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | Lekéri a [ValueTuple](./) objektum komponensének értékére mutató referenciát. |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | Lekéri a [ValueTuple](./) objektum komponensének értékét. |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Dekonstruálja az objektumot ebbe az érték tuple-ba. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Visszaad egy referenciát a [TypeInfo](../typeinfo/) objektumra, amely a [ValueTuple](./) osztály típusinformációját képviseli. |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Létrehoz egy tuple objektumot. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)