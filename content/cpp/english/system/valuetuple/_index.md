---
title: ValueTuple
second_title: Aspose.Slides for C++ API Reference
description: Class that represents a ValueTuple data structure.
type: docs
weight: 1379
url: /system/valuetuple/
---
## ValueTuple class


Class that represents a [ValueTuple](./) data structure.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Determines if the current and the specified objects are identical. |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<Index, tuple_t\>\& [Item](./item/)() | Gets the reference to value of the [ValueTuple](./) object's component. |
| const std::tuple_element_t\<Index, tuple_t\>\& [Item](./item/)() const | Gets the value of the [ValueTuple](./) object's component. |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returns a reference to the [TypeInfo](../typeinfo/) object representing the [ValueTuple](./) class type information. |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Constructs a tuple object. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)