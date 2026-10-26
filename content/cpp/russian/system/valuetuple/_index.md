---
title: ValueTuple
second_title: Справочник API Aspose.Slides для C++
description: Класс, представляющий структуру данных ValueTuple.
type: docs
weight: 1418
url: /ru/system/valuetuple/
---
## Класс ValueTuple

Class that represents a [ValueTuple](./) data structure.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Методы

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Determines if the current and the specified objects are identical. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<Index, tuple_t\>\& [Item](./item/)() | Gets the reference to value of the [ValueTuple](./) object's component. |
| const std::tuple_element_t\<Index, tuple_t\>\& [Item](./item/)() const | Gets the value of the [ValueTuple](./) object's component. |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Deconstructs object to this value tuple. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returns a reference to the [TypeInfo](../typeinfo/) object representing the [ValueTuple](./) class type information. |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Constructs a tuple object. |
## См. также

* Namespace [System](../)
* Library [Aspose.Slides](../../)