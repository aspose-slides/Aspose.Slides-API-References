---
title: Index
second_title: Aspose.Slides for C++ API Reference
description: "Represents an index into a collection. The index can be from the start or from the end. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 1015
url: /system/index/
---
## Index class


Represents an index into a collection. The index can be from the start or from the end. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Determines whether the current instance and the specified [Index](./) represent the same position. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Creates an [Index](./) that is relative to the end of the collection. |
| static constexpr [Index](./) [get_End](./get_end/)() | Gets an [Index](./) object representing the end of a collection. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | Gets a value that indicates whether the index is from the end. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Gets an [Index](./) object representing the start of a collection. |
| constexpr **int32_t** [get_Value](./get_value/)() const | Gets the index value. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Returns a hash code for the current index. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Converts the current [Index](./) into an offset from the start of a collection with the specified length. |
| constexpr [Index](./index/)() | Constructs an instance that represents the start of a collection. |
| constexpr [Index](./index/)(**int32_t**) | Constructs an instance that represents the specified position from the start of a collection. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Constructs an instance that represents the specified index. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)