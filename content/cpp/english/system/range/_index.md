---
title: Range
second_title: Aspose.Slides for C++ API Reference
description: "Represents a range with a start and end index. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 1197
url: /system/range/
---
## Range class


Represents a range with a start and end index. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Creates a range that begins at the start of the collection and ends at the specified end index. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Determines whether the current range is equal to the specified range. |
| static constexpr [Range](./) [get_All](./get_all/)() | Returns a [Range](./) that represents the whole collection. |
| const [Index](../index/)\& [get_End](./get_end/)() const | Gets the End index. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Gets the Start index. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Returns a hash code for the current range. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Computes the zero-based start offset and length for the specified collection length. |
| constexpr [Range](./range/)() | Constructs an empty range. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Constructs a [Range](./) from the specified start and end indexes. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Creates a range that begins at the specified start index and extends to the end of the collection. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)